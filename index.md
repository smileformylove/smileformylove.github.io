---
layout: page
---

<style>
  .profile-container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 2rem;
  }

  .hero-section {
    text-align: center;
    margin-bottom: 3rem;
    padding: 3rem 2rem;
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    border-radius: 20px;
    color: white;
    box-shadow: 0 15px 40px rgba(0,0,0,0.15);
    position: relative;
    overflow: hidden;
  }

  .hero-section::before {
    content: '';
    position: absolute;
    top: -50%;
    left: -50%;
    width: 200%;
    height: 200%;
    background: radial-gradient(circle, rgba(255,255,255,0.1) 0%, transparent 70%);
    animation: pulse 15s ease-in-out infinite;
  }

  @keyframes pulse {
    0%, 100% { transform: scale(1); }
    50% { transform: scale(1.1); }
  }

  .hero-section h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
    font-weight: 700;
    position: relative;
    z-index: 1;
  }

  .hero-section .title {
    font-size: 1.5rem;
    opacity: 0.95;
    margin-bottom: 1.5rem;
    position: relative;
    z-index: 1;
  }

  .hero-section .affiliation {
    font-size: 1.2rem;
    opacity: 0.9;
    position: relative;
    z-index: 1;
  }

  .hero-section a {
    color: #ffd700;
    text-decoration: none;
    border-bottom: 2px solid #ffd700;
    transition: all 0.3s ease;
  }

  .hero-section a:hover {
    color: #ffed4e;
    border-bottom-color: #ffed4e;
  }

  .bio-section {
    background: white;
    padding: 2.5rem;
    border-radius: 15px;
    margin-bottom: 2rem;
    box-shadow: 0 8px 24px rgba(0,0,0,0.1);
    line-height: 1.9;
    font-size: 1.05rem;
  }

  .research-philosophy {
    background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
    padding: 2.5rem;
    border-radius: 15px;
    margin-bottom: 2rem;
    border-left: 6px solid #667eea;
    font-size: 1.05rem;
    line-height: 1.9;
  }

  .research-philosophy strong {
    color: #667eea;
    font-size: 1.15rem;
  }

  .section-title {
    font-size: 2rem;
    font-weight: 700;
    margin-bottom: 1.5rem;
    color: #333;
    border-bottom: 3px solid #667eea;
    padding-bottom: 0.5rem;
    display: inline-block;
  }

  .news-item {
    background: white;
    padding: 1.5rem;
    margin-bottom: 1.2rem;
    border-radius: 12px;
    border-left: 5px solid #667eea;
    box-shadow: 0 3px 12px rgba(0,0,0,0.08);
    transition: all 0.3s ease;
    font-size: 1.02rem;
    line-height: 1.7;
  }

  .news-item:hover {
    transform: translateX(5px);
    box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  }

  .news-item strong {
    color: #667eea;
    font-weight: 600;
  }

  .publication-item {
    background: white;
    padding: 2rem;
    margin-bottom: 1.2rem;
    border-radius: 12px;
    border: 1px solid #e0e0e0;
    transition: all 0.3s ease;
  }

  .publication-item:hover {
    border-color: #667eea;
    box-shadow: 0 6px 20px rgba(102, 126, 234, 0.2);
    transform: translateY(-2px);
  }

  .award-item {
    background: linear-gradient(135deg, #ffeaa7 0%, #fdcb6e 100%);
    padding: 1.5rem;
    margin-bottom: 1.2rem;
    border-radius: 12px;
    font-weight: 500;
    box-shadow: 0 4px 15px rgba(0,0,0,0.12);
    font-size: 1.05rem;
  }

  .award-item a {
    color: #2d3436;
    text-decoration: none;
    font-weight: 600;
  }

  .content-section {
    margin-top: 3rem;
  }

  @media (max-width: 768px) {
    .profile-container {
      padding: 1rem;
    }

    .hero-section {
      padding: 2rem 1rem;
    }

    .hero-section h1 {
      font-size: 2rem;
    }

    .hero-section .title {
      font-size: 1.2rem;
    }

    .hero-section .affiliation {
      font-size: 1rem;
    }

    .bio-section,
    .research-philosophy {
      padding: 1.5rem;
    }

    .section-title {
      font-size: 1.5rem;
    }
  }
</style>

<div class="profile-container">
  <div class="hero-section">
    <h1>Jixiang Luo</h1>
    <p class="title">Research Scientist @ TeleAI</p>
    <p class="affiliation">
      Ubiquitous Artificial General Intelligence Group<br>
      Working with <a href="https://scholar.google.com/citations?hl=de&user=M0Ltb88AAAAJ" target="_blank">Dell Zhang</a>
    </p>
  </div>

  <div class="bio-section">
    <p>
      I currently work at the <strong>Ubiquitous Artificial General Intelligence Group of TeleAI</strong>, focusing on multi-modal signal representation, understanding, generation, and AICodec (end-to-end image and video compression). Previously, I gained two years of experience at Sensetime Research and six months at Xiaohongshu MediaLab. During my postgraduate studies, I interned at Huawei Cloud and Alibaba Cloud.
    </p>
    <p style="margin-top: 1rem;">
      I received both my bachelor's and master's degrees from <strong>Shanghai Jiao Tong University</strong>, specializing in data compression, video compression, and signal processing under the supervision of Prof. Hongkai Xiong and Prof. Wenrui Dai at the <a href="https://min.sjtu.edu.cn/" target="_blank">MIN lab</a>.
    </p>
    <p style="margin-top: 1rem;">
      My publications have appeared in <strong>DCC, CVPR, ICML, ACMMM, AAAI, SIGIR, ICIP, VCIP, WWW, and EACL</strong>. I also serve as a reviewer for CVPR, ICCV, ICLR, ACMMM, AAAI, ACL/EMNLP, WACV, and PRCV. You can find my complete list of publications <a href="https://scholar.google.com/citations?user=ua29MrwAAAAJ&hl=de" target="_blank">here</a>.
    </p>
  </div>

  <div class="research-philosophy">
    <p style="margin-bottom: 1rem;">
      I believe that <strong>compression is fundamentally about representing the world</strong>. My current research explores the representation of <strong>multi-modal signals</strong>, including image, video, text, and audio, investigating the principle that <strong>everything is embedding</strong> or <strong>everything is token</strong>.
    </p>
    <p>
      My primary focus is uncovering the intrinsic relationship between compression and generation within multi-modal signals.
    </p>
  </div>
</div> 

---

<div class="content-section">
  <h2 class="section-title">📰 News and Updates</h2>

  <div class="news-item">
    <strong>🎉 Jan 2026</strong> – Our paper "Boosting Large Language Models for Mental Manipulation Detection via Data Augmentation and Distillation" has been accepted by <strong>WWW2026</strong>!
  </div>

  <div class="news-item">
    <strong>📄 Dec 2025</strong> – Our report <a href="https://arxiv.org/abs/2601.06037" target="_blank"><strong>TeleMem: Building Long-Term and Multimodal Memory for Agentic AI</strong></a> has been published!
  </div>

  <div class="news-item">
    <strong>📄 Dec 2025</strong> – Our position paper <a href="https://www.arxiv.org/pdf/2512.24300" target="_blank"><strong>Generative Video Compression: Towards 0.01% Compression Rate for Video Transmission</strong></a>, along with reports at <a href="https://mp.weixin.qq.com/s/BKFbsXsIc0dAvqWszVFTrQ" target="_blank">TeleAI</a> and <a href="https://mp.weixin.qq.com/s/GG1BFS8mFugifO9xzA33Tg?scene=1&click_id=7&version=4.1.36.70499&platform=mac" target="_blank">QbitAI</a>, have been published!
  </div>

  <div class="news-item">
    <strong>📄 Dec 2025</strong> – Our position paper <a href="https://arxiv.org/pdf/2512.21567" target="_blank">"Beyond Heuristics: A Decision-Theoretic Framework for Agent Memory Management"</a> is now available!
  </div>

  <div class="news-item">
    <strong>🎤 Nov 2025</strong> – Invited talk at <a href="https://mp.weixin.qq.com/s/F8ex_pJWwBxXeoDE2ZNJJg?version=4.1.36.70499&platform=mac&from=industrynews" target="_blank">"CSIG-MM"</a> to report on AICodec progress!
  </div>

  <div class="news-item">
    <strong>✅ Nov 2025</strong> – Our work "STMI: Segmentation-Guided Token Modulation with Cross-Modal Hypergraph Interaction for Multi-Modal Object Re-Identification" has been accepted by <strong>AAAI2026</strong>!
  </div>

  <div class="news-item">
    <strong>📄 Nov 2025</strong> – Our work <a href="https://arxiv.org/abs/2511.01590" target="_blank">"EV-NVC: Efficient Variable bitrate Neural Video Compression"</a> is now available!
  </div>

  <div class="news-item">
    <strong>📄 Oct 2025</strong> – Our work <a href="https://arxiv.org/abs/2510.23981" target="_blank">"TeleEgo: Benchmarking Egocentric AI Assistants in the Wild"</a> has been published!
  </div>

  <div class="news-item">
    <strong>📚 Sept 2025</strong> – Our tutorial <a href="https://dl.acm.org/doi/10.1145/3767695.3769671" target="_blank"><strong>Conversational Agents: From RAG to LTM</strong></a> has been accepted by <strong>SIGIR-AP2025</strong>! The corresponding <a href="https://github.com/TeleAI-UAGI/telemem" target="_blank"><strong>TeleMem</strong></a> is also available!
  </div>

  <div class="news-item">
    <strong>📺 Sept 2025</strong> – Our project <a href="https://tv.cctv.com/2025/09/10/VIDEQvv9vbxpZCBEeog7xKdt250910.shtml?spm=C53156045404.P8kLhvFcIptK.0.0" target="_blank"><strong>TeleFood</strong> and the corresponding AI glasses</a> have been featured on CCTV!
  </div>

  <div class="news-item">
    <strong>📄 July 2025</strong> – Our work <a href="https://arxiv.org/pdf/2507.09068" target="_blank">"Infinite Video Understanding"</a> is now available!
  </div>

  <div class="news-item">
    <strong>🏆 May 2025</strong> – Our team 'NewbeeDVC' won <strong>first place</strong> in the E2E track of <a href="https://iscasnnvcgc.github.io/awards/" target="_blank">the ISCAS Grand Challenge 2025</a>!
  </div>

  <div class="news-item">
    <strong>✅ April 2025</strong> – Our work <a href="https://smartfreeedit.github.io/" target="_blank"><strong>"SmartFreeEdit: Mask-Free Spatial-Aware Image Editing with Complex Instruction Understanding"</strong></a> has been published and accepted by <strong>ACMMM2025</strong>! The corresponding report is available at <a href="https://mp.weixin.qq.com/s/esmn7HUqJjA5rIK0bJ-MaQ?version=4.1.36.70499&platform=mac&from=industrynews" target="_blank">TeleAI</a>!
  </div>

  <div class="news-item">
    <strong>💼 Nov 2024</strong> – New position! I joined TeleAI as a Research Scientist.
  </div>

  <div class="news-item">
    <strong>🎤 Nov 2024</strong> – Attendance at CCF Young Computer Scientists & Engineers Forum (YOCSEF) in Hefei to discuss the future of <a href="https://mp.weixin.qq.com/s/FLwFMvz_fQr41FXdcXyH7Q" target="_blank">AI-based image and video compression</a>.
  </div>

  <div class="news-item">
    <strong>📄 July 2024</strong> – My work <a href="https://arxiv.org/abs/2407.11590" target="_blank">"Rethinking Learned Image Compression: Context is All You Need"</a> is now available!
  </div>

  <div class="news-item">
    <strong>🎤 June 2024</strong> – Invited talk for <a href="https://tiangong-china.com/" target="_blank">Skywork</a> about <strong>Visual Reconstruction and Generation</strong>!
  </div>

  <div class="news-item">
    <strong>📰 June 2024</strong> – Invited report on <a href="https://www.mittrchina.com/news/detail/13461" target="_blank">compressible and searchable</a> featured in <strong>MIT Technology Review</strong>!
  </div>

  <div class="news-item">
    <strong>🎤 April 2024</strong> – Invited talk and corresponding report on <a href="https://www.sohu.com/a/768385893_116132" target="_blank">Sora with Generative AI</a> in Shanghai!
  </div>

  <div class="news-item">
    <strong>📄 April 2024</strong> – My work <a href="https://arxiv.org/abs/2404.10234" target="_blank">"Compressible and Searchable: AI-native Multi-Modal Retrieval System with Learned Image Compression"</a> is now available!
  </div>

  <div class="news-item">
    <strong>📄 March 2024</strong> – Our work <a href="https://arxiv.org/abs/2403.13030" target="_blank">"Super-High-Fidelity Image Compression via Hierarchical-ROI and Adaptive Quantization"</a> is now available!
  </div>

  <div class="news-item">
    <strong>✅ February 2024</strong> – Our work <a href="https://arxiv.org/abs/2404.04848" target="_blank">"Task-Aware Encoder Control for Deep Video Compression"</a> has been accepted by <strong>CVPR2024</strong>!
  </div>
</div>

---

<div class="content-section">
  <h2 class="section-title">📚 Publications</h2>

  <div class="publication-item">
    <p><strong>📄 Rethinking Learned Image Compression: Context is All You Need</strong></p>
    <p style="margin-top: 0.5rem; font-size: 0.95rem; color: #666;">
      Jixiang Luo<br>
      <em>Arxiv'2024</em><br>
      <a href="https://arxiv.org/abs/2407.11590" target="_blank" style="color: #667eea;">https://arxiv.org/abs/2407.11590</a>
    </p>
  </div>

  <div class="publication-item">
    <p><strong>📄 Compressible and Searchable: AI-native Multi-Modal Retrieval System with Learned Image Compression</strong></p>
    <p style="margin-top: 0.5rem; font-size: 0.95rem; color: #666;">
      Jixiang Luo<br>
      <em>Arxiv'2024</em><br>
      <a href="https://arxiv.org/abs/2404.10234" target="_blank" style="color: #667eea;">https://arxiv.org/abs/2404.10234</a>
    </p>
  </div>

  <div class="publication-item">
    <p><strong>📄 Super-High-Fidelity Image Compression via Hierarchical-ROI and Adaptive Quantization</strong></p>
    <p style="margin-top: 0.5rem; font-size: 0.95rem; color: #666;">
      Jixiang Luo, Yan Wang, Hongwei Qin<br>
      <em>Arxiv'2024</em><br>
      <a href="https://arxiv.org/abs/2403.13030" target="_blank" style="color: #667eea;">https://arxiv.org/abs/2403.13030</a>
    </p>
  </div>

  <div class="publication-item">
    <p><strong>📄 Task-Aware Encoder Control for Deep Video Compression</strong></p>
    <p style="margin-top: 0.5rem; font-size: 0.95rem; color: #666;">
      Xingtong Ge, Jixiang Luo, Xinjie Zhang, Tongda Xu, Guo Lu, Dailan He, Jing Geng, Yan Wang, Jun Zhang, Hongwei Qin<br>
      <em>CVPR'2024</em><br>
      <a href="https://arxiv.org/abs/2404.04848" target="_blank" style="color: #667eea;">https://arxiv.org/abs/2404.04848</a>
    </p>
  </div>

  <div style="text-align: center; margin-top: 2rem;">
    <a href="https://scholar.google.com/citations?user=ua29MrwAAAAJ&hl=de" target="_blank" style="display: inline-block; padding: 12px 30px; background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); color: white; text-decoration: none; border-radius: 25px; font-weight: 600; transition: all 0.3s ease; box-shadow: 0 4px 15px rgba(102, 126, 234, 0.4);">
      View All Publications →
    </a>
  </div>
</div>

---

<div class="content-section">
  <h2 class="section-title">🏆 Awards</h2>

  <div class="award-item">
    <strong>🥇 1st Place</strong> – Video Compression Track, <a href="https://iscasnnvcgc.github.io/awards/" target="_blank">ISCAS2025</a>
  </div>

  <div class="award-item">
    <strong>🥇 1st Place</strong> – Image Compression Track, <a href="https://archive.compression.cc/2022/leaderboard/image_075/test/index.html" target="_blank">CVPRW2022</a>
  </div>

  <div class="award-item">
    <strong>🏅 Top 1</strong> – MSU Cloud Video Compression, <a href="http://www.compression.ru/video/codec_comparison/2022/cloud_report.html" target="_blank">MSU2021</a>
  </div>

  <div class="award-item">
    <strong>🏆 Champion</strong> – Call for Code, IBM2019
  </div>

  <div class="award-item">
    <strong>🎖️ National Scholarship</strong> – 2020
  </div>
</div>
