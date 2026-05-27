---
permalink: /
author_profile: true
stylesheets:
  - /assets/css/home.css
redirect_from: 
  - /about/
  - /about.html
---
<h1 class="main-heading">Hi there <img src="images/Hi.gif" width="40px"> Welcome to my Homepage!</h1>

Hi! I work on AI, survive on instant noodles, and submit papers 3 minutes before deadlines.

Feel free to reach out if you are interested in collaboration or potential opportunities.

News
---------------
<div class="news-box">
  <ul class="news-list">
<li><span class="news-date"><em>2026.02</em></span> 🎉🎉 Our Work on LVLM Reasoning Hallucination have been accepted by CVPR 2026. Thanks all of the co-authors!</li>

<li><span class="news-date"><em>2026.02</em></span> 🎉🎉 Our Work on LVLM Token Pruning have been accepted by TCSVT 2026. Thanks all of the co-authors!</li>

<li><span class="news-date"><em>2026.01</em></span> 🎉🎉 Our Work on LVLM Reasoning have been accepted by ICLR 2026. Thanks all of the co-authors!</li>

<li><span class="news-date"><em>2025.09</em></span> 🎉🎉 I become a PhD student at Fudan University.</li>

<li><span class="news-date"><em>2023.09</em></span> 🎉🎉 I began my studies at Fudan University.</li>
  </ul>
</div>




Publications
--------------
<button class="pub-button active" onclick="filterPublications(event, 'all')">Core Publications</button>
<button class="pub-button" onclick="filterPublications(event, 'list')">Full Publications List</button>

(* equal contribution · &dagger; corresponding author · &Dagger; project leader)

<div id="core-publications" class="publication-view" data-publication-view="core">

<div class="publication-card" data-category="all">
  <div style="display: flex; align-items: center;">
    <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;">
      <img src="images/CVPR_poster.png" alt="Envision, Attend, Then Respond" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;">
    </div>
    <div>
      <strong>Envision, Attend, Then Respond: Counterfactual Hallucination Mitigation in Large Vision-Language Models</strong><br>
      <i style="font-size: 13px;">
        <strong>Yuxuan Liang</strong>, et al.
      </i><br>
      We propose an "Envision–Attend–Respond" framework that mitigates hallucinations in Large Vision-Language Models through counterfactual visual reasoning, encouraging the model to first imagine alternative scenes, re-attend to grounded evidence, and then generate faithful responses.
      <br>
      <b><i style="color:#83a1c7;">CVPR 2026 &nbsp;</i></b>
      <a href="#"><em>[arXiv]</em></a>
      <a href="#"><em>[code]</em></a>
    </div>
  </div>
</div>

<div class="publication-card" data-category="all">
  <div style="display: flex; align-items: center;">
    <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;">
      <img src="images/ICLR_poster.png" alt="Decomposition of Concept-Level Rules" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;">
    </div>
    <div>
      <strong>Decomposition of Concept-Level Rules in Visual Scenes</strong><br>
      <i style="font-size: 13px;">
        <strong>Yuxuan Liang</strong>, et al.
      </i><br>
      We study how high-level visual reasoning rules can be decomposed into interpretable concept-level primitives, enabling models to discover, reuse, and compose rules across diverse visual scenes for more systematic and generalizable reasoning.
      <br>
      <b><i style="color:#83a1c7;">ICLR 2026 &nbsp;</i></b>
      <a href="#"><em>[arXiv]</em></a>
      <a href="#"><em>[code]</em></a>
    </div>
  </div>
</div>

<div class="publication-card" data-category="all">
  <div style="display: flex; align-items: center;">
    <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;">
      <img src="images/TCSVT.png" alt="Pyramid Token Pruning" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;">
    </div>
    <div>
      <strong>Pyramid Token Pruning for High-Resolution Large Vision-Language Models via Region, Token, and Instruction-Guided Importance</strong><br>
      <i style="font-size: 13px;">
        <strong>Yuxuan Liang</strong>, et al.
      </i><br>
      We propose a pyramid token pruning strategy for high-resolution LVLMs that jointly leverages region-level, token-level, and instruction-guided importance, substantially reducing visual token cost while preserving fine-grained understanding.
      <br>
      <b><i style="color:#83a1c7;">TCSVT 2026 &nbsp;</i></b>
      <a href="#"><em>[arXiv]</em></a>
      <a href="#"><em>[code]</em></a>
    </div>
  </div>
</div>

</div>


<div id="full-publications" class="publication-view" data-publication-view="list" hidden>
  <ul class="full-publication-list">
    <li>
      <span class="pub-list-badge">CVPR 2026</span>
      <span class="pub-list-title">Envision, Attend, Then Respond: Counterfactual Hallucination Mitigation in Large Vision-Language Models</span><br>
      <span class="pub-list-authors"><strong>Yuxuan Liang</strong>, et al.</span>
      <span class="pub-list-links"><a href="#">[arXiv]</a><a href="#">[code]</a></span>
    </li>
    <li>
      <span class="pub-list-badge">ICLR 2026</span>
      <span class="pub-list-title">Decomposition of Concept-Level Rules in Visual Scenes</span><br>
      <span class="pub-list-authors"><strong>Yuxuan Liang</strong>, et al.</span>
      <span class="pub-list-links"><a href="#">[arXiv]</a><a href="#">[code]</a></span>
    </li>
    <li>
      <span class="pub-list-badge">TCSVT 2026</span>
      <span class="pub-list-title">Pyramid Token Pruning for High-Resolution Large Vision-Language Models via Region, Token, and Instruction-Guided Importance</span><br>
      <span class="pub-list-authors"><strong>Yuxuan Liang</strong>, et al.</span>
      <span class="pub-list-links"><a href="#">[arXiv]</a><a href="#">[code]</a></span>
    </li>
  </ul>
</div>

<script src="assets/js/show_publications.js"></script>
<script src="assets/js/pub_media_rotator.js"></script>


Projects
--------
<div class="project-card" data-category="project"> 
  <div style="display: flex; align-items: center;">
    <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;">
      <img src="images/2.png" alt="ManiUniCon" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;">
    </div>
    <div> 
      <strong>WowPage</strong><br>
      <i style="font-size: 13px;">
        <a href="https://wd7ang.github.io" target="_blank"><strong>Weidong Tang</strong></a>,
        <a href="https://selen-suyue.github.io/" target="_blank"><strong>Yue Su</strong></a>.
      </i><br>
      In collaboration with Yue Su, I refined and improved his original homepage template. A clean standalone template version is coming soon.
      <br> 
      <b><i style="color:#83a1c7;">Project &nbsp;</i></b> 
      <a href=""><em>[code]</em></a> 
    </div>
  </div> 
</div>


Awards
--------
- *3026.01*, Successfully survived 17 consecutive paper deadlines without touching grass.
- *3025.09*, Best Excuse Generation Award, SleepFormer Research Group.
- *3025.06*, Outstanding Contributor to Instant Noodle Consumption Efficiency.
- *3024.12*, GPU Emotional Damage Scholarship (Full Funding).
- *3024.08*, Ranked Top 0.1% Worldwide in “I’ll Fix It Tomorrow”.



Services
--------
- *3026.06 – Present*, Chief Coffee Consumption Officer, Midnight Research Lab.
- *3026.01 – Present*, Full-time Debugger of Problems Created by Myself.
- Reviewer for Journal of Unfinished Projects.
- Area Chair for Conference on Last-Minute Submissions (CLMS).
- Volunteer Therapist for Burned-out GPUs.



Talks
--------
- *3026.07*, “How to Finish a Paper 3 Minutes Before Deadline.”
- *3026.05*, “Large Language Models and Large Amounts of Caffeine.”
- *3025.11*, “On the Emotional Stability of GPUs Under Extreme Stress.”
- *3025.08*, “Instant Noodles as Scalable Research Infrastructure.”
- *3025.03*, “Sleep is Temporary, Camera-Ready is Forever.”