---
layout: splash
permalink: /
excerpt: "Practical D2T at INLG 2024<br/> Tokyo, Japan, 23 Sept, 2024"
layout: single
classes: wide
header:
  overlay_color: "#000"
  overlay_filter: "0.1"
  overlay_image: /assets/images/banner_new.jpg
---
## The 2nd Workshop on Practical LLM-assisted Data-to-Text Generation

# News
- 09/09/2024: The [workshop programme](https://practicald2t.github.io/_pages/programme) and [accepted papers list](https://practicald2t.github.io/_pages/accepted_papers) are now available!
- 06/09/2024: Craig Thomson (ADAPT/DCU), and Marco Valentino (Neuro-Symbolic AI Group / Idiap Research Institute) confirmed as keynote speakers!
- 24/07/2024: Based on multiple requests, we decided to update the deadline. The submission page is now open until Friday, July 26, 23.59 AoE. Good luck with your submissions!
- 01/07/2024: We created a public Google group [https://groups.google.com/g/public-d2t2024/](https://groups.google.com/g/public-d2t2024/) where you can follow the news and get technical feedback. For private matters see the [/contacts page](https://practicald2t.github.io/_pages/contacts).
- 28/06/2024: We now have a date! Practical D2T 2024 will be on 23 September @INLG 2024, Tokyo, Japan!
- 20/06/2024: Call for paper is [online](https://practicald2t.github.io/_pages/cfp)!
- 19/06/2024: the official Practical D2T 2024 website is online!

# Background
Natural Language Generation (NLG) has been an active area of research for decades, both academically and industrially. Data-to-text (D2T) generation ([Reiter and Dale, 1997](https://www.cambridge.org/core/journals/natural-language-engineering/article/abs/building-applied-natural-language-generation-systems/FEB374A3FF652F06D8567A6FAB2EF36E); [Gatt and Krahmer, 2018](https://www.jair.org/index.php/jair/article/view/11173)) is the NLG task where a system describes structured data in natural language. Traditionally, commercial D2T systems have been based on symbolic approaches ([Dale, 2020](https://books.google.cz/books?hl=en&lr=&id=MnEjBsMIxxsC&oi=fnd&pg=PA1&dq=info:F-d-6SfJfnwJ:scholar.google.com&ots=5KT1isSwf-&sig=U0WO3CoTWItFhZtvkJCvuGfQ9cM&redir_esc=y#v=onepage&q&f=false); [Leppänen et al., 2017](https://aclanthology.org/W17-3528/)), i.e. handcrafted rules or templates. More experimental approaches to D2T, such as E2E and Transformer-based systems ([Dušek et al., 2020](https://www.sciencedirect.com/science/article/pii/S0885230819300919); [Sharma et al., 2022](https://arxiv.org/abs/2207.12571)) have been limited to research because of well-known issues like knowledge gaps, lack of factuality, and hallucination ([Ji et al., 2023](https://aclanthology.org/2023.findings-emnlp.123/); [Wang et al., 2023](https://aclanthology.org/2023.emnlp-main.949/)).

The recently introduced instruction-tuned, multi-task Large Language Models (LLMs) promise to become a viable alternative to rule-based D2T systems. They exhibit the ability to capture knowledge, follow instructions, and produce coherent text from various domains ([Sanh et al., 2021](https://arxiv.org/abs/2110.08207); [Ouyang et al., 2022](https://proceedings.neurips.cc/paper_files/paper/2022/hash/b1efde53be364a73914f58805a001731-Abstract-Conference.html)). However, even the best LLMs still suffer from well-known issues of neural models, such as lack of controllability and risk of producing harmful text. Recent research thus proposed various approaches to improve the semantic accuracy of LLMs D2T, including prompt tuning ([Su et al., 2022](https://aclanthology.org/2022.naacl-main.290/); [Ye and Durrett, 2022](https://proceedings.neurips.cc/paper_files/paper/2022/hash/c402501846f9fe03e2cac015b3f0e6b1-Abstract-Conference.html)), targeted fine-tuning ([Zhang et al., 2024](https://arxiv.org/abs/2402.17193)), Retrieval Augmented Generation (RAG) ([Jiang et al., 2023](https://arxiv.org/abs/2305.06983); [Chen et al., 2024](https://ojs.aaai.org/index.php/AAAI/article/view/29728)), external tool integration ([Wang et al., 2024](https://arxiv.org/abs/2402.02420)), and neuro-symbolic approaches ([Sarker et al, 2021](https://arxiv.org/abs/2105.05330); [Hitzler et al., 2022](https://books.google.cz/books?hl=it&lr=&id=uFtcEAAAQBAJ&oi=fnd&pg=PR1&dq=Sarker+et+al,+2021+neuro-symbolic&ots=s8GC0CDB-c&sig=WMNbMuSy_fDcfco3TSBwySxWi5c&redir_esc=y#v=onepage&q=Sarker%20et%20al%2C%202021%20neuro-symbolic&f=false)).

Practical D2T 2024 aims to build a space for researchers to discuss and present innovative work on D2T systems using LLMs. Building upon the 2023 edition’s hackathon, Practical D2T 2024 opens up a broader range of activities, including a special track for neuro-symbolic D2T approaches and a hackathon focused on the evaluation and semantic accuracy of D2T using LLMs.

# Important dates
Note: All deadlines are 23:59 UTC-12.

Main and special track:
- **First call for paper:** 20 June
- <span style="color: #276275;">**Regular paper submission:**  ~~22 July~~ 26 July</span>
- **Notification of acceptance:**  19 August
- **Camera-ready:**  28 August
- **Workshop:** 23 September @INLG 2024, Tokyo, Japan

# Invited Talks

|![Craig Thomson](/assets/images/2024/Craig Thomson - small.png) |![Marco Valentino](/assets/images/2024/Marco Valentino - small.png) |
|:-------------------------------------------------:|:------------------------------------------:|
|<b>Craig Thomson</b>, <br>ADAPT/DCU | <b>Marco Valentino</b>, <br>Neuro-Symbolic AI Group / Idiap Research Institute|


## Organizers


<div class="organizer-container" style="display: flex; flex-wrap: wrap; gap: 20px;">

  <div class="organizer" style="display: inline-block; text-align: center; width: 120px;">
      <img src="../assets/images/organizers/standard-size/simone_balloccu.png" alt="Simone Ballocu" style="width: 100px; height: 100px; border-radius: 50%;">
      <a href="https://uccollab.github.io/">
          <p style="margin: 5px 0; font-weight: bold;">Simone Balloccu</p>
      </a>
      <span>Charles University</span>
  </div>

  <div class="organizer" style="display: inline-block; text-align: center; width: 120px;">
      <img src="../assets/images/organizers/standard-size/zdenek_kasner.png" alt="Zdeněk Kasner" style="width: 100px; height: 100px; border-radius: 50%;">
      <a href="https://kasnerz.github.io">
          <p style="margin: 5px 0; font-weight: bold;">Zdeněk Kasner</p>
      </a>
      <span>Charles University</span>
  </div>

  <div class="organizer" style="display: inline-block; text-align: center; width: 120px;">
      <img src="../assets/images/organizers/standard-size/ondrej_platek.png" alt="Ondřej Plátek" style="width: 100px; height: 100px; border-radius: 50%;">
      <a href="http://opla.cz">
          <p style="margin: 5px 0; font-weight: bold;">Ondřej Plátek</p>
      </a>
      <span>Charles University</span>
  </div>

  <div class="organizer" style="display: inline-block; text-align: center; width: 120px;">
      <img src="../assets/images/organizers/standard-size/patricia_schmidtova.png" alt="Patricia Schmidtova" style="width: 100px; height: 100px; border-radius: 50%;">
      <a href="https://patuchen.github.io/">
          <p style="margin: 5px 0; font-weight: bold;">Patrícia Schmidtová</p>
      </a>
      <span>Charles University</span>
  </div>

  <div class="organizer" style="display: inline-block; text-align: center; width: 120px;">
      <img src="../assets/images/organizers/standard-size/kristyna_onderkova.png" alt="Kristýna Onderková" style="width: 100px; height: 100px; border-radius: 50%;">
      <p style="margin: 5px 0; font-weight: bold;">Kristýna Onderková</p>
      <span>Charles University</span>
  </div>

  <div class="organizer" style="display: inline-block; text-align: center; width: 120px;">
      <img src="../assets/images/organizers/standard-size/mateusz_lango.png" alt="Mateusz Lango" style="width: 100px; height: 100px; border-radius: 50%;">
      <a href="https://ufal.mff.cuni.cz/mateusz-lango">
          <p style="margin: 5px 0; font-weight: bold;">Mateusz Lango</p>
      </a>
      <span>Charles University</span>
  </div>

  <div class="organizer" style="display: inline-block; text-align: center; width: 120px;">
      <img src="../assets/images/organizers/standard-size/ondrej_dusek.png" alt="Ondřej Dušek" style="width: 100px; height: 100px; border-radius: 50%;">
      <a href="https://tuetschek.github.io/">
          <p style="margin: 5px 0; font-weight: bold;">Ondřej Dušek</p>
      </a>
      <span>Charles University</span>
  </div>

  <div class="organizer" style="display: inline-block; text-align: center; width: 120px;">
      <img src="../assets/images/organizers/standard-size/lucie_flek.png" alt="Lucie Flek" style="width: 100px; height: 100px; border-radius: 50%;">
      <a href="https://caisa-lab.github.io/members/lucie-flek.html">
          <p style="margin: 5px 0; font-weight: bold;">Lucie Flek</p>
      </a>
      <span>University of Bonn</span>
  </div>

  <div class="organizer" style="display: inline-block; text-align: center; width: 120px;">
      <img src="../assets/images/organizers/standard-size/ehud_reiter.png" alt="Ehud Reiter" style="width: 100px; height: 100px; border-radius: 50%;">
      <a href="https://ehudreiter.com/">
          <p style="margin: 5px 0; font-weight: bold;">Ehud Reiter</p>
      </a>
      <span>University of Aberdeen</span>
  </div>

  <div class="organizer" style="display: inline-block; text-align: center; width: 120px;">
      <img src="../assets/images/organizers/standard-size/dimitra_gkatzia.png" alt="Dimitra Gkatzia" style="width: 100px; height: 100px; border-radius: 50%;">
      <a href="https://dimitragkatzia.wordpress.com">
          <p style="margin: 5px 0; font-weight: bold;">Dimitra Gkatzia</p>
      </a>
      <span>Edinburgh Napier University</span>
  </div>

  <div class="organizer" style="display: inline-block; text-align: center; width: 120px;">
      <img src="../assets/images/organizers/standard-size/simon_mille.png" alt="Simon Mille" style="width: 100px; height: 100px; border-radius: 50%;">
      <a href="https://www.adaptcentre.ie/experts/simon-mille/">
          <p style="margin: 5px 0; font-weight: bold;">Simon Mille</p>
      </a>
      <span>ADAPT Centre</span>
  </div>

</div> <!--organizer-container!-->

## Previous Years
<a href="/2023/"> 2023: 1st Workshop on Practical LLM-assisted Data-to-Text Generation</a>

## Acknowledgments
<p>Funded by the European Union (ERC, NG-NLG, 101039303)</p>
<img src="assets/images/erc.png" style="max-width: 300px;" alt="ERC">





