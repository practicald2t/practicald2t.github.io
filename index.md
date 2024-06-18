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


# Backgound
Natural Language Generation (NLG) has been an active area of research for decades, both academically and industrially. Data-to-text (D2T) generation (Reiter and Dale,1997; Gatt and Krahmer, 2018) is the NLG task where a system describes structured data in natural language. Traditionally, commercial D2T systems have been based on symbolic approaches (Dale, 2020; Leppänen et al., 2017), i.e. handcrafted rules or templates. More experimental approaches to D2T, such as Transformer-based systems (Dušek et al., 2020; Sharma et al., 2022) have been limited to research because of well-known issues like knowledge gaps, lack of factuality, and hallucination (Ji et al., 2023; Wang et al., 2023).

The recently introduced instruction-tuned, multi-task Large Language Models (LLMs) promise to become a viable alternative to rule-based D2T systems. They exhibit the ability to capture knowledge, follow instructions, and produce coherent text from various domains (Sanh et al., 2021; Ouyang et al., 2022). However, even the best LLMs still suffer from well-known issues of neural models, such as lack of controllability and risk of producing harmful text. Recent research thus proposed various approaches to improve the semantic accuracy of LLMs D2T, including prompt tuning (Lee et al., 2022; Ye and Durrett, 2022), targeted fine-tuning (Zhang et al., 2024), Retrieval Augmented Generation (RAG) (Jiang et al., 2023; Chen et al., 2024), external tool integration (Wang et al., 2024), and neuro-symbolic approaches (Sarker et al, 2021; Hitzler et al., 2022).

Motivated by this development, Practical D2T 2024 aims to build a space for researchers to discuss and present innovative work on D2T systems using LLMs. Building upon the 2023 edition’s hackathon, Practical D2T 2024 opens up a broader range of activities, including a special track for neuro-symbolic D2T approaches and a shared task in D2T evaluation focused on semantic accuracy.

### Workshop topic anc content
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
The workshop will feature a shared task on improving semantic accuracy of D2T systems. Participants will build an LLM-assisted D2T system to generate textual reports from various domains, such as weather forecasting, product descriptions or sports reports. We will provide testing data obtained from public APIs, to limit potential previous exposure to the used LLMs. 

We encourage participants to focus on system robustness and objective evaluation, rather than metrics scores. The shared task will adopt the following protocol:

1. Development and evaluation on known domains: we will release a dataset covering four (4) D2T domains, on which participants will base the development of their system. For evaluation, we will provide an initial script that uses LLMs to assess criteria like semantic accuracy and fluency.
2. Variation of the evaluation script: the script we will provide can be customised with different LLMs and prompts. Participants are encouraged to modify/improve the script to explore different evaluation methodologies.
Participants can use Llama3, Phi3, Qwen2, and Mistral, or provide their own custom model checkpoints (along with details on the model characteristics), as long as the format is compatible with the aforementioned ones.
3. Output submission and surprise domain evaluation: participants will submit their best output, evaluation results and eventual modified evaluation script. Upon submission, they will receive an additional test-set covering a surprise domain, to test the robustness of their system/evaluation. Participants will have one week to send back their outputs on the new test-set.
4. Final automatic evaluation: once we receive all submissions, we will evaluate every received output against every received evaluation script.
5. Final human evaluation: Finally, we will run a human evaluation on all the received outputs, and correlate human judgements against the automatic evaluations.

Results and insights of our evaluation: how every script works on different system outputs, and how they correlate with human annotators. The system reaching the highest correlation with humans will be declared winner of the competition. Results and participants’ system descriptions will be featured in the workshop proceedings. 

# Important dates
NOTE: All deadlines are 23:59 UTC-12.

- **Call for paper:  14 June
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

### Long papers
Long papers must describe substantial, completed work, with concrete evaluation wherever appropriate. Long papers may consist of up to eight (8) pages of content, plus unlimited pages of references. 

### Short papers
Short paper submissions may include preliminary contributions, negative results, opinion pieces, or a small set of interesting results. Short papers may consist of up to four (4) pages of content, plus unlimited pages of references.

### Shared task participation
Participants will send their submission through $TODO with the subject "[Submission] {title of your work}" before the submission deadline (see below).

### Multiple submission policy
We allow multiple submissions for non-archival work.

### Submission procedure and templates
Please submit short and long papers directly $TODO
Please follow the submission guidelines issued by INLG 2024.

### Optional Supplementary Materials: Appendices, Software and Data
Additionally, supplementary materials can be added in an appendix. Should you make any software or data available within the paper, these need to be fully anonymised.

# Contacts
For any query, contact us at [practicald2t@googlegroups.com](mailto:practicald2t@googlegroups.com)
If you have any problem with the above mail group, contact [balloccu@ufal.mff.cuni.cz](balloccu@ufal.mff.cuni.cz)

## Organizers

<div class="organizer-container">

<div class="organizer">
    <img src="assets/images/organizers/standard-size/simone_balloccu.png" alt="Simone Ballocu">
    <a href="https://uccollab.github.io/">
        <p>Simone Balloccu</p>
    </a>
    <span>Charles University</span>
</div>

<div class="organizer">
        <img src="assets/images/organizers/standard-size/zdenek_kasner.png" alt="Zdeněk Kasner">
        <a href="https://kasnerz.github.io">
            <p>Zdeněk Kasner</p>
        </a>
        <span>Charles University</span>
    </div>
    
<div class="organizer">
    <img src="assets/images/organizers/standard-size/ondrej_platek.png" alt="Ondřej Plátek">
    <a href="http://opla.cz">
    <p>Ondřej Plátek</p>
     </a>
    <span>Charles University</span>
</div>

<div class="organizer">
    <img src="assets/images/organizers/standard-size/patricia_schmidtova.png" alt="Patricia Schmidtova">
    <a href="https://patuchen.github.io/">
        <p>Patrícia Schmidtová</p>
    </a>
    <span>Charles University</span>
</div>

<div class="organizer">
    <img src="assets/images/organizers/standard-size/kristyna_onderkova.png" alt="Kristýna Onderková">
    <!-- <a href="TBD"> -->
        <p>Kristýna Onderková</p>
    <!-- </a> -->
    <span>Charles University</span>
</div>
<div class="organizer">
    <img src="assets/images/organizers/standard-size/mateusz_lango.png" alt="Mateusz Lango">
    <a href="https://ufal.mff.cuni.cz/mateusz-lango">
        <p>Mateusz Lango</p>
    </a>
    <span>Charles University</span>
</div>



<div class="organizer">
    <img src="assets/images/organizers/standard-size/ondrej_dusek.png" alt="Ondřej Dušek">
    <a href="https://tuetschek.github.io/">
        <p>Ondřej Dušek</p>
    </a>
    <span>Charles University</span>
</div>

<div class="organizer">
    <img src="assets/images/organizers/standard-size/lucie_flek.png" alt="Lucie Flek">
    <!-- <a href="https://lucieflek.github.io"> -->
    <a href="https://caisa-lab.github.io/members/lucie-flek.html">
        <p>Lucie Flek</p>
    </a>
    <span>University of Bonn</span>
</div>

<div class="organizer">
    <img src="assets/images/organizers/standard-size/ehud_reiter.png" alt="Ehud Reiter">
    <a href="https://ehudreiter.com/">
        <p>Ehud Reiter</p>
    </a>
    <span>University of Aberdeen</span>
</div>


<div class="organizer">
    <img src="assets/images/organizers/standard-size/dimitra_gkatzia.png" alt="Dimitra Gkatzia">
    <a href="https://dimitragkatzia.wordpress.com">
        <p>Dimitra Gkatzia</p>
    </a>
    <span>Edinburgh Napier University</span>
</div>

<div class="organizer">
    <img src="assets/images/organizers/standard-size/simon_mille.png" alt="Simon Mille">
    <a href="https://www.adaptcentre.ie/experts/simon-mille/">
        <p>Simon Mille</p>
    </a>
    <span>ADAPT Centre</span>
</div>

</div> <!--organizer-container!-->

## Acknowledgments
<p>Funded by the European Union (ERC, NG-NLG, 101039303)</p>
<img src="assets/images/erc.png" style="max-width: 300px;" alt="ERC">


## Previous Years
<a href="/2023/"> 2023: 1st Workshop on Practical LLM-assisted Data-to-Text Generation</a>


<hr>
<div class="footer">
    © 2023. Built using Jekyll <a href="https://github.com/pages-themes/hacker">Hacker theme</a> and icons from flaticon.com.
  </div>
