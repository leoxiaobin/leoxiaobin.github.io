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
        <p class="research-home__headline">Multimodal and agentic AI research for systems people can actually use.</p>
        <p class="research-home__support">
          Member of Tech Staff at Microsoft AI, building compact multimodal and agentic systems with representative work across Phi-3 Vision, Florence, CvT, and HRNet.
        </p>
        <div class="research-home__actions">
          <a class="research-home__button research-home__button--primary" href="#selected-work">Selected publications</a>
          <a class="research-home__button research-home__button--secondary" href="https://scholar.google.com/citations?view_op=list_works&hl=en&user=t5HZdzoAAAAJ" target="_blank" rel="noopener">Google Scholar</a>
        </div>
      </div>
    </div>
  </header>

  <section class="research-home__section research-home__section--paper" id="trajectory">
    <div class="research-home__container">
      <div class="research-home__section-heading">
        <h2>Research Highlights</h2>
        <p>Selected milestones across reasoning and coding models, multimodal post-training, and dense vision systems.</p>
      </div>

      <ol class="trajectory-list">
        <li>
          <span class="trajectory-list__year">2025–present</span>
          <p>Reasoning, agentic, and coding model training.</p>
        </li>
        <li>
          <span class="trajectory-list__year">2024–2025</span>
          <p>Multimodal Llama post-training.</p>
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
          <p>Part of the Phi-3 effort to make compact models practical on-device, including strong multimodal capability.</p>
          <p class="publication-list__links"><a href="https://arxiv.org/abs/2404.14219" target="_blank" rel="noopener">Paper</a><a href="https://huggingface.co/microsoft/Phi-3-vision-128k-instruct" target="_blank" rel="noopener">Model</a></p>
        </article>

        <article class="publication-list__item">
          <p class="publication-list__meta">2024 · CVPR oral · unified vision model</p>
          <h3>Florence-2: Advancing a Unified Representation for a Variety of Vision Tasks</h3>
          <p>A unified representation model that spans captioning, OCR, grounding, segmentation, and open-ended vision-language tasks.</p>
          <p class="publication-list__links"><a href="https://arxiv.org/pdf/2311.06242.pdf" target="_blank" rel="noopener">Paper</a><a href="https://huggingface.co/microsoft/Florence-2-large" target="_blank" rel="noopener">Model</a></p>
        </article>

        <article class="publication-list__item">
          <p class="publication-list__meta">2021 · ICCV · transformer backbone</p>
          <h3>CvT: Introducing Convolutions to Vision Transformers</h3>
          <p>One of the early hybrid CNN-transformer architectures, later becoming one of the most cited ICCV 2021 papers.</p>
          <p class="publication-list__links"><a href="https://openaccess.thecvf.com/content/ICCV2021/papers/Wu_CvT_Introducing_Convolutions_to_Vision_Transformers_ICCV_2021_paper.pdf" target="_blank" rel="noopener">Paper</a><a href="https://github.com/microsoft/CvT" target="_blank" rel="noopener">Code</a></p>
        </article>

        <article class="publication-list__item">
          <p class="publication-list__meta">2019 · CVPR · dense prediction backbone</p>
          <h3>Deep High-Resolution Representation Learning for Human Pose Estimation</h3>
          <p>Introduced the HRNet family, maintaining high-resolution representations throughout the backbone for dense recognition tasks.</p>
          <p class="publication-list__links"><a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Sun_Deep_High-Resolution_Representation_Learning_for_Human_Pose_Estimation_CVPR_2019_paper.pdf" target="_blank" rel="noopener">Paper</a><a href="https://github.com/leoxiaobin/deep-high-resolution-net.pytorch" target="_blank" rel="noopener">Code</a></p>
        </article>

        <article class="publication-list__item">
          <p class="publication-list__meta">2018 · ECCV · pose estimation baseline</p>
          <h3>Simple Baselines for Human Pose Estimation and Tracking</h3>
          <p>A straightforward, high-performing baseline that became a durable reference point for pose estimation and tracking.</p>
          <p class="publication-list__links"><a href="http://openaccess.thecvf.com/content_ECCV_2018/papers/Bin_Xiao_Simple_Baselines_for_ECCV_2018_paper.pdf" target="_blank" rel="noopener">Paper</a><a href="https://github.com/microsoft/human-pose-estimation.pytorch" target="_blank" rel="noopener">Code</a></p>
        </article>
      </div>
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
        <li>SimpleBaseline ranks among the most cited ECCV 2018 papers, with more than 2,100 citations.</li>
        <li>1st place in Look into Person Challenge 2019: Single-Person Human Pose Estimation Track.</li>
        <li>2nd place in Object365 Challenge 2019: Full track.</li>
        <li>1st place in PoseTrack Multi-Person Pose Tracking Challenge 2018.</li>
        <li>2nd place in COCO Keypoint Detection Challenge 2018.</li>
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
        Elsewhere:
        <a href="https://github.com/leoxiaobin" target="_blank" rel="noopener">GitHub</a>
        <span>·</span>
        <a href="https://scholar.google.com/citations?user=t5HZdzoAAAAJ&hl=en" target="_blank" rel="noopener">Google Scholar</a>
        <span>·</span>
        <a href="https://orcid.org/0000-0001-6477-5911" target="_blank" rel="noopener">ORCID</a>
      </p>
    </div>
  </section>
</div>
