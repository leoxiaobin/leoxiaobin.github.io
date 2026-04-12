---
permalink: /
title: "Bin Xiao"
excerpt: "Bin Xiao builds multimodal and agentic AI systems at Microsoft AI."
layout: homepage
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<div class="research-home">
  <header class="research-home__hero">
    <div class="research-home__hero-texture" aria-hidden="true"></div>
    <div class="research-home__portrait" aria-hidden="true"></div>

    <div class="research-home__container research-home__hero-inner">
      <div class="research-home__copy">
        <h1 class="research-home__brand">Bin Xiao</h1>
        <p class="research-home__headline">Multimodal systems, visual intelligence, and agentic model training.</p>
        <p class="research-home__support">
          Member of Technical Staff at Microsoft AI. Recent work includes Phi-3 Vision, Florence, CvT, and HRNet.
        </p>
        <div class="research-home__actions">
          <a class="research-home__button research-home__button--primary" href="#selected-work">Selected publications</a>
          <a class="research-home__button research-home__button--secondary" href="https://scholar.google.com/citations?view_op=list_works&hl=en&user=t5HZdzoAAAAJ" target="_blank" rel="noopener">Google Scholar</a>
        </div>
      </div>
    </div>
  </header>

  <section class="research-home__section research-home__section--program" id="program">
    <div class="research-home__container research-home__program-grid">
      <div class="research-home__section-heading research-home__section-heading--compact">
        <h2>Research Program</h2>
        <p>Research centered on compact multimodal systems, large-scale data curation, and agentic training that can move from paper into product.</p>
      </div>

      <ul class="program-list">
        <li>
          <h3>Vision-language training</h3>
          <p>Small multimodal models designed for strong perception, grounding, and practical reasoning.</p>
        </li>
        <li>
          <h3>Data curation at scale</h3>
          <p>Training data pipelines that improve model quality, breadth, and reliability across tasks.</p>
        </li>
        <li>
          <h3>Agentic and coding models</h3>
          <p>Post-training methods for reasoning, action, and tool-using systems that operate in real workflows.</p>
        </li>
      </ul>
    </div>
  </section>

  <section class="research-home__section research-home__section--paper" id="trajectory">
    <div class="research-home__container">
      <div class="research-home__section-heading">
        <h2>Research Highlights</h2>
        <p>Selected milestones across recent multimodal post-training, reasoning, and dense vision research.</p>
      </div>

      <ol class="trajectory-list">
        <li>
          <span class="trajectory-list__year">2025–present</span>
          <p>Reasoning, agentic, and coding model training.</p>
        </li>
        <li>
          <span class="trajectory-list__year">2024</span>
          <p>Led <a href="https://huggingface.co/microsoft/Phi-3-vision-128k-instruct" target="_blank" rel="noopener">Phi-3 Vision</a> and <a href="https://huggingface.co/microsoft/Phi-3.5-vision-instruct" target="_blank" rel="noopener">Phi-3.5 Vision</a>, helping define a strong generation of small multimodal LLMs.</p>
        </li>
        <li>
          <span class="trajectory-list__year">2020–2023</span>
          <p>Led Florence and co-authored <a href="https://arxiv.org/pdf/2111.11432" target="_blank" rel="noopener">Florence-1</a> and <a href="https://arxiv.org/pdf/2311.06242.pdf" target="_blank" rel="noopener">Florence-2</a>; Florence-2 was selected as a CVPR 2024 oral presentation.</p>
        </li>
        <li>
          <span class="trajectory-list__year">2018–2021</span>
          <p>Co-authored <a href="https://openaccess.thecvf.com/content/ICCV2021/papers/Wu_CvT_Introducing_Convolutions_to_Vision_Transformers_ICCV_2021_paper.pdf" target="_blank" rel="noopener">CvT</a>, <a href="https://arxiv.org/pdf/1908.07919" target="_blank" rel="noopener">HRNet</a>, and <a href="http://openaccess.thecvf.com/content_ECCV_2018/papers/Bin_Xiao_Simple_Baselines_for_ECCV_2018_paper.pdf" target="_blank" rel="noopener">SimpleBaseline</a>, three papers that became durable reference points in vision research.</p>
        </li>
      </ol>
    </div>
  </section>

  <section class="research-home__section research-home__section--sand" id="selected-work">
    <div class="research-home__container">
      <div class="research-home__section-heading">
        <h2>Selected Publications</h2>
        <p>A concise reading path through papers and systems that most clearly represent the work.</p>
      </div>

      <div class="publication-list">
        <article class="publication-list__item">
          <p class="publication-list__meta">2024 · Technical report · multimodal LLM</p>
          <h3>Phi-3 Technical Report: A Highly Capable Language Model Locally on Your Phone</h3>
          <p>Compact multimodal capability designed to bring strong language and vision performance onto everyday devices.</p>
          <p class="publication-list__links"><a href="https://arxiv.org/abs/2404.14219" target="_blank" rel="noopener">Paper</a><a href="https://huggingface.co/microsoft/Phi-3-vision-128k-instruct" target="_blank" rel="noopener">Model</a></p>
        </article>

        <article class="publication-list__item">
          <p class="publication-list__meta">2024 · CVPR oral · unified vision model</p>
          <h3>Florence-2: Advancing a Unified Representation for a Variety of Vision Tasks</h3>
          <p>A unified representation for captioning, OCR, grounding, segmentation, and open-ended vision-language tasks.</p>
          <p class="publication-list__links"><a href="https://arxiv.org/pdf/2311.06242.pdf" target="_blank" rel="noopener">Paper</a><a href="https://huggingface.co/microsoft/Florence-2-large" target="_blank" rel="noopener">Model</a></p>
        </article>

        <article class="publication-list__item">
          <p class="publication-list__meta">2019 · CVPR · dense prediction backbone</p>
          <h3>Deep High-Resolution Representation Learning for Human Pose Estimation</h3>
          <p>The HRNet family introduced a high-resolution backbone that became a durable reference point for dense vision tasks.</p>
          <p class="publication-list__links"><a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Sun_Deep_High-Resolution_Representation_Learning_for_Human_Pose_Estimation_CVPR_2019_paper.pdf" target="_blank" rel="noopener">Paper</a><a href="https://github.com/leoxiaobin/deep-high-resolution-net.pytorch" target="_blank" rel="noopener">Code</a></p>
        </article>
      </div>

      <p class="research-home__more-link"><a href="https://scholar.google.com/citations?view_op=list_works&hl=en&user=t5HZdzoAAAAJ" target="_blank" rel="noopener">View full publication list</a></p>
    </div>
  </section>

  <section class="research-home__section research-home__section--paper" id="recognition">
    <div class="research-home__container">
      <div class="research-home__section-heading">
        <h2>Honors and Awards</h2>
        <p>Selected recognitions, including challenge results and highly cited vision work.</p>
      </div>

      <ul class="simple-list">
        <li>Florence-2 was accepted as a CVPR 2024 oral presentation.</li>
        <li>HRNet ranks among the most cited CVPR 2019 papers, with more than 5,000 citations.</li>
        <li>CvT ranks among the most cited ICCV 2021 papers, with more than 2,000 citations.</li>
        <li>1st place in Look into Person Challenge 2019 and PoseTrack Multi-Person Pose Tracking Challenge 2018.</li>
      </ul>
    </div>
  </section>

  <section class="research-home__section research-home__section--ink" id="community">
    <div class="research-home__container">
      <div class="research-home__section-heading research-home__section-heading--light">
        <h2>Professional Service</h2>
        <p>Ongoing service across leading conferences and journals in computer vision and machine learning.</p>
      </div>

      <div class="community-strip">
        <p>Conference reviewer: CVPR, ICCV, ECCV, ICLR, and related venues.</p>
        <p>Journal reviewer: TPAMI, TMM, IJCV, and related venues.</p>
      </div>

      <p class="research-home__outbound">
        Further reading:
        <a href="https://github.com/leoxiaobin" target="_blank" rel="noopener">GitHub</a>
        <span>·</span>
        <a href="https://scholar.google.com/citations?user=t5HZdzoAAAAJ&hl=en" target="_blank" rel="noopener">Google Scholar</a>
        <span>·</span>
        <a href="https://orcid.org/0000-0001-6477-5911" target="_blank" rel="noopener">ORCID</a>
      </p>
    </div>
  </section>
</div>
