---
layout: default
---
 <div class="forms-container">

 <div class="forms">
    <img src="assets/images/github-logo.png">
    <a href="https://github.com/kasnerz/factgenie/">
    <p style="font-size: large">See __factgenie__ on GitHub</p>
    </a>
</div>
 <div class="forms">
    <img src="assets/images/factgenie-logo.png">
    <a href="https://quest.ms.mff.cuni.cz/namuddis/factgenie/browse?dataset=st24-openweather&split=dev&example_idx=0">
    <p style="font-size: large">Browse shared tasks `st-*` datasets in deployed factgenie instance</p>
    </a>
</div>
</div>

# Shared task
Practical D2T 2024 features a shared task on improving the semantic accuracy of D2T systems. The shared task requires three main efforts from you:

1. Build your own LLM-assisted D2T system, which takes structured data as input (e.g. weather data), and produces a summary of it as output.
2. Use LLMs to perform error annotation on the summaries produced by your system. This means annotating the spans of text containing errors, specifying the type of error and the reason why the span was flagged. We will provide a starting code for this (more info below).
3. (*optional*) Modify our starting code to create your custom evaluation.

### The data
For this shared task, we provide a new dataset (the "known domain data") with recent data (in the form of JSONs and CSVs) from four domains:

- [**openweather**](https://quest.ms.mff.cuni.cz/namuddis/factgenie/browse?dataset=st24-openweather&split=dev&example_idx=0): weather data,
- [**gsmarena**](https://quest.ms.mff.cuni.cz/namuddis/factgenie/browse?dataset=st24-gsmarena&split=dev&example_idx=0): product descriptions (specifically smartphone specs),
- [**ice_hockey**](https://quest.ms.mff.cuni.cz/namuddis/factgenie/browse?dataset=st24-ice_hockey&split=dev&example_idx=0): sports results (specifically hockey),
- [**owid**](https://quest.ms.mff.cuni.cz/namuddis/factgenie/browse?dataset=st24-owid&split=dev&example_idx=0): time-series covering data from miscellaneous origins.

### You can download the dataset from [here](https://practicald2t.github.io/assets/shared_task_data/known_domains.zip). 
Each domain contains a dev set (100 examples) and a test set (50 examples).

For evaluation purposes, we prepared the datasets in [factgenie](https://github.com/kasnerz/factgenie/blob/c8fb56aa17482dd04c9341b3bb68a2f65a7fe355/factgenie/loaders/practicald2t_st24.py) and you can browse them in the [factgenie-demo](https://quest.ms.mff.cuni.cz/namuddis/factgenie/browse?dataset=st24-openweather&split=dev&example_idx=0).
In _factgenie_, we evaluate baseline outputs from the _mistral_ model (select the annotations `st24-demo-openweather-dev-llama3` annotation created using `llama3` demo).

## Expression of interest in participating
If you wish to take part in the shared task, send an email to [d2t2024@googlegroups.com](mailto:d2t2024@googlegroups.com), with object "Shared Task Participation", and let us know the list of members of your team (name, surname and affiliation), and a team name.

Optionally, you may want to join also the public Google group https://groups.google.com/g/public-d2t2024/ where we will share news and you may post FAQs. 

## Phase 1: System development
**Deadline:** 29 July 2024 23:59 AoE

During this phase, use the known domain data to develop and evaluate your LLM-assisted D2T system. For evaluation, we will provide an initial script that prompts LLM to perform error span annotation, as a proxy for semantic accuracy. You must develop your system on the dev set and evaluate it on the test set.

## Evaluation script and the baseline

**[See the dedicated page of how we evaluated the baseline LLM outputs using _factgenie_](/pages/shared_task_evaluation_script)!**


### Variation of the evaluation script 
Our script can be customised to vary the used LLMs, prompts, errors, annotation attributes and more. We encourage you to modify/improve the script to explore different evaluation methodologies. For example, you may:
- Explore other types of errors
- Use a different LLM
- Experiment with prompt engineering 

Suggested LLMs are:
- Llama3
- Phi3
- Qwen2
- Mistral

You can provide your own custom model checkpoints (along with details on the model characteristics), as long as the format is compatible with the aforementioned ones. Find more info about this in [FAQs](#faq). Every participant can provide up to **one** custom evaluation script. **You are not allowed to alter the output format of our evaluation script, as it is necessary to keep it fixed to make it comparable across different participants.**

Once you have finalized your system, you must submit:
- Your best output
- Evaluation results (both our original one and any custom one you may implement)
- The eventual modified evaluation script you produced

All your submissions should be on the test set only. We will keep an updated leaderboard on this webpage, with an overview of all teams' results. You can submit multiple times while you improve your system, but only the last one you send will be considered.

## Phase 2: Output submission and surprise domain evaluation
**Deadline:** 5 Aug  2024 23:59 AoE

Upon submission, you will receive an additional test set covering a surprise domain, to test the robustness of your system/evaluation. You will have one week to send back your system's outputs on the new test set. If you developed a custom evaluation (i.e. modifying the script), you must provide results for both the initial and modified scripts.

## Phase 3: Final automatic and human evaluation
Once we receive all submissions, we will evaluate every received output against every received evaluation script. This means that, if you submit a custom evaluation script, you will be able to know how it performs on other participants' systems.

Finally, we will run a human evaluation, asking annotators to perform error annotation on all summaries from all participants. We will correlate human judgments against all the available automatic evaluations. At the workshop, we will present the results and insights of our evaluation: how every script works on different system outputs, and how they correlate with human annotators. The system reaching the highest correlation with humans will be declared the winner of the competition. Results and participants’ system descriptions will be featured in the workshop proceedings. 

# Submission
For your participation to be valid, you will need to submit your
  1. Best output (textual summaries produced by their system)
  2. Results of our evaluation script (error annotation for all the produced summaries across all test sets)
  3. Eventual custom evaluation results, along with the modified script and every element (i.e. model checkpoint) necessary to run it
  4. System description (up to 4 pages)

Submissions must be sent to [d2t2024@googlegroups.com](mailto:d2t2024@googlegroups.com), with object "$TEAM submission known" and "$TEAM submission surprise" for the known domain and surprise domain respectively. $TEAM is your chosen team name. The system description must follow the submission template and guidelines issued by INLG 2024.

# FAQs
<a name="faq"></a>
<span style="color: #276275;">**Q:** Where does the shared task dataset come from?</span>  
<span style="color: #276275;">**A:**</span> Our dataset is sourced by querying existing open APIs to retrieve tabular data across various domains. We adopt this approach as LLMs potentially met this kind of data during pre-training/RL. We query very recent data tables to minimise the risk of data contamination.

<span style="color: #276275;">**Q:** Can I use my custom model (e.g. fine-tuned, architectural changes etc) if it is not among the suggested ones?</span>  
<span style="color: #276275;">**A:**</span> As we will have to re-run every custom evaluation against all participants' submitted outputs, we aim to do it in the most painless way possible. If you plan to submit an evaluation script using a custom model, please send us model checkpoints (HuggingFace format) and make your script compatible with Pytorch and Ollama (versions to be announced). Generally, we should be able just to run your evaluation script and get the results. 

<span style="color: #276275;">**Q:** How big can the model I will use for custom evaluation be?</span>  
<span style="color: #276275;">**A:**</span> Your model should be able to run on an NVidia A100 or A40 (48GB VRAM). The use of quantisation is allowed but should, again, be set up by you in the script you will submit.

<span style="color: #276275;">**Q:** I want to develop a neurosymbolic D2T system/evaluation script for the shared task. Can I?</span>  
<span style="color: #276275;">**A:**</span> Yes! In light of our workshop's interest in neuro-symbolic D2T, participants of the shared task are welcome to include symbolic knowledge, intermediate representations etc. Please remember that you still need to adhere to the above points.

Should you have any other questions, feel free to contact the organisers.

## Acknowledgments
<p>Funded by the European Union (ERC, NG-NLG, 101039303)</p>
<img src="../assets/images/erc.png" style="max-width: 300px;" alt="ERC">

<hr>
<div class="footer">
    © 2023. Built using Jekyll <a href="https://github.com/pages-themes/hacker">Hacker theme</a> and icons from flaticon.com.
  </div>

