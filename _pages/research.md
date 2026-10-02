---
layout: archive
title: "Research Overview"
permalink: /research/
author_profile: true
---

My research develops and applies **causal AI**, **explainable AI (XAI)**, **graph neural networks (GNNs)**, and **large language models (LLMs)** to complex data-driven problems. A central focus of my current work is building interpretable and clinically useful AI systems that integrate electronic health records, social determinants of health, patient-reported information, and unstructured data to support healthcare decision-making.
---

## Current Research

### Explainable AI for Radiation Therapy Interruptions
I develop interpretable machine learning, graph neural network, and causal inference approaches for predicting **unplanned radiation therapy interruptions (RTIs)**. This work integrates clinical, treatment, demographic, and social determinants of health data to identify factors associated with treatment disruption and support clinically actionable risk assessment.

Building on risk prediction, the current phase investigates **intervention-oriented explainability**, including mapping potentially modifiable risk factors to candidate interventions and using constrained perturbation simulations to examine how changes in patient-level factors affect predicted RTI risk. The goal is to move from explaining predictions toward clinically actionable decision support.

<figure class="research-figure research-figure--wide">
  <img src="/images/research/rti-xai-framework.jpg" alt="Framework for explainable prediction of radiation therapy interruptions">
  <figcaption><strong>Explainable AI framework for radiation therapy interruption prediction.</strong> Patient-level data are modeled using tabular and graph-based approaches, with explainability and structural inference supporting pretreatment risk estimation and clinical triage.</figcaption>
</figure>

### Multimodal Clinical AI and Digital Twins for Radiation Oncology
I work on AI-ready clinical data architectures that integrate structured EHR data, clinical narratives, treatment information, and social determinants of health. This includes **X-CART**, a scalable multimodal architecture for explainable AI-driven radiation oncology applications, and ongoing work on **digital twins** that model longitudinal treatment trajectories and clinically informed scenarios.

<figure class="research-figure research-figure--medium">
  <img src="/images/research/xcart-patient-journey.png" alt="X-CART-supported patient navigation journey during cancer treatment">
  <figcaption><strong>Proposed X-CART-supported cancer patient journey.</strong> Real-world clinical and community data inform patient screening, risk identification, coordinated navigation, supportive services, and longitudinal follow-up during radiation treatment.</figcaption>
</figure>

### Empathic and Agentic AI for Oncology Patient Navigation
I develop and evaluate AI systems for patient-centered oncology navigation using **synthetic patient personas and simulated clinical conversations**. This work studies empathy, communication quality, safety, clinical appropriateness, and conversational complexity. A related line of research examines agentic AI architectures and evaluation requirements for longitudinal healthcare tasks.

<figure class="research-figure research-figure--wide">
  <img src="/images/research/empathic-ai-simulation-framework.png" alt="Three-stage synthetic persona, dialogue simulation, and evaluation framework">
  <figcaption><strong>Empathic AI stress-testing framework.</strong> Synthetic patient personas support dual-agent, multi-turn oncology navigation simulations, followed by automated and human expert evaluation of dialogue quality, problem recognition, and clinical actionability.</figcaption>
</figure>

**Code:** [RTI Empathic AI Simulation](https://github.com/rezaurrashid/rti-empathic-ai-simulation/)

### Maternal Health Sentiment and Social-Media Analytics
I study health-related sentiment analysis in social-media data, with current work focused on pregnancy-related weight discussions on Reddit. This research benchmarks large language models and conventional NLP approaches against human expert annotations and examines model behavior under interpretive ambiguity in sensitive health contexts.

<figure class="research-figure research-figure--wide">
  <img src="/images/research/maternal-sentiment-benchmark.png" alt="Workflow for expert annotation and benchmarking of pregnancy-related Reddit sentiment models">
  <figcaption><strong>Sentiment benchmarking and deployment workflow.</strong> Reddit discussions are used to construct an expert-annotated reference set for benchmarking multiple model families, followed by scalable sentiment analysis of the broader unlabeled corpus.</figcaption>
</figure>

### Large-Scale Drug–Condition Association Discovery
I am investigating computational approaches for identifying candidate **off-label medication–condition relationships** from large-scale clinical data using distributed processing, temporal exposure definitions, and association measures such as PMI, normalized PMI, and lift. The current analysis covers approximately **146 million medication–condition relationships**.

### EHR-Based Phenotyping and Outcomes in Menière's Disease
I am collaborating with clinicians and informatics researchers on a large-scale EHR study of **Menière's disease and related vestibular disorders**. The research examines clinical factors associated with disease onset and develops longitudinal phenotypes for characterizing disease severity and progression.

The work combines diagnostic histories, symptoms, healthcare utilization, and treatment trajectories to study clinically meaningful outcomes such as symptom burden, disease extent, treatment escalation, and acute-care utilization. A parallel analysis examines potential clinical triggers and comorbidities associated with Menière's disease compared with patients undergoing evaluation for related vestibular conditions.
---

## Foundational and Prior Research

### Probabilistic Causal Discovery and Causal Feature Selection
My doctoral research focused on learning causal structure from observational data using probabilistic and graph-based approaches. I developed methods for moving from pairwise cause-effect relationships to larger causal graphs, extended this work using graph neural networks for probabilistic causal discovery, and developed causal feature-selection and evaluation frameworks.

<figure class="research-figure research-figure--wide">
  <img src="/images/research/causal-gnn-framework.png" alt="Graph neural network framework for probabilistic causal edge-direction prediction">
  <figcaption><strong>GNN-based probabilistic causal discovery framework.</strong> Statistical and causal information is encoded in a graph neural network that learns local and global dependencies and estimates probability distributions over causal edge directions.</figcaption>
</figure>

### Computational Social Science and Affective Polarization
I have applied causal inference, network analysis, and language models to study **affective polarization and information dynamics in social media**, including influencer effects and LLM-based measurement of polarized discourse.

<figure class="research-figure research-figure--wide">
  <img src="/images/research/polarization-interaction-network.png" alt="Social interaction networks compared with and without a focal conversation">
  <figcaption><strong>Conversation-level influence in a social interaction network.</strong> Comparing networks with and without a focal conversation illustrates how follower interactions and network connectivity can persist beyond an individual discussion.</figcaption>
</figure>

### Causal Analytics for Business Operations
During my doctoral research and an industry collaboration with **Lowe's Companies, Inc.**, I worked on causal and automated feature-generation methods for operational decision support, with applications to supply-chain and business outcomes.

**Open-source software:** [Causal Feature Selection](https://bitbucket.org/uqlab/causal_feature_selection/src/master/) | [Automated Feature Synthesis](https://bitbucket.org/uqlab/automated_feature_synthesis/src/master/)
---

## Earlier Academic Projects

### Graduate-Level Projects
- **Sentiment Analysis of Social Media Responses Using Spark & Python**: Multiclass SVM sentiment classification with distributed processing using Apache Spark. [GitHub](https://github.com/rezaurrashid/ITCS8190_CloudComputing_Fall2022/tree/main/final%20project/code)
- **COVID-19 Mortality-Rate Forecasting in the U.S.**: Time-series modeling in R. [GitHub](https://github.com/rezaurrashid/BINF8310-Spring2022/tree/master/Project)
- **Information-Theoretic Analysis of DNN & CNN Models**: Investigation of theoretical and information-based properties of deep neural networks.
- **Pneumonia Detection from X-ray Images**: CNN-based image classification for pneumonia detection. [GitHub](https://github.com/khyatimahajan/ml_project_fall_2019)

### Undergraduate-Level Projects
- **Human Fall Control System for Disabled People Using Double Inverted Pendulum**: Theoretical control-system approach for assistive fall prevention.
- **Library Book Finder Robot with Self-Navigation**: Self-navigation algorithm for an autonomous library book-finder robot.
- **Comparative Analysis of Gesture Recognition Methods**: Comparison of light-dependent and ultrasonic gesture-recognition approaches.
