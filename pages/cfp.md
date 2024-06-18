---
layout: default
---
 <div class="forms-container">

 <!-- <div class="forms">
    <img src="assets/images/github-logo.png">
    <a href="https://github.com/practicald2t/hackathon/">
    <p style="font-size: large">Hackathon – Github</p>
    </a>
</div> -->
</div>


# Call for Papers

### Workshop topic and content
Practical D2T 2024 will be a full-day in-person-only event. We welcome contributions from both original unpublished work and non-archival submissions, in the form of long (8 pages) or short (4 pages) papers, on topics including but not limited to:

- Design, implementation and evaluation of LLM-assisted D2T systems
- Cross-domain adaption of LLMs for D2T
- User perceptions and acceptance of LLM-generated text in D2T
- Bias, fairness and red-teaming issues in LLM-assisted D2T systems
- Leveraging LLMs for D2T in low-resource languages and domains
- Error analysis and debugging techniques for LLM-assisted D2T
- Human-in-the-loop approaches for improving LLM-assisted D2T
- Comparison between LLM-assisted D2T and traditional symbolic approaches

### Special Track: Neuro-Symbolic D2T
Research is currently seeing a renewed interest in developing systems combining neural and symbolic approaches to improve explainability and reduce dependence on training data. Practical D2T 2024 will feature a special track on neuro-symbolic approaches to D2T. Submissions for papers in the special track follow the same requirements and procedure as the main workshop submissions.

### Shared task: Improving Semantic Accuracy in LLM-assisted D2T
This year will feature a shared task on improving semantic accuracy of D2T systems. Participants will build an LLM-assisted D2T system to generate textual reports from various domains, such as weather forecasting, product descriptions or sports reports. We will provide testing data obtained from public APIs, to limit potential previous exposure to the used LLMs. 

We encourage participants to focus on system robustness and objective evaluation, rather than metrics scores. The shared task will adopt the following protocol:

1. **Development and evaluation on known domains:** we will release a dataset covering four (4) D2T domains, on which participants will base the development of their system. For evaluation, we will provide an initial script that uses LLMs to assess criteria like semantic accuracy and fluency.
2. **Variation of the evaluation script:** the script we will provide can be customised with different LLMs and prompts. Participants are encouraged to modify/improve the script to explore different evaluation methodologies.
Participants can use Llama3, Phi3, Qwen2, and Mistral, or provide their own custom model checkpoints (along with details on the model characteristics), as long as the format is compatible with the aforementioned ones.
3. **Output submission and surprise domain evaluation:** participants will submit their best output, evaluation results and eventual modified evaluation script. Upon submission, they will receive an additional test-set covering a surprise domain, to test the robustness of their system/evaluation. Participants will have one week to send back their outputs on the new test-set.
4. **Final automatic evaluation:** once we receive all submissions, we will evaluate every received output against every received evaluation script.
5. **Final human evaluation:** Finally, we will run a human evaluation on all the received outputs, and correlate human judgements against the automatic evaluations.

At the workshop, we will present results and insights of our evaluation: how every script works on different system outputs, and how they correlate with human annotators. The system reaching the highest correlation with humans will be declared winner of the competition. Results and participants’ system descriptions will be featured in the workshop proceedings. 

# Important dates
NOTE: All deadlines are 23:59 UTC-12.

- **Call for paper:**  14 June
- **Evaluation script and data release for known domains (shared task):**  24 June
- **Regular paper submission (main & special track, archival & non-archival):** 22 July
- **Known domains system output submission & surprise domain data release:** 29 July
- **Surprise domain system outputs submission:** 5 August
- **System description submission (shared task):** 12 August
- **Notification of acceptance (main, special track and shared task):**  19 August
- **Camera-ready (main, special track and shared task):**  28 August
- **Workshop:** 23/24 September (to be decided)


# Submission

We welcome two types of papers: regular workshop papers and non-archival submissions. Regular workshop papers will be included in the workshop proceedings. Papers should use the INLG templates. The page counts exclude references and appendices. All submissions will be given one extra page of space to address reviewers’ comments.

- **Long papers**: *up to eight (8) pages* describing substantial, completed work, with concrete evaluation wherever appropriate.
- **Short papers**: *up to four (4) pages of content*. Short papers may describe preliminary contributions, negative results, opinion pieces, or a small set of interesting results.
- **Shared task**: participants will be required to send their
  1. Best output (textual summaries produced by their system)
  2. Results of our evaluation script
  3. Eventual custom evaluation results, along with the modified script and every element (i.e. model checkpoint) necessary to run it

<!---
Participants will send their submission through $TODO_CODALAB_EMAIL_OR_BOTH_? with the subject "[Submission] {title of your work}" before the submission deadline (see below).--->

### Submission procedure and templates
Please submit short and long papers directly through the [INLG submission portal](https://softconf.com/n/inlg2024/user/scmd.cgi?scmd=submitNew), selecting "Click HERE to make a new Practical Data-to-Text submission". 
Choose the appropriate *submission type* (Long/Short Paper), *track* (Main/Neuro-Symbolic D2T) and *Proceedings Type* (Archival/Non-Archival).
Submissions must follow the submission template and guidelines issued by INLG 2024.

Participants of the shared task will send their submission through $TODO_CODALAB_EMAIL_OR_BOTH_? with the subject "[Submission] {title of your work}" before the submission deadline (see below)

### Multiple submission policy
We allow multiple submissions for non-archival work.

### Optional Supplementary Materials: Appendices, Software and Data
Additionally, supplementary materials can be added in an appendix. Should you make any software or data available within the paper, these need to be fully anonymised.

## Acknowledgments
<p>Funded by the European Union (ERC, NG-NLG, 101039303)</p>
<img src="assets/images/erc.png" style="max-width: 300px;" alt="ERC">

<hr>
<div class="footer">
    © 2023. Built using Jekyll <a href="https://github.com/pages-themes/hacker">Hacker theme</a> and icons from flaticon.com.
  </div>
