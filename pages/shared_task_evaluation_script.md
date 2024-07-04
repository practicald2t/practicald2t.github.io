---
layout: default
---
 <div class="forms-container">

 <div class="forms">
    <img src="assets/images/github-logo.png">
    <a href="https://github.com/kasnerz/factgenie/">
    <p style="font-size: large">Factgenie Toolking for Annotating and Visualizing LLM Hallucinations</p>
    </a>
</div>

</div>

# Running an Evaluation Script for the Shared Task Datasets

- We use the https://github.com/kasnerz/factgenie/ framework in the shared task for running the LLM evaluation (annotation of the data-to-text system outputs using LLMs).
    - **We strongly encourage to run it locally and visualize and evaluate your outputs in factgenie**
    - _factgenie_ has cli `factgenie run-llm-eval` for running the evaluation from CLI. 
    - _factgenie_ can run the same evaluation interactively in a browser at `http://127.0.0.1:5000/llm-eval`. It is great for debugging the prompt. 
- We use _factgenie_ webserver also for visualization of the annotation and the datasets themselves.
- Before using any dataset one needs to prepare dataloading of the datasets in _factgenie_. Luckily, we have added the shared tasks `st-*` datasets to _factgenie_ for you.

## Looking at the result: Shared Task datasets and annotations
_Before we start. Let's look at running _factgenie_ instance deployed at:

<a href="https://quest.ms.mff.cuni.cz/namuddis/factgenie/browse?dataset=st24-openweather&split=dev&example_idx=0">
    https://quest.ms.mff.cuni.cz/namuddis/factgenie/browse?dataset=st24-openweather&split=dev&example_idx=0 </br>
    <img src="../assets/images/factgenie_eval_script/factgenie_st24_openweather_dev_llama3_annotation.png" alt="Example from deployed factgenie toolkit at the address https://quest.ms.mff.cuni.cz/namuddis/factgenie/browse?dataset=st24-openweather&split=dev&example_idx=0">
</a>

- You see an _Openweather_ domain input data examples released as `st24-openweather` dataset.
- The output from a _mistral_ model was generated using https://github.com/kasnerz/quintd/ (in particular this [version](https://github.com/kasnerz/quintd/pull/4))
- The annotations with id `st24-demo-opnweather-dev-llama3` were generated using the following command

```
factgenie run-llm-eval \
  --campaign_name st24-demo-openweather-dev-llama3 \
  --dataset_name st24-openweather \
  --split dev \
  --llm_output_name mistral \
  --llm_metric_config factgenie/llm-eval/ollama-llama3.yaml
```


## Running the evaluation

1. Go through the [README.md](https://github.com/kasnerz/factgenie/blob/main/README.md) and install dependencies.
2. [(Optionally) Look at how we added the shared [task datasets](https://github.com/kasnerz/factgenie/pull/35#issue-2384606283) in the section `How to evaluate the existing outputs?`
3. At the same [PR](https://github.com/kasnerz/factgenie/pull/35#issue-2384606283) look at the section `How to evaluate the existing outputs?` and learn how to run the `factgenie run-llm-eval` command
4. Finally, look how you can add your model outputs to factgenie so you can run `factgenie run-llm-eval` on your model output. Here is [the example](https://github.com/kasnerz/factgenie/pull/35/files#r1665339740) for _mistral_ model.
    For your outputs by your `awesome_model` which you used to generate outputs for `st24-gsmarena` `dev` split you need to create file  `factgenie/outputs/st24-gsmarena/dev/awesome_model.json` with the [structure described in the example](factgenie/outputs/st24-gsmarena/dev/mistral.json).