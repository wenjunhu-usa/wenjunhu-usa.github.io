---
layout: default
title: Wenjun Hu - AI Research
---
<div class="header">
    <div class="profile-section">
        <img src="images/profile.jpg" alt="Wenjun Hu" class="profile-image">
        <div class="profile-info">
            <h1>Wenjun Hu</h1>
            <div class="profile-summary">
                <p>Welcome to my portfolio. I am an AI Scientist with 5+ years of experience specializing in deep learning, generative AI, and large language models. Beyond research, I design and implement end-to-end AI pipelines that align with user needs—transforming cutting-edge models into practical, scalable solutions that create measurable impact across industries.</p>
                <p>For an in-depth view of my research interests, publications, and current projects, please explore the research-area tabs below.</p>
            </div>
        </div>
    </div>
    
    <div class="contact-info">
        <a href="mailto:nuaahwj@gmail.com" class="contact-item">
            <svg class="contact-icon" viewBox="0 0 24 24" fill="currentColor">
                <path d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"/>
            </svg>
            nuaahwj@gmail.com
        </a>
        <a href="https://scholar.google.com/citations?user=rCG_IBgAAAAJ&hl=en" class="contact-item" target="_blank">
            <svg class="contact-icon" viewBox="0 0 24 24" fill="currentColor">
                <path d="M5.242 13.769L0.5 9.5 12 1l11.5 8.5-4.742 4.269C17.548 14.359 14.899 14.5 12 14.5c-2.899 0-5.548-.141-6.758-.731z"/>
                <path d="M12 14.5c-2.899 0-5.548-.141-6.758-.731L0.5 18.5 12 23l11.5-4.5-4.742-4.731C17.548 14.359 14.899 14.5 12 14.5z"/>
            </svg>
            Google Scholar
        </a>
        <a href="https://www.linkedin.com/in/wenjunhu-usa/" class="contact-item" target="_blank">
            <svg class="contact-icon" viewBox="0 0 24 24" fill="currentColor">
                <path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/>
            </svg>
            LinkedIn
        </a>
        <a href="https://github.com/phyhuhu" class="contact-item" target="_blank">
            <svg class="contact-icon" viewBox="0 0 24 24" fill="currentColor">
                <path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/>
            </svg>
            GitHub
        </a>

    </div>
</div>

<div class="content-section">
    <h2>Research Interests</h2>
    
    <p style="margin-bottom: 30px;">My research focuses on developing foundational AI algorithms and applying state-of-the-art models to real-world problems. For a complete list of publications and citations, please visit my <a href="https://scholar.google.com/citations?user=rCG_IBgAAAAJ&hl=en" target="_blank">Google Scholar profile</a>.</p>
    
    <div class="research-tabs">
        <div class="tabs-header">
            <button class="tab-button" onclick="showTab('genai')">Generative AI & LLMs</button>
            <button class="tab-button" onclick="showTab('computer-vision')">Computer Vision</button>
            <button class="tab-button" onclick="showTab('physics')">Scientific ML</button>
        </div>
        
        <div id="genai" class="tab-content">
            <div style="margin: 40px 0;">
                <h3>Generative AI & Large Language Models</h3>
                <p style="font-size: 1em; color: #666; margin-bottom: 20px;">My research explores how to leverage large language models (LLMs) with reinforcement learning (RL), guided by partial‑match rewards and verbal self‑evaluation, to generate executable SQL queries from natural‑language questions on complex, industry‑scale databases. The framework combines in‑context group self‑evaluation (verbal‑RL) and a chain‑of‑thought RL pipeline to improve execution accuracy, dialect generalization, and industrial robustness in text‑to‑SQL tasks.</p>
                
                <h4>Research Contributions</h4>
                <ul style="margin-bottom: 20px;">
                    <li><strong>Execution-Accuracy Optimization:</strong> Improving SQL generation using partial-match reward functions.</li>
                    <li><strong>Unsupervised Self-Evaluation:</strong> Introducing verbal reinforcement learning for iterative reasoning refinement.</li>
                    <li><strong>Efficient Chain-of-Thought RL:</strong> Enabling smaller models to achieve high performance cost-effectively.</li>
                    <li><strong>Dialect and Domain Generalization:</strong> Enhancing robustness across SQL dialects and industrial database schemas.</li>
                    <li><strong>Industrial-Scale Deployment:</strong> Providing a scalable pipeline suitable for real-world database applications.</li>
                </ul>
                
                <div class="publication-item">
                    <strong>PaVeRL-SQL: Text-to-SQL via Partial-Match Rewards and Verbal Reinforcement Learning</strong><br>
                    <a href="https://arxiv.org/abs/2509.07159" target="_blank">arXiv:2509.07159</a>
                </div>
            </div>
        </div>
        
        <div id="computer-vision" class="tab-content">
            <div style="margin: 40px 0;">
                <h3>Computer Vision & Deep Learning</h3>
                <p style="font-size: 1em; color: #666; margin-bottom: 20px;">My research focuses on leveraging deep learning combined with Bayesian active learning to achieve data-efficient semantic segmentation. Using a pixel-level uncertainty-driven annotation framework enables near fully supervised performance with a fraction of labeled data, reducing annotation cost without compromising accuracy.</p>
                
                <h4>Research Contributions</h4>
                <ul style="margin-bottom: 20px;">
                    <li><strong>Data Efficiency:</strong> Developing methods that achieve high segmentation accuracy using minimal labeled pixels.</li>
                    <li><strong>Uncertainty-Aware Learning:</strong> Creating principled Bayesian measures to guide annotation and improve model reliability.</li>
                    <li><strong>Scalable Active Learning:</strong> Designing acquisition strategies that can be efficiently applied to large datasets and high-resolution images.</li>
                    <li><strong>Cross-Dataset Generalization:</strong> Building models and frameworks that maintain effectiveness across diverse segmentation benchmarks.</li>
                    <li><strong>Industrial Translation:</strong> Providing practical strategies to reduce annotation cost, facilitating deployment in real-world applications such as autonomous driving, medical imaging, and remote sensing.</li>
                </ul>
                
                <div class="publication-item">
                    <strong>Bayesian active learning for semantic segmentation</strong><br>
                    <a href="https://arxiv.org/abs/2408.01694" target="_blank">arXiv:2408.01694</a>
                </div>
            </div>
        </div>
        
        <div id="physics" class="tab-content">
            <div style="margin: 40px 0;">
                <h3>Scientific Machine Learning</h3>
                <p style="font-size: 1em; color: #666; margin-bottom: 20px;">My research focuses on integrating deep neural networks (DNNs) and graph neural networks (GNNs) with variational Monte Carlo (VMC) methods to solve complex quantum many-body problems. Convolutional DNNs are used to enhance VMC efficiency and accuracy, while scalable graph neural network variational ansatzes enable application to arbitrary geometries and larger system sizes. Together, these approaches demonstrate how deep learning can effectively and accurately address challenging scientific problems in computational physics..</p>
                
                <h4>Research Contributions</h4>
                <ul style="margin-bottom: 20px;">
                    <li><strong>Deep Learning + Physics Simulation:</strong> Systematic integration of deep learning (DNNs/GNNs) into variational Monte Carlo methods.</li>
                    <li><strong>High-Accuracy Scientific Computation:</strong> Achieved precise approximations of ground-state wavefunctions and related physical observables.</li>
                    <li><strong>Scalability and Generality:</strong> Demonstrated applicability to larger system sizes and arbitrary geometries.</li>
                    <li><strong>Algorithmic & System Innovations:</strong> Developed ISGO optimization, distributed training, and parameter-sharing mechanisms.</li>
                    <li><strong>Transferability & Reusability:</strong> Graph-based neural network architectures enable reusability across systems.</li>
                    <li><strong>Advancing Scientific Computation:</strong> Established deep learning as a viable tool for accelerating and enhancing quantum many-body simulations.</li>
                </ul>

                <div class="publication-item">
                    <strong>Scalable variational Monte Carlo with graph neural ansatz</strong><br>
                    <a href="https://arxiv.org/abs/2011.12453" target="_blank">arXiv:2011.12453</a><br>
                    <strong>Deep learning-enhanced variational Monte Carlo method for quantum many-body physics</strong><br>
                    <a href="https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.2.012039" target="_blank">Phys. Rev. Research 2, 012039(R)</a>
                </div>
            </div>
        </div>
    </div>
</div>

<div class="content-section">
    <h2>Education</h2>
    
    <div class="timeline-item">
        <div class="timeline-date">September 2013</div>
        <div class="timeline-title">Ph.D. in Theory and Simulation of Condensed Matter</div>
        <div class="timeline-company">Scuola Internazionale Superiore di Studi Avanzati di Trieste | Trieste, Italy</div>
    </div>
</div>

<div class="content-section">
    <h2>Professional Background</h2>
    
    <div class="timeline-item">
        <div class="timeline-date">Mar 2022 – Present</div>
        <div class="timeline-title">AI Scientist</div>
        <div class="timeline-company">AI Science Lab, Samsung SDS | San Jose, CA</div>
        
        <h4>Key Responsibilities:</h4>
        <ul>
            <li>Process and analyze data using various methods, design and maintain databases, and leverage large language models to interpret user data and database content.</li>
            <li>Research and develop core AI algorithms while transforming cutting-edge models into practical, impactful solutions.</li>
            <li>Develop and deploy AI-driven products, solutions, and pipelines to meet diverse user requirements.</li>
            <li>Collaborate across teams to translate user needs into scalable AI systems and ensure smooth technology development and deployment.</li>
        </ul>

        <h4>Major Projects:</h4>
        <ul>
            <li><strong>Data Understanding & Management:</strong> Analyzed, organized, and managed user data; developed pipelines and databases to support model training and user-driven applications.</li>
            <li><strong>Generative AI & Large Language Models:</strong> Designed and fine-tuned Text-to-SQL systems, developed data-efficient alignment strategies, customized multimodal LLMs for both text and tabular data, explored reinforcement learning techniques for policy optimization, and built intelligent agents with memory and multi-step reasoning capabilities.</li>
            <li><strong>Computer Vision:</strong> Built an active learning framework for image classification, object detection, and semantic segmentation tasks.</li>
        </ul>
    </div>
    
    <div class="timeline-item">
        <div class="timeline-date">Feb 2021 – Mar 2022</div>
        <div class="timeline-title">Senior Data Science Engineer</div>
        <div class="timeline-company">Nabors Industries | Houston, TX</div>
        <ul>
            <li>Develop deep learning models (RNN, LSTM, Transformer) for time series forecasting and pattern analysis.</li>
            <li>Implement MQTT-based communication systems with robust publisher–subscriber architecture for real-time data exchange.</li>
            <li>Design and manage PostgreSQL databases optimized for large-scale time series data storage and retrieval.</li>
            <li>Orchestrate end-to-end machine learning workflows using Apache Airflow on Ubuntu servers.</li>
            <li>Apply ResNet, GoogleNet, and LSTM architectures for human activity recognition in video data.</li>
        </ul>
    </div>
    
    <div class="timeline-item">
        <div class="timeline-date">Oct 2013 – Feb 2021</div>
        <div class="timeline-title">Research Associate</div>
        <div class="timeline-company">
          <p>Department of Physics & Astronomy, University of Tennessee, Knoxville | Knoxville, TN</p>
          <p>Physics & Astronomy Department, Rice University | Houston, TX</p>
          <p>Department of Physics & Astronomy, CSU Northridge | Northridge, CA</p>
        </div>
        <ul>
            <li>Developed efficient variational Monte Carlo codes to study entanglement entropy in U(1) gapless spin liquids with a spinon Fermi surface; published in Physical Review Letters.</li>
            <li>Implemented graph neural networks and distributed computation to study quantum many-body ground states using variational Monte Carlo; presented at NeurIPS 2020 (ML & Physical Sciences Workshop).</li>
            <li>Developed spin-1 SU(2) DMRG algorithms to explore dipolar and quadrupolar phases in 2D spin models; produced 10 papers, including two in Physical Review Letters.</li>
            <li>Designed convolutional neural networks and new optimization algorithms to accelerate variational Monte Carlo training for quantum many-body systems; published in Physical Review Research.</li>
            <li>Created new Monte Carlo algorithms to study chiral spin liquids in kagome and triangular models; published two Physical Review B papers with 150+ citations.</li>
            <li>Developed spin-1/2 SU(2) DMRG codes to investigate spin-liquid phases in triangular models; published two Physical Review B papers with 570+ citations and opened a new research direction in frustrated magnetism.</li>
        </ul>
    </div>
</div>
