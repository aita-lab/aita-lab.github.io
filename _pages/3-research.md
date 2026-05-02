---
layout: page
title: Research
permalink: /research/
image: 
description: Presentation of the research areas and ongoing research projects of the AI Technology and Application Research Lab at the FPT University, Ho Chi Minh Campus
toc: true
toc_sticky: true
toc_label: "Table of Contents"
---

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>
  .research-container {
    --bg-main: #ffffff;
    --bg-card: #f8f9fa;
    --bg-card-hover: #ffffff;
    --primary-theme: #ed8428;
    --accent-theme: #d97521;
    --text-primary: #2b2b2b;
    --text-secondary: #555555;
    --text-muted: #888888;
    --border-color: #eaebed;
    --shadow-sm: 0 2px 4px rgba(0,0,0,0.05);
    --shadow-md: 0 4px 12px rgba(237, 132, 40, 0.12);

    background: var(--bg-main);
    color: var(--text-primary);
    font-family: 'Inter', -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
    line-height: 1.6;
    -webkit-font-smoothing: antialiased;
    max-width: 900px;
    margin: 0 auto;
    padding: 20px 24px 40px 24px;
    box-sizing: border-box;
  }

  .research-container * { 
    box-sizing: border-box; 
  }

  /* Header */
  .aita-header {
    text-align: center;
    margin-bottom: 48px;
    border-bottom: 2px solid var(--border-color);
    padding-bottom: 32px;
    display: block;
    height: auto;
    overflow: visible;
  }

  .aita-badge {
    display: inline-block;
    background: rgba(237, 132, 40, 0.1);
    color: var(--primary-theme);
    font-size: 13px;
    font-weight: 600;
    letter-spacing: 1px;
    text-transform: uppercase;
    padding: 6px 16px;
    border-radius: 4px;
    margin-bottom: 24px;
  }

  .aita-header h1 {
    font-size: 40px;
    font-weight: 700;
    color: var(--text-primary);
    line-height: 1.2;
    margin-bottom: 16px;
  }
  
  .aita-header h1 .aita-highlight {
    color: var(--primary-theme);
  }

  .aita-subtitle {
    font-size: 18px;
    color: var(--text-secondary);
    max-width: 650px;
    margin: 0 auto;
    font-weight: 400;
    line-height: 1.6;
  }

  /* Table of Contents */
  .aita-toc {
    background: var(--bg-card);
    border: 1px solid var(--border-color);
    border-left: 4px solid var(--primary-theme);
    border-radius: 8px;
    padding: 24px;
    margin-bottom: 48px;
    display: block;
    box-shadow: var(--shadow-sm);
  }
  
  .aita-toc-heading {
    font-size: 18px;
    font-weight: 700;
    color: var(--text-primary);
    margin-bottom: 16px;
  }

  .aita-toc-list {
    list-style: none;
    padding-left: 0;
    margin: 0;
  }

  .aita-toc-list li {
    margin-bottom: 12px;
    font-size: 15px;
  }

  .aita-toc-list a {
    color: var(--text-secondary);
    text-decoration: none;
    transition: color 0.2s ease, padding-left 0.2s ease;
    display: inline-block;
  }

  .aita-toc-list a:hover {
    color: var(--primary-theme);
    padding-left: 6px;
  }

  /* Section titles */
  .aita-section-label {
    font-size: 24px;
    font-weight: 700;
    color: var(--text-primary);
    margin-top: 48px;
    margin-bottom: 32px;
    display: flex;
    align-items: center;
    gap: 16px;
    clear: both;
    border: 0;
    padding: 0;
  }

  .aita-section-label::after {
    content: '';
    flex: 1;
    height: 1px;
    background: var(--border-color);
  }

  /* Project cards */
  .aita-projects {
    display: flex;
    flex-direction: column;
    gap: 24px;
    margin-bottom: 48px;
  }

  .aita-project-card {
    background: var(--bg-card);
    border: 1px solid var(--border-color);
    border-radius: 8px;
    padding: 32px;
    transition: all 0.3s ease;
    border-left: 4px solid var(--border-color);
    margin-bottom: 24px;
    display: block;
  }

  .aita-project-card:hover {
    background: var(--bg-card-hover);
    border-left-color: var(--primary-theme);
    box-shadow: var(--shadow-md);
    transform: translateY(-2px);
  }

  .aita-project-title {
    font-size: 20px;
    font-weight: 600;
    color: var(--primary-theme);
    margin: 0 0 20px 0;
    line-height: 1.3;
    display: flex;
    align-items: center;
    gap: 8px;
    border: none;
    padding: 0;
  }

  .aita-topics-list {
    margin-top: 16px;
    display: flex;
    flex-direction: column;
    gap: 14px;
  }

  .aita-topic-dropdown {
    background: #ffffff;
    border: 1px solid var(--border-color);
    border-left: 3px solid #eaebed;
    border-radius: 8px;
    margin-bottom: 2px;
    padding: 16px 20px;
    transition: all 0.3s cubic-bezier(0.25, 1, 0.5, 1);
    cursor: pointer;
    box-shadow: 0 1px 3px rgba(0,0,0,0.02);
  }

  .aita-topic-dropdown:hover {
    border-color: var(--primary-theme);
    border-left-color: var(--primary-theme);
    box-shadow: var(--shadow-sm);
    transform: translateY(-2px);
  }

  .aita-topic-dropdown[open] {
    border-color: var(--primary-theme);
    border-left-color: var(--primary-theme);
    background: #fffaf5;
    box-shadow: var(--shadow-md);
  }

  .aita-topic-summary {
    font-size: 16px;
    font-weight: 600;
    color: var(--text-primary);
    outline: none;
    user-select: none;
    list-style: none;
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 12px;
  }

  .aita-topic-summary::-webkit-details-marker {
    display: none;
  }

  .aita-topic-summary::after {
    content: '↓';
    font-size: 16px;
    font-weight: 500;
    color: var(--text-muted);
    transition: transform 0.3s ease, color 0.3s ease;
    display: inline-block;
  }

  .aita-topic-dropdown[open] .aita-topic-summary::after {
    transform: rotate(180deg);
    color: var(--primary-theme);
  }

  .aita-topic-content {
    font-size: 14.5px;
    color: var(--text-secondary);
    line-height: 1.7;
    margin-top: 14px;
    padding-top: 14px;
    border-top: 1px dashed var(--border-color);
  }

  .aita-publication-badge {
    display: inline-flex;
    align-items: center;
    background: #e8f5e9;
    color: #2e7d32;
    font-size: 11px;
    font-weight: 600;
    text-transform: uppercase;
    padding: 4px 10px;
    border-radius: 4px;
    margin-bottom: 16px;
  }

  /* Benefits section */
  .aita-benefits-section { 
    margin-bottom: 60px; 
  }
  
  .aita-benefits-grid { 
    display: grid; 
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); 
    gap: 20px; 
  }

  .aita-benefit-card {
    background: var(--bg-main);
    border: 1px solid var(--border-color);
    border-radius: 8px;
    padding: 24px;
    transition: box-shadow 0.3s ease;
  }

  .aita-benefit-card:hover {
    box-shadow: var(--shadow-md);
  }

  .aita-benefit-icon { 
    font-size: 24px; 
    margin-bottom: 16px; 
    display: block; 
  }
  
  .aita-benefit-title { 
    font-weight: 600; 
    font-size: 16px; 
    margin-bottom: 8px; 
    color: var(--text-primary); 
  }
  
  .aita-benefit-desc { 
    font-size: 14px; 
    color: var(--text-secondary); 
    line-height: 1.6; 
  }

  /* Footer */
  .aita-footer {
    text-align: center;
    margin-top: 60px;
    padding-top: 32px;
    border-top: 1px solid var(--border-color);
    color: var(--text-muted);
    font-size: 14px;
  }

  .aita-footer .aita-lab-name {
    font-weight: 600;
    letter-spacing: 1px;
    color: var(--primary-theme);
    margin-bottom: 8px;
  }

  /* Responsive */
  @media (max-width: 600px) {
    .research-container { padding: 40px 16px; }
    .aita-header h1 { font-size: 32px; }
    .aita-project-card { padding: 24px 20px; }
    .aita-benefits-grid { grid-template-columns: 1fr; }
  }
</style>

<div class="research-container">

  <!-- <div class="aita-header"> -->
    <!-- <div class="aita-badge">Research Areas</div> -->
    <!-- <h1>Lab Research <span class="aita-highlight">Themes & Focus</span></h1> -->
    <!-- <p class="aita-subtitle">Discover our core competencies in artificial intelligence, computer vision, and interdisciplinary systems at the AI Technology and Application Research Lab.</p> -->
  <!-- </div> -->

  <div class="aita-toc">
    <h5 class="aita-toc-heading">Research Areas</h5>
    <ul class="aita-toc-list">
      <li><a href="#cv-pattern">👁️ 1. Computer Vision & Pattern Recognition</a></li>
      <li><a href="#core-ml">⚙️ 2. Core Machine Learning & Advanced Computing</a></li>
      <li><a href="#smart-net">📡 3. Intelligent Networking & Smart Systems</a></li>
      <li><a href="#uav-drones">🚁 4. Autonomous UAVs & Drone Systems</a></li>
      <li><a href="#audio-emotion">🎙️ 5. Audio & Multimodal Emotion Processing</a></li>
      <li><a href="#comp-biology">🧬 6. Computational Biology & Bioinformatics</a></li>
    </ul>
  </div>

  <h2 class="aita-section-label" id="core-categories">Core Categories</h2>

  <div class="aita-projects">

    <div class="aita-project-card" id="cv-pattern">

      <h3 class="aita-project-title">👁️ 1. Computer Vision & Pattern Recognition</h3>

      <div class="aita-topics-list">

        <details class="aita-topic-dropdown">
          <summary class="aita-topic-summary">🏥 Medical Image Segmentation</summary>
          <div class="aita-topic-content">
            This research direction applies advanced neural network architectures, such as 3D U-Nets and dual-attention models, to process complex high-dimensional medical images from clinical domains (e.g., CT and MRI scans). The focus is on precisely delineating biological structures, tissues, and pathological anomalies to assist in objective diagnostic procedures and automated treatment planning.
          </div>
        </details>

        <details class="aita-topic-dropdown">
          <summary class="aita-topic-summary">🚦 Traffic Sign Recognition</summary>
          <div class="aita-topic-content">
            This theme focuses on the development and optimization of ultra-fast, high-accuracy object detection algorithms, specifically leveraging YOLOv8, YOLOv10, and TensorRT optimization. Research is geared toward achieving real-time inference on low-power, resource-constrained edge systems to improve automated safety and driver assistance systems in complex environments.
          </div>
        </details>

        <details class="aita-topic-dropdown">
          <summary class="aita-topic-summary">📝 Parsing Handwritten Math</summary>
          <div class="aita-topic-content">
            This research domain addresses the complex challenge of interpreting and translating handwritten mathematical expressions into digital markup like LaTeX. By leveraging vision transformers and graph-based models, research evaluates spatial, semantic, and hierarchical relationships between disparate mathematical symbols across diverse handwriting styles.
          </div>
        </details>

        <details class="aita-topic-dropdown">
          <summary class="aita-topic-summary">🎯 Active Learning for Detection</summary>
          <div class="aita-topic-content">
            This research explores smart sampling algorithms that intelligently measure uncertainty and select the most informative visual data points for model training. By developing advanced dual-ambiguity strategies, the focus is on optimizing model performance and robustness while significantly reducing manual data-annotation overhead.
          </div>
        </details>

        <details class="aita-topic-dropdown">
          <summary class="aita-topic-summary">🖼️ Image Captioning & Video Colorization</summary>
          <div class="aita-topic-content">
            This work operates at the intersection of computer vision and natural language generation. Research focuses on multimodal generative models that automatically narrate visual contexts into descriptive text, and colorization architectures that utilize temporal and spatial consistency to accurately restore grayscale video content.
          </div>
        </details>

      </div>

    </div>

    <div class="aita-project-card" id="core-ml">

      <h3 class="aita-project-title">⚙️ 2. Core Machine Learning & Advanced Computing</h3>

      <div class="aita-topics-list">

        <details class="aita-topic-dropdown">
          <summary class="aita-topic-summary">🔐 Federated & Distributed Learning</summary>
          <div class="aita-topic-content">
            Data privacy is one of the most critical challenges in machine learning today. This research explores privacy-preserving frameworks that enable decentralized training across heterogeneous client devices without centralizing raw data. The objective is to develop robust aggregation algorithms and optimize communication efficiency to resist client data bias.
          </div>
        </details>

        <details class="aita-topic-dropdown">
          <summary class="aita-topic-summary">⚛️ Quantum Machine Learning</summary>
          <div class="aita-topic-content">
            This pioneering area merges quantum computing with the power of artificial intelligence. By harnessing quantum properties such as superposition, entanglement, and tunneling, research focuses on developing algorithms that accelerate complex data classification, clustering, and dimensional optimization.
          </div>
        </details>

        <details class="aita-topic-dropdown">
          <summary class="aita-topic-summary">🖧 Distributed Systems Optimization</summary>
          <div class="aita-topic-content">
            As deep learning models scale exponentially, distributed optimization across multi-node high-performance computing clusters is essential. Research in this area develops synchronization schemes and parallelized algorithms to optimize cluster throughput and reduce computational bottlenecks.
          </div>
        </details>

      </div>

    </div>

    <div class="aita-project-card" id="smart-net">

      <h3 class="aita-project-title">📡 3. Intelligent Networking & Smart Systems</h3>

      <div class="aita-topics-list">

        <details class="aita-topic-dropdown">
          <summary class="aita-topic-summary">📶 AI-Integrated MAC Protocols</summary>
          <div class="aita-topic-content">
            Wireless and IoT networks often suffer from performance drops due to channel interference and data packet collisions. This research direction integrates deep reinforcement learning into Medium Access Control (MAC) operations. By enabling dynamic channel sensing and adaptive power allocation, the objective is to optimize spectral efficiency, minimize packet collision rates, and reduce latency.
          </div>
        </details>

        <details class="aita-topic-dropdown">
          <summary class="aita-topic-summary">🚗 Intelligent Transport Systems & VANETs</summary>
          <div class="aita-topic-content">
            This theme investigates the integration of IoT and predictive machine learning models to build intelligent municipal infrastructure. Key topics include routing protocols in Vehicular Ad-hoc Networks (VANETs), real-time smart parking allocation systems, and connected sensor infrastructures for improved traffic management.
          </div>
        </details>

      </div>

    </div>

    <div class="aita-project-card" id="uav-drones">

      <h3 class="aita-project-title">🚁 4. Autonomous UAVs & Drone Systems</h3>

      <div class="aita-topics-list">

        <details class="aita-topic-dropdown">
          <summary class="aita-topic-summary">🤖 Autonomous Aerial Vehicles</summary>
          <div class="aita-topic-content">
            This research direction focuses on the development of AI-enabled drone systems capable of real-time perception, adaptive decision-making, and fully autonomous operation in dynamic environments. Emphasis is placed on onboard (edge) intelligence, allowing UAVs to process sensory data locally to reduce latency, improve reliability, and optimize communication efficiency.
          </div>
        </details>

        <details class="aita-topic-dropdown">
          <summary class="aita-topic-summary">⚡ Edge AI on Drone Hardware</summary>
          <div class="aita-topic-content">
            Running intensive deep learning visual models on airborne drones requires highly specialized computing. Key objectives include optimizing neural networks via quantization and hardware acceleration techniques to perform visual tasks directly on resource-constrained onboard chips.
          </div>
        </details>

        <details class="aita-topic-dropdown">
          <summary class="aita-topic-summary">🌐 Multi-Drone Swarm Intelligence</summary>
          <div class="aita-topic-content">
            Key research areas include aerial computer vision for object detection, environmental analysis, and anomaly identification; autonomous navigation and coverage path planning under uncertainty; and cooperative multi-drone systems (swarm intelligence) for scalable, large-area monitoring. The integration of UAVs with IoT and intelligent networking infrastructures is also explored to support applications in smart cities, precision agriculture, disaster response, and environmental monitoring.
          </div>
        </details>

      </div>

    </div>

    <div class="aita-project-card" id="audio-emotion">

      <h3 class="aita-project-title">🎙️ 5. Audio & Multimodal Emotion Processing</h3>

      <span class="aita-publication-badge">Highly Published Area</span>

      <div class="aita-topics-list">

        <details class="aita-topic-dropdown">
          <summary class="aita-topic-summary">🗣️ Speech Emotion Recognition</summary>
          <div class="aita-topic-content">
            This domain explores extracting complex affective contexts directly from acoustic vocal waveforms. Research leverages multi-feature fusion techniques and sequential modeling, such as Graph-LSTM architectures, to identify emotional patterns independently of specific spoken languages.
          </div>
        </details>

        <details class="aita-topic-dropdown">
          <summary class="aita-topic-summary">🎭 Multimodal Emotion Fusion</summary>
          <div class="aita-topic-content">
            This theme addresses the challenge of integrating disparate modalities like audio, visual gestures, and text transcripts. By utilizing self-aligning cross-modal attention mechanisms and dynamic hypergraphs, the goal is to capture subtle, non-linear correlations to achieve a unified emotional representation.
          </div>
        </details>

        <details class="aita-topic-dropdown">
          <summary class="aita-topic-summary">❤️ Affective Computing & AI Synthesis</summary>
          <div class="aita-topic-content">
            This research focuses on developing empathetic conversational AI agents that dynamically parse emotional contexts and synthesize high-fidelity empathetic text or speech outputs. The objective is to improve the naturalness and context-awareness of modern human-computer interaction frameworks.
          </div>
        </details>

      </div>

    </div>

    <div class="aita-project-card" id="comp-biology">

      <h3 class="aita-project-title">🧬 6. Computational Biology & Bioinformatics</h3>

      <div class="aita-topics-list">

        <details class="aita-topic-dropdown">
          <summary class="aita-topic-summary">💊 Small Molecule Generation</summary>
          <div class="aita-topic-content">
            This theme explores the intersection of deep learning and computational chemistry to accelerate structural drug discovery. Research investigates generative AI and text-to-molecule architectures to automate the generation of novel chemical compounds targeting specific medical conditions.
          </div>
        </details>

        <details class="aita-topic-dropdown">
          <summary class="aita-topic-summary">🧬 Splice Site Prediction</summary>
          <div class="aita-topic-content">
            This research focuses on deploying sequence-to-sequence deep modeling architectures to accurately predict exact mRNA splicing positions. The objective is to map complex genomic mutations and understand the foundational molecular mechanisms responsible for various genetic disorders.
          </div>
        </details>

        <details class="aita-topic-dropdown">
          <summary class="aita-topic-summary">🧪 Peptide-based Therapeutics Prediction</summary>
          <div class="aita-topic-content">
            This research involves utilizing deep learning models, such as graph neural networks and protein language models, to predict the bioactivity, binding affinity, and stability of therapeutic peptides. By analyzing amino acid sequences and structural flexibility, the goal is to design precise peptide-based drugs for targeted delivery and immunotherapy.
          </div>
        </details>

        <details class="aita-topic-dropdown">
          <summary class="aita-topic-summary">🧬 RNA Post-transcriptional Modification Sites Prediction</summary>
          <div class="aita-topic-content">
            This theme focuses on the computational identification of chemical modifications in RNA (e.g., m6A, m5C, and pseudouridylation) that define the "epitranscriptome." Research leverages transformer-based architectures and RNA/genomic language models to predict how these modifications regulate mRNA stability and translation, providing insights into the pathogenesis of complex diseases and cancers.
          </div>
        </details>

        <details class="aita-topic-dropdown">
          <summary class="aita-topic-summary">🥩 Protein Post-translational Modification Sites Prediction</summary>
          <div class="aita-topic-content">
            This research investigates the use of deep learning models, such as graph neural networks and protein language models, to predict site-specific modifications (e.g., phosphorylation, ubiquitination, and glycosylation) that occur after protein synthesis. By mapping these sites, the objective is to understand how PTMs expand proteomic diversity and influence cellular signaling and metabolic regulation.
          </div>
        </details>

      </div>

    </div>

  </div>

  <h2 class="aita-section-label" id="opportunities">Opportunities</h2>

  <div class="aita-benefits-grid aita-benefits-section">
    <div class="aita-benefit-card">
      <span class="aita-benefit-icon">📘</span>
      <div class="aita-benefit-title">Expert Mentorship</div>
      <div class="aita-benefit-desc">Receive direct guidance from leading researchers with multiple publications in high-impact academic journals and conferences.</div>
    </div>
    <div class="aita-benefit-card">
      <span class="aita-benefit-icon">🔬</span>
      <div class="aita-benefit-title">State-of-the-Art Projects</div>
      <div class="aita-benefit-desc">Collaborate on diverse, high-impact research projects spanning computer vision, quantum computing, and computational biology.</div>
    </div>
    <div class="aita-benefit-card">
      <span class="aita-benefit-icon">📝</span>
      <div class="aita-benefit-title">Publication Support</div>
      <div class="aita-benefit-desc">Work systematically towards contributing to international conferences and high-tier academic journals.</div>
    </div>
  </div>

  <footer class="aita-footer">
    <div class="aita-lab-name">AI Technology and Application Research Lab (AITA)</div>
    <p>© 2026 AITA Lab - All rights reserved.</p>
  </footer>

</div>