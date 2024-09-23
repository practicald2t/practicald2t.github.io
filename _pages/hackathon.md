---
layout: splash
excerpt: "Practical D2T at INLG 2024<br/> Tokyo, Japan, 23 Sept, 2024"
permalink: /_pages/hackathon/
classes: wide
header:
  overlay_color: "#000"
  overlay_filter: "0.1"
  overlay_image: /assets/images/banner_new.jpg
---

# Hackathon

 <div class="forms-container">

 <div class="forms">
    <a href="https://github.com/ufal/factgenie/">
    <p style="font-size: large">See <i>factgenie</i> on GitHub</p>
    </a>
</div>
 <div class="forms">
    <a href="https://quest.ms.mff.cuni.cz/namuddis/factgenie/browse?dataset=st24-openweather&split=dev&example_idx=0">
    <p style="font-size: large">Browse some examples of datasets in the deployed <i>factgenie</i> instance</p>
    </a>
</div>
</div>

Practical D2T 2024 features a hackathon focused on improving the semantic accuracy of D2T systems.
Join us and get hands-on experience with easy and quick LLM as judge and comparable human annotations!
Let's explore the NLG outputs together at the hackathon on Monday 💪

Join us on September 23rd, and explore LLMs for:

1. Generating textual summaries from structured data as input
2. Detecting different categories of errors in the obtained summaries 
3. Comparing error detection capabilities with those of human annotators.

We will use <a href="https://github.com/ufal/factgenie/"><i>factgenie</i></a>, our web framework for annotating and visualizing word spans in textual model outputs.
With <a href="https://github.com/ufal/factgenie/"><i>factgenie</i></a>, both humans and LLMs can be used to annotate various span-based errors including semantic inaccuracies or irrelevant text.

We will work on various domains using recent structured data in the form of JSONs and CSVs.
You can take a first look at the data in the online [factgenie-demo](https://quest.ms.mff.cuni.cz/namuddis/factgenie/browse?dataset=st24-openweather&split=dev&example_idx=0) we prepared.
You can also see some examples of LLM-driven D2T and error annotation: try selecting the dataset (top left) _st24-openweather_, and the annotations (top right) _st24-demo-openweather-dev-llama3_.
You will see what kind of weather summaries _Mistral_ produces, and how _LLama 3_ tries to spot eventual errors.

## Communication channels

We encourage you to [join the Some INLG Discord server](https://discord.gg/QzdUDQMXzW) which will be the official communication channel for [INLG 2024](https://inlg2024.github.io/).

We will use **[dedicated practical-d2t-workshop-2024 channel](https://discord.com/channels/788758570183032894/1285176845121359944)** for communication during the hackathon.

We will use are existing Google Group [d2t2024@googlegroups.com](https://groups.google.com/g/d2t2024) only as a backup solution.

## Phase 1: Intro + generation (50 min)

During the first part of the hackathon, we will give you a quick tour of <a href="https://github.com/ufal/factgenie/"><i>factgenie</i></a> and its features.
This phase will be focused on generation, so we will work together on prompting open LLMs to produce summaries from structured data.
Feel free to variate your prompts, parameters and play with different datasets to get the best output!

## Phase 2: Annotation and results (80 minutes)

Next, it's time to see how good the obtained summaries are!
We will explore the second feature of <a href="https://github.com/ufal/factgenie/"><i>factgenie</i></a>, that is error annotation.
During this phase, you can play with different LLMs as error annotators.
Just like before, you can variate the model, prompts and parameters, but also, introduce new error categories besides those we will provide.

At the same time, we will gather some human error annotation, to compare them with the LLMs' ones.
It is up to you to decide if you want to help us by quickly annotating a couple of summaries, focus on annotation through LLMs, or both!

Finally, we will correlate human annotation against LLMs ones, and discuss the results.

Should you have any other questions, feel free to contact the organisers.

## Acknowledgments
<p>Funded by the European Union (ERC, NG-NLG, 101039303)</p>
<img src="/assets/images/erc.png" style="max-width: 300px;" alt="ERC">
