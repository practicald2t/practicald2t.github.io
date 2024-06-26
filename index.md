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


# Background
Natural Language Generation (NLG) has been an active area of research for decades, both academically and industrially. Data-to-text (D2T) generation ([Reiter and Dale, 1997](https://www.cambridge.org/core/journals/natural-language-engineering/article/abs/building-applied-natural-language-generation-systems/FEB374A3FF652F06D8567A6FAB2EF36E); [Gatt and Krahmer, 2018](https://www.jair.org/index.php/jair/article/view/11173)) is the NLG task where a system describes structured data in natural language. Traditionally, commercial D2T systems have been based on symbolic approaches ([Dale, 2020](https://books.google.cz/books?hl=en&lr=&id=MnEjBsMIxxsC&oi=fnd&pg=PA1&dq=info:F-d-6SfJfnwJ:scholar.google.com&ots=5KT1isSwf-&sig=U0WO3CoTWItFhZtvkJCvuGfQ9cM&redir_esc=y#v=onepage&q&f=false); [Leppänen et al., 2017](https://aclanthology.org/W17-3528/)), i.e. handcrafted rules or templates. More experimental approaches to D2T, such as E2E and Transformer-based systems ([Dušek et al., 2020](https://www.sciencedirect.com/science/article/pii/S0885230819300919); [Sharma et al., 2022](https://arxiv.org/abs/2207.12571)) have been limited to research because of well-known issues like knowledge gaps, lack of factuality, and hallucination ([Ji et al., 2023](https://aclanthology.org/2023.findings-emnlp.123/); [Wang et al., 2023](https://aclanthology.org/2023.emnlp-main.949/)).

The recently introduced instruction-tuned, multi-task Large Language Models (LLMs) promise to become a viable alternative to rule-based D2T systems. They exhibit the ability to capture knowledge, follow instructions, and produce coherent text from various domains ([Sanh et al., 2021](https://arxiv.org/abs/2110.08207); [Ouyang et al., 2022](https://proceedings.neurips.cc/paper_files/paper/2022/hash/b1efde53be364a73914f58805a001731-Abstract-Conference.html)). However, even the best LLMs still suffer from well-known issues of neural models, such as lack of controllability and risk of producing harmful text. Recent research thus proposed various approaches to improve the semantic accuracy of LLMs D2T, including prompt tuning ([Su et al., 2022](https://aclanthology.org/2022.naacl-main.290/); [Ye and Durrett, 2022](https://proceedings.neurips.cc/paper_files/paper/2022/hash/c402501846f9fe03e2cac015b3f0e6b1-Abstract-Conference.html)), targeted fine-tuning ([Zhang et al., 2024](https://arxiv.org/abs/2402.17193)), Retrieval Augmented Generation (RAG) ([Jiang et al., 2023](https://arxiv.org/abs/2305.06983); [Chen et al., 2024](https://ojs.aaai.org/index.php/AAAI/article/view/29728)), external tool integration ([Wang et al., 2024](https://arxiv.org/abs/2402.02420)), and neuro-symbolic approaches ([Sarker et al, 2021](https://arxiv.org/abs/2105.05330); [Hitzler et al., 2022](https://books.google.cz/books?hl=it&lr=&id=uFtcEAAAQBAJ&oi=fnd&pg=PR1&dq=Sarker+et+al,+2021+neuro-symbolic&ots=s8GC0CDB-c&sig=WMNbMuSy_fDcfco3TSBwySxWi5c&redir_esc=y#v=onepage&q=Sarker%20et%20al%2C%202021%20neuro-symbolic&f=false)).

Practical D2T 2024 aims to build a space for researchers to discuss and present innovative work on D2T systems using LLMs. Building upon the 2023 edition’s hackathon, Practical D2T 2024 opens up a broader range of activities, including a special track for neuro-symbolic D2T approaches and a shared task in D2T evaluation focused on semantic accuracy.

# Important dates
Note: All deadlines are 23:59 UTC-12.

Main and special track:
- **First call for paper:** 20 June
- <span style="color: #276275;">**Regular paper submission:** 22 July</span>
- **Notification of acceptance:**  19 August
- **Camera-ready:**  28 August
- **Workshop:** 23 September @INLG 2024, Tokyo, Japan


Shared task:
- **Evaluation script and data release for known domains (shared task):**  24 June
- <span style="color: #276275;">**Known domains system output submission & surprise domain data release:** 29 July</span>
- <span style="color: #276275;">**Surprise domain system outputs submission:** 5 August</span>
- <span style="color: #276275;">**System description submission (shared task):** 12 August</span>
- **Notification of acceptance:**  19 August
- **Camera-ready:**  28 August

<!--

# Important dates
Note: All deadlines are 23:59 UTC-12.

- **First call for paper:** 20 June
- **Evaluation script and data release for known domains (shared task):**  24 June
- **Known domains system output submission & surprise domain data release:** 29 July
- ### **Regular paper submission:** 22 July
- **Surprise domain system outputs submission:** 5 August
- **System description submission (shared task):** 12 August
- **Notification of acceptance:**  19 August
- **Camera-ready:**  28 August
- **Workshop:** 23/24 September at INLG, Tokyo, Japan (to be decided)


-->


# News
- 28/06/2024: We now have a date! Practical D2T 2024 will be on 23 September @INLG 2024, Tokyo, Japan!
- 25/06/2024: Known domain data for the shared task is [online](https://practicald2t.github.io/pages/shared_task)!
- 20/06/2024: Call for paper is [online](https://practicald2t.github.io/pages/cfp)!
- 19/06/2024: the official Practical D2T 2024 website for is online!

# Invited Talks

To be announced

<div class="organizer-container">

<div class="organizer">
    <img src="../assets/images/organizers/standard-size/simone_balloccu.png" alt="Simone Ballocu">
    <a href="https://uccollab.github.io/">
        <p>Simone Balloccu</p>
    </a>
    <span>Charles University</span>
</div>

<div class="organizer">
        <img src="../assets/images/organizers/standard-size/zdenek_kasner.png" alt="Zdeněk Kasner">
        <a href="https://kasnerz.github.io">
            <p>Zdeněk Kasner</p>
        </a>
        <span>Charles University</span>
    </div>
    
<div class="organizer">
    <img src="../assets/images/organizers/standard-size/ondrej_platek.png" alt="Ondřej Plátek">
    <a href="http://opla.cz">
    <p>Ondřej Plátek</p>
     </a>
    <span>Charles University</span>
</div>

<div class="organizer">
    <img src="../assets/images/organizers/standard-size/patricia_schmidtova.png" alt="Patricia Schmidtova">
    <a href="https://patuchen.github.io/">
        <p>Patrícia Schmidtová</p>
    </a>
    <span>Charles University</span>
</div>

<div class="organizer">
    <img src="../assets/images/organizers/standard-size/kristyna_onderkova.png" alt="Kristýna Onderková">
    <!-- <a href="TBD"> -->
        <p>Kristýna Onderková</p>
    <!-- </a> -->
    <span>Charles University</span>
</div>
<div class="organizer">
    <img src="../assets/images/organizers/standard-size/mateusz_lango.png" alt="Mateusz Lango">
    <a href="https://ufal.mff.cuni.cz/mateusz-lango">
        <p>Mateusz Lango</p>
    </a>
    <span>Charles University</span>
</div>



<div class="organizer">
    <img src="../assets/images/organizers/standard-size/ondrej_dusek.png" alt="Ondřej Dušek">
    <a href="https://tuetschek.github.io/">
        <p>Ondřej Dušek</p>
    </a>
    <span>Charles University</span>
</div>

<div class="organizer">
    <img src="../assets/images/organizers/standard-size/lucie_flek.png" alt="Lucie Flek">
    <!-- <a href="https://lucieflek.github.io"> -->
    <a href="https://caisa-lab.github.io/members/lucie-flek.html">
        <p>Lucie Flek</p>
    </a>
    <span>University of Bonn</span>
</div>

<div class="organizer">
    <img src="../assets/images/organizers/standard-size/ehud_reiter.png" alt="Ehud Reiter">
    <a href="https://ehudreiter.com/">
        <p>Ehud Reiter</p>
    </a>
    <span>University of Aberdeen</span>
</div>


<div class="organizer">
    <img src="../assets/images/organizers/standard-size/dimitra_gkatzia.png" alt="Dimitra Gkatzia">
    <a href="https://dimitragkatzia.wordpress.com">
        <p>Dimitra Gkatzia</p>
    </a>
    <span>Edinburgh Napier University</span>
</div>

<div class="organizer">
    <img src="../assets/images/organizers/standard-size/simon_mille.png" alt="Simon Mille">
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
