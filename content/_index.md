---
# Leave the homepage title empty to use the site title
title: Trustworthy AI Exploration (ExRAIL) Lab
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Trustworthy AI Exploration (ExRAIL) Lab
      image:
        filename: sihong-xie-head.jpg
        alt_text: Sihong Xie
      text: |
        Led by [Prof. Sihong XIE](https://sihongxie.github.io/), a tenured Associate Professor at the AI Thrust, Information Hub of HKUST(GZ).

        ExRAIL develops trustworthy machine learning for graph learning, language models, multi-agent systems, and reinforcement learning.

        Email: [sihongxie@hkust-gz.edu.cn](mailto:sihongxie@hkust-gz.edu.cn)

        [Personal Website](https://sihongxie.github.io/) &nbsp; [Google Scholar](https://scholar.google.co.uk/citations?user=qRp1xZwAAAAJ&hl=zh-CN&oi=ao) &nbsp; [People](./people/)
    design:
      css_class: homepage-intro

  - block: markdown
    content:
      title: About
      subtitle: ''
      text: |
        Dr. Sihong Xie is a **tenured Associate Professor** at the AI Thrust, Information Hub of **HKUST(GZ)**. He is the director of the **Trustworthy AI Exploration (ExRAIL) Lab**.

        Before joining HKUST(GZ), he was a faculty member in the Computer Science and Engineering Department at Lehigh University from 2016 to 2023, where he was promoted to Associate Professor with tenure in 2023. He received his Ph.D. in Computer Science from the University of Illinois at Chicago in 2016, advised by Prof. Philip S. Yu, and received his B.S. and M.S. from Sun Yat-Sen University.

        His research focuses on **trustworthy machine learning** — including explainability, uncertainty quantification, fairness, robustness, and reliability — with applications in graph learning, language models, and multi-agent systems. He has published **130+ papers** in top venues (NeurIPS, ICML, ICLR, AAAI, IJCAI, KDD, ACL, CVPR, CIKM, ICDM, WSDM) with **3,100+ citations** and an **h-index of 24**.

        He is the recipient of the **NSF CAREER Award** (2022) and the **国家自然科学基金优秀青年科学基金项目（海外）** (2024). He serves on the executive committees of ACM SIGSPATIAL China, CCF-AI, and CCF-BigData.

        <div class="recruiting-callout">📣 <strong>Recruiting Ph.D./RA/Intern positions for 2026–2027.</strong> Recent highlights include ICML 2026 Oral (0.7%), ICML 2026 Spotlight, ECCV 2026, IJCAI 2026, and IROS 2026.</div>
    design:
      columns: '1'
      css_class: homepage-about

  - block: markdown
    content:
      title: Project Demonstration
      subtitle: ''
      text: |
        <div class="project-demo-scroll">
          <a class="project-demo-card" href="https://psg-nav.github.io/" target="_blank" rel="noopener">
            <span class="project-demo-copy">
              <span class="project-demo-title">PSG-Nav: Probabilistic Scene Graph Navigation via Multiverse Decision Making</span>
              <span class="project-demo-venue">ICML 2026</span>
            </span>
            <img class="project-demo-thumb" src="/uploads/project-demo/psg-nav.png" alt="PSG-Nav project preview">
          </a>

          <a class="project-demo-card" href="https://github.com/FUTUREEEEEE/CogniBench" target="_blank" rel="noopener">
            <span class="project-demo-copy">
              <span class="project-demo-title">CogniBench: A Benchmark for Evaluating LLM Cognitive Abilities</span>
              <span class="project-demo-venue">ACL 2025</span>
            </span>
            <img class="project-demo-thumb" src="/uploads/project-demo/cognibench.svg" alt="CogniBench project preview">
          </a>

          <a class="project-demo-card" href="https://github.com/FUTUREEEEEE/Dynamic-RAG" target="_blank" rel="noopener">
            <span class="project-demo-copy">
              <span class="project-demo-title">Bandit-enhanced Retrieval-Augmented Generation over Knowledge Graphs</span>
              <span class="project-demo-venue">AAAI 2025</span>
            </span>
            <img class="project-demo-thumb" src="/uploads/project-demo/dynamic-rag.svg" alt="Dynamic-RAG project preview">
          </a>

          <a class="project-demo-card" href="https://github.com/rxu0112/WR-CP" target="_blank" rel="noopener">
            <span class="project-demo-copy">
              <span class="project-demo-title">Wasserstein-Regularized Conformal Prediction under General Distribution Shift</span>
              <span class="project-demo-venue">ICLR 2025</span>
            </span>
            <img class="project-demo-thumb" src="/uploads/project-demo/wr-cp.svg" alt="WR-CP project preview">
          </a>

          <a class="project-demo-card" href="https://github.com/yazhengliu/Axiomatic-Layer-Edges" target="_blank" rel="noopener">
            <span class="project-demo-copy">
              <span class="project-demo-title">Explainable GNNs via Multi-level Attribution</span>
              <span class="project-demo-venue">ICLR 2025</span>
            </span>
            <img class="project-demo-thumb" src="/uploads/project-demo/gnn-attribution.svg" alt="GNN attribution project preview">
          </a>

          <a class="project-demo-card" href="https://github.com/MengzSun/KDCN" target="_blank" rel="noopener">
            <span class="project-demo-copy">
              <span class="project-demo-title">Inconsistent Matters: A Knowledge-guided Dual-consistency Network for Multi-modal Rumor Detection</span>
              <span class="project-demo-venue">TKDE 2023</span>
            </span>
            <img class="project-demo-thumb" src="/uploads/project-demo/kdcn.svg" alt="KDCN project preview">
          </a>
        </div>
    design:
      columns: '1'
      css_class: homepage-project-demo
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 30
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
      css_class: homepage-news-timeline

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
