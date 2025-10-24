# Awesome Agentic AI for Healthcare

![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

This repository is a curated list of research papers, projects, and resources related to the application of **agentic AI for healthcare**, including medical image analysis, EHR manipulation, counseling, drug discovery, patient dialogue, and healthcare administration. Agentic AI refers to artificial intelligence systems that can autonomously perform tasks, make decisions, and interact with their environment, often through the use of large language models (LLMs) and multi-agent systems.

We will try to make this list updated. If you found any error or any missed paper, please don't hesitate to open issues or pull requests.

---

<font size=5><center><b> Table of Contents </b> </center></font>
- [Latest Papers](#latest-papers)
  - [Year 2025](#year-2025)
  - [Year 2024](#year-2024)
  - [Year 2023](#year-2023)
- [Papers by Category](#papers-by-category)
  - [1. Clinical Agents](#1-clinical-agents)
    - [1.1 Multi-Modal Agents](#11-multi-modal-agents)
    - [1.2 Radiology Agents (CT, X-ray, etc.)](#12-radiology-agents-ct-x-ray-etc)
    - [1.3 Pathology Agents](#13-pathology-agents)
    - [1.4 Cardiovascular Imaging Agents](#14-cardiovascular-imaging)
    - [1.5 Sonography / Ultrasound Agents](#15-sonography--ultrasound)
    - [1.6 Radiotherapy Agents](#16-radiotherapy)
    - [1.7 Dermatology Agents](#17-dermatology)
    - [1.8 Dental Agents](#18-dental-agents)
    - [1.9 Genomics & Biomarker Agents](#19-genomics--biomarker-agents)
    - [1.10 EHR & Clinical Note Agents](#110-ehr--clinical-note-agents)
    - [1.11 Surgical Agents](#111-surgical-agents)
    - [1.12 Reasoning & Multi Agents](#112-reasoning--multi-agents)
  - [2. Patient-Facing Applications](#2-patient-facing-applications)
    - [2.1 Mental Health & CBT Agents](#21-mental-health--cbt-agents)
    - [2.2 Clinical Communication & Intake Agents](#22-clinical-communication--intake-agents)
    - [2.3 Screening & Personalized Care Agents](#23-screening--personalized-care-agents)
    - [2.4 General-purpose Healthcare Avatars](#24-general-purpose-healthcare-avatars)
  - [3. Drug Discovery & Development Agents](#3-drug-discovery--development)
  - [4. Healthcare Administration & Workflow Agents](#4-healthcare-administration--workflow)
  - [5. Datasets & Benchmarks](#5-datasets--benchmarks)
---

# Latest Papers

## Year 2025

1.  [arxiv 2025.9] **ShortageSim: Simulating Drug Shortages under Information Asymmetry** [[paper]](http://arxiv.org/abs/2509.01813)
2.  [arxiv 2025.9] **Code Like Humans: A Multi-Agent Solution for Medical Coding** [[paper]](http://arxiv.org/abs/2509.05378)
3.  [arxiv 2025.8] **The Anatomy of a Personal Health Agent** [[paper]](http://arxiv.org/abs/2508.20148)
4.  [arxiv 2025.8] **ChatThero: An LLM-Supported Chatbot for Behavior Change and Therapeutic Support in Addiction Recovery** [[paper]](http://arxiv.org/abs/2508.20996)
5.  [arxiv 2025.8] **Automated Clinical Problem Detection from SOAP Notes using a Collaborative Multi-Agent LLM Architecture** [[paper]](http://arxiv.org/abs/2508.21803)
6.  [arxiv 2025.8] **Trustworthy Agents for Electronic Health Records through Confidence Estimation** [[paper]](http://arxiv.org/abs/2508.19096)
8.  [arxiv 2025.8] **AT-CXR: Uncertainty-Aware Agentic Triage for Chest X-rays** [[paper]](http://arxiv.org/abs/2508.19322)
9.  [arxiv 2025.8] **End-to-End Agentic RAG System Training for Traceable Diagnostic Reasoning** [[paper]](http://arxiv.org/abs/2508.15746)
10. [arxiv 2025.8] **Organ-Agents: Virtual Human Physiology Simulator via LLMs** [[paper]](http://arxiv.org/abs/2508.14357)
11. [arxiv 2025.8] **A Multi-Agent Approach to Neurological Clinical Reasoning** [[paper]](https://arxiv.org/abs/2508.14063)
12. [arxiv 2025.8] **PASS: Probabilistic Agentic Supernet Sampling for Interpretable and Adaptive Chest X-Ray Reasoning** [[paper]](http://arxiv.org/abs/2508.10501v1)
13. [arxiv 2025.8] **HealthFlow: A Self-Evolving AI Agent with Meta Planning for Autonomous Healthcare Research** [[paper]](https://arxiv.org/abs/2508.02621) [[code]](https://github.com/yhzhu99/HealthFlow)
15. [arxiv 2025.6] **MedOrch: Medical Diagnosis with Tool-Augmented Reasoning Agents for Flexible Extensibility** [[paper]](https://arxiv.org/abs/2506.00235)
16. [arxiv 2025.8] **ConfAgents: A Conformal-Guided Multi-Agent Framework for Cost-Efficient Medical Diagnosis** [[paper]](https://arxiv.org/abs/2508.04915)
17. [arxiv 2025.8] **Colacare: Enhancing electronic health record modeling through large language model-driven multi-agent collaboration** [[paper]](https://arxiv.org/abs/2410.02551)[[project page]](https://colacare.netlify.app/)
21. [arxiv 2025.8] **FEAT: A Multi-Agent Forensic AI System with Domain-Adapted Large Language Model for Automated Cause-of-Death Analysis** [[paper]](https://arxiv.org/abs/2502.20301)
22. [arxiv 2025.8] **Are Large Language Models Dynamic Treatment Planners? An In Silico Study from a Prior Knowledge Injection Angle** [[paper]](http://arxiv.org/abs/2508.04755v1)
23. [arxiv 2025.8] **Tree-of-Reasoning: Towards Complex Medical Diagnosis via Multi-Agent Reasoning with Evidence Tree** [[paper]](http://arxiv.org/abs/2508.03038v1)
24. [arxiv 2025.8] **A Multi-Agent System for Complex Reasoning in Radiology Visual Question Answering** [[paper]](http://arxiv.org/abs/2508.02841v1)
25. [arxiv 2025.8] **Patho-AgenticRAG: Towards Multimodal Agentic Retrieval-Augmented Generation for Pathology VLMs via Reinforcement Learning** [[paper]](http://arxiv.org/abs/2508.02258v1) [[code]](https://github.com/Wenchuan-Zhang/Patho-AgenticRAG)
26. [arxiv 2025.8] **Agent-Based Feature Generation from Clinical Notes for Outcome Prediction** [[paper]](http://arxiv.org/abs/2508.01956v1)
27. [arxiv 2025.8] **GMAT: Grounded Multi-Agent Clinical Description Generation for Text Encoder in Vision-Language MIL for Whole Slide Image Classification** [[paper]](http://arxiv.org/abs/2508.01293v1)
28. [arxiv 2025.8] **A Multi-Agent Approach to Neurological Clinical Reasoning** [[paper]](https://arxiv.org/abs/2508.14063)
29. [biorxiv 2025.8] **BioScientistAgent: Designing LLM-Biomedical Agents with KG-Augmented RL Reasoning Modules for Drug Repurposing and Mechanistic of Action Elucidation** [[paper]](https://www.biorxiv.org/content/10.1101/2025.08.08.669291)
30. [arxiv 2025.7] **Agentic AI framework for end-to-end medical data inference** [[paper]](http://arxiv.org/abs/2507.18115v1)
31. [arxiv 2025.7] **Resilient Multi-Agent Negotiation for Medical Supply Chains: Integrating LLMs and Blockchain for Transparent Coordination** [[paper]](http://arxiv.org/abs/2507.17134v1)
32. [arxiv 2025.7] **AURA: A Multi-Modal Medical Agent for Understanding, Reasoning & Annotation** [[paper]](http://arxiv.org/abs/2507.16940v1)
33. [arxiv 2025.7] **Intelligent Virtual Sonographer (IVS): Enhancing Physician-Robot-Patient Communication** [[paper]](http://arxiv.org/abs/2507.13052v1)
34. [arxiv 2025.7] **A Comprehensive Survey of Electronic Health Record Modeling: From Deep Learning Approaches to Large Language Models** [[paper]](http://arxiv.org/abs/2507.12774v1) [[project page]](https://survey-on-tabular-data.github.io/)
35. [arxiv 2025.7] **Infherno: End-to-end agent-based FHIR resource synthesis from free-form clinical notes** [[paper]](http://arxiv.org/abs/2507.12261v1)
36. [arxiv 2025.7] **Multi-agent retrieval-augmented framework for evidence-based counterspeech against health misinformation** [[paper]](http://arxiv.org/abs/2507.07307v2)
37. [arxiv 2025.7] **AI-VaxGuide: An Agentic RAG-Based LLM for Vaccination Decisions** [[paper]](http://arxiv.org/abs/2507.03493v1)
38. [arxiv 2025.7] **Multi-Agent Reasoning for Cardiovascular Imaging Phenotype Analysis** [[paper]](http://arxiv.org/abs/2507.03460v2)
39. [arxiv 2025.7] **DynamiCare: A Dynamic Multi-Agent Framework for Interactive and Open-Ended Medical Decision-Making** [[paper]](http://arxiv.org/abs/2507.02616v1)
40. [arxiv 2025.7] **KERAP: A Knowledge-Enhanced Reasoning Approach for Accurate Zero-shot Diagnosis Prediction Using Multi-agent LLMs** [[paper]](http://arxiv.org/abs/2507.02773v2)
41. [arxiv 2025.7] **STELLA: Self-Evolving LLM Agent for Biomedical Research** [[paper]](http://arxiv.org/abs/2507.02004v1)
42. [arxiv 2025.6] **From EHRs to Patient Pathways: Scalable Modeling of Longitudinal Health Trajectories with LLMs** [[paper]](https://www.arxiv.org/abs/2506.04831)
43. [arxiv 2025.6] **Evidence-based diagnostic reasoning with multi-agent copilot for human pathology** [[paper]](http://arxiv.org/abs/2506.20964v1)
44. [arxiv 2025.6] **An agentic system for rare disease diagnosis with traceable reasoning** [[paper]](https://arxiv.org/abs/2506.20430) [[demo]](https://raredx.cn/doctor#/)
45. [arxiv 2025.6] **Standard Applicability Judgment and Cross-jurisdictional Reasoning: A RAG-based Framework for Medical Device Compliance** [[paper]](http://arxiv.org/abs/2506.18511v1)
46. [arxiv 2025.6] **From RAG to Agentic: Validating Islamic-Medicine Responses with LLM Agents** [[paper]](http://arxiv.org/abs/2506.15911v2)
47. [arxiv 2025.6] **PRISM2: Unlocking Multi-Modal General Pathology AI with Clinical Dialogue** [[paper]](http://arxiv.org/abs/2506.13063v1)
48. [arxiv 2025.6] **Tiered Agentic Oversight: A Hierarchical Multi-Agent System for Healthcare Safety** [[paper]](https://arxiv.org/pdf/2506.12482)
49. [arxiv 2025.6] **The Optimization Paradox in Clinical AI Multi-Agent Systems** [[paper]](http://arxiv.org/abs/2506.06574v1)
50. [arxiv 2025.6] **AUTOCT: Automating Interpretable Clinical Trial Prediction with LLM Agents** [[paper]](http://arxiv.org/abs/2506.04293v1)
51. [arxiv 2025.6] **AI Agents for Conversational Patient Triage: Preliminary Simulation-Based Evaluation with Real-World EHR Data** [[paper]](http://arxiv.org/abs/2506.04032v1)
52. [arxiv 2025.6] **VChatter: Exploring Generative Conversational Agents for Simulating Exposure Therapy to Reduce Social Anxiety** [[paper]](http://arxiv.org/abs/2506.03520v1)
53. [arxiv 2025.6] **AnnaAgent: Dynamic Evolution Agent System with Multi-Session Memory for Realistic Seeker Simulation** [[paper]](http://arxiv.org/abs/2506.00551v2) [[code]](https://github.com/sci-m-wang/AnnaAgent)
54. [arxiv 2025.6] **ReflecTool: Towards Reflection-Aware Tool-Augmented Clinical Agents** [[paper]](http://arxiv.org/abs/2410.17657v3)
55. [arxiv 2025.6] **RadFabric: Agentic AI System with Reasoning Capability for Radiology** [[Paper]](https://arxiv.org/abs/2506.14142) [[Project]](https://yidong11.github.io/Towards-Multi-Modal-Agentic-AI-System-for-Chest-X-Ray/) |
56. [arxiv 2025.5] **CDR-Agent: Intelligent Selection and Execution of Clinical Decision Rules Using Large Language Model Agents** [[paper]](http://arxiv.org/abs/2505.23055v1) [[code]](https://github.com/zhenxianglance/medagent-cdr-agent)
57. [arxiv 2025.5] **BehaviorSFT: Behavioral Token Conditioning for Clinical Agents Across the Proactivity Spectrum** [[paper]](http://arxiv.org/abs/2505.21757v1)
58. [arxiv 2025.5] **Silence is Not Consensus: Disrupting Agreement Bias in Multi-Agent LLMs via Catfish Agent for Clinical Decision Making** [[paper]](http://arxiv.org/abs/2505.21503v1)
59. [arxiv 2025.5] **CPathAgent: An Agent-based Foundation Model for Interpretable High-Resolution Pathology Image Analysis Mimicking Pathologists' Diagnostic Logic** [[paper]](http://arxiv.org/abs/2505.20510v1)
60. [arxiv 2025.5] **Are Vision Language Models Ready for Clinical Diagnosis? A 3D Medical Benchmark for Tumor-centric Visual Question Answering** [[paper]](http://arxiv.org/abs/2505.18915v1) [[code]](https://github.com/Schuture/DeepTumorVQA)
61. [arxiv 2025.5] **Beyond Correlation: Towards Causal Large Language Model Agents in Biomedicine** [[paper]](http://arxiv.org/abs/2505.16982v1)
62. [arxiv 2025.5] **Generator-Mediated Bandits: Thompson Sampling for GenAI-Powered Adaptive Interventions** [[paper]](http://arxiv.org/abs/2505.16311v1)
63. [arxiv 2025.5] **CT-Agent: A Multimodal-LLM Agent for 3D CT Radiology Question Answering** [[paper]](http://arxiv.org/abs/2505.16229v1)
64. [arxiv 2025.5] **A Risk Taxonomy for Evaluating AI-Powered Psychotherapy Agents** [[paper]](http://arxiv.org/abs/2505.15108v1)
65. [arxiv 2025.5] **MedAgentBoard: Benchmarking Multi-Agent Collaboration with Conventional Methods for Diverse Medical Tasks** [[paper]](http://arxiv.org/abs/2505.12371v1) [[project page]](https://medagentboard.netlify.app/)
66. [arxiv 2025.5] **A Multimodal Multi-Agent Framework for Radiology Report Generation** [[paper]](http://arxiv.org/abs/2505.09787v1)
67. [arxiv 2025.5] **DoctorAgent-RL: A Multi-Agent Collaborative Reinforcement Learning System for Multi-Turn Clinical Dialogue** [[paper]](https://arxiv.org/abs/2505.19630) [[code]](https://github.com/JarvisUSTC/DoctorAgent-RL)
68. [biorxiv 2025.5] **Biomni: A general-purpose biomedical ai agent** [[paper]](https://www.biorxiv.org/content/10.1101/2025.05.30.656746)
69. [arxiv 2025.4] **Llm agent swarm for hypothesis-driven drug discovery** [[paper]](http://arxiv.org/abs/2504.17967v1)
70. [arxiv 2025.4] **Towards a HIPAA Compliant Agentic AI System in Healthcare** [[paper]](http://arxiv.org/abs/2504.17669v1)
71. [arxiv 2025.4] **Customizing emotional support: How do individuals construct and interact with LLM-powered chatbots** [[paper]](http://arxiv.org/abs/2504.12943v2)
72. [arxiv 2025.4] **Privacy-Preserving Operating Room Workflow Analysis using Digital Twins** [[paper]](https://arxiv.org/abs/2504.12552)
73. [arxiv 2025.4] **An LLM-Driven Multi-Agent Debate System for Mendelian Diseases** [[paper]](http://arxiv.org/abs/2504.07881v2)
74. [arxiv 2025.4] **Txgemma: Efficient and agentic llms for therapeutics** [[paper]](https://arxiv.org/abs/2504.06196)
75. [medrxiv 2025.4] **TrialGenie: Empowering Clinical Trial Design with Agentic Intelligence and Real World Data** [[paper]](https://www.medrxiv.org/content/10.1101/2025.04.17.25326033)
76. [arxiv 2025.3] **Operating room workflow analysis via reasoning segmentation over digital twins** [[paper]](http://arxiv.org/abs/2503.21054v1)
77. [arxiv 2025.3] **TAMA: A Human--AI Collaborative Thematic Analysis Framework Using Multi-Agent LLMs for Clinical Interviews** [[paper]](https://arxiv.org/pdf/2503.20666)
78. [arxiv 2025.3] **Autonomous Radiotherapy Treatment Planning Using DOLA: A Privacy-Preserving, LLM-Based Optimization Agent** [[paper]](http://arxiv.org/abs/2503.17553v1)
79. [arxiv 2025.3] **The Application of MATEC (Multi-AI Agent Team Care) Framework in Sepsis Care** [[paper]](http://arxiv.org/abs/2503.16433v1)
80. [arxiv 2025.3] **MDTeamGPT: A Self-Evolving LLM-Based Multi-Agent Framework for Multi-Disciplinary Team Medical Consultation** [[paper]](http://arxiv.org/abs/2503.13856v1)
81. [arxiv 2025.3] **RAG-KG-IL: A Multi-Agent Hybrid Framework for Reducing Hallucinations and Enhancing LLM Reasoning through RAG and Incremental Knowledge Graph Learning Integration** [[paper]](http://arxiv.org/abs/2503.13514v1)
82. [arxiv 2025.3] **MAP: Evaluation and Multi-Agent Enhancement of Large Language Models for Inpatient Pathways** [[paper]](http://arxiv.org/abs/2503.13205v1)
83. [arxiv 2025.3] **TxAgent: An AI agent for therapeutic reasoning across a universe of tools** [[paper]](http://arxiv.org/abs/2503.10970v1)
84. [arxiv 2025.3] **Can A Society of Generative Agents Simulate Human Behavior and Inform Public Health Policy? A Case Study on Vaccine Hesitancy** [[paper]](http://arxiv.org/abs/2503.09639v4)
85. [arxiv 2025.3] **MedAgentsBench: Benchmarking Thinking Models and Agent Frameworks for Complex Medical Reasoning** [[paper]](http://arxiv.org/abs/2503.07459v2) [[project page]](https://github.com/gersteinlab/medagents-benchmark)
86. [arxiv 2025.3] **Towards conversational ai for disease management** [[paper]](http://arxiv.org/abs/2503.06074v1)
87. [arxiv 2025.3] **GEMA-Score: Granular Explainable Multi-Agent Score for Radiology Report Evaluation** [[paper]](https://arxiv.org/pdf/2503.05347)
88. [arxiv 2025.2] **MIND: Towards Immersive Psychological Healing with Multi-Agent Inner Dialogue** [[paper]](http://arxiv.org/abs/2502.19860v2)
89. [arxiv 2025.2] **Enhancing hepatopathy clinical trial efficiency: a secure, large language model-powered pre-screening pipeline** [[paper]](http://arxiv.org/abs/2502.18531v1)
90. [arxiv 2025.2] **RAG-Enhanced Collaborative LLM Agents for Drug Discovery** [[paper]](http://arxiv.org/abs/2502.17506v2)
91. [arxiv 2025.2] **Agentic Medical Knowledge Graphs Enhance Medical Question Answering: Bridging the Gap Between LLMs and Evolving Medical Knowledge** [[paper]](http://arxiv.org/abs/2502.13010v3)
92. [arxiv 2025.2] **An LLM-Powered Agent for Physiological Data Analysis: A Case Study on PPG-based Heart Rate Estimation** [[paper]](http://arxiv.org/abs/2502.12836v2)
93. [arxiv 2025.2] **Regulatory science innovation for generative AI and large language models in health and medicine: a global call for action** [[paper]](http://arxiv.org/abs/2502.07794v1)
94. [arxiv 2025.2] **Cami: A counselor agent supporting motivational interviewing through state inference and topic exploration** [[paper]](http://arxiv.org/abs/2502.02807v1)
95. [arxiv 2025.2] **MedRAX: Medical Reasoning Agent for Chest X-ray** [[paper]](http://arxiv.org/abs/2502.02673v2) [[code]](https://github.com/bowang-lab/MedRAX)
96. [arxiv 2025.2] **PathFinder: A Multi-Modal Multi-Agent System for Medical Diagnostic Decision-Making Applied to Histopathology** [[Paper]](https://arxiv.org/abs/2502.08916) [[project page]](https://pathfinder-dx.github.io/)
97. [arxiv 2025.2] **M^3Builder: A Multi-Agent System for Automated Machine Learning in Medical Imaging** [[paper]](https://arxiv.org/abs/2502.20301)
98. [arxiv 2025.1] **MedAgentBench: A Realistic Virtual EHR Environment to Benchmark Medical LLM Agents** [[paper]](http://arxiv.org/abs/2501.14654v2) [[project page]](https://github.com/stanfordmlgroup/MedAgentBench)
99. [arxiv 2025.1] **AI Chatbots as Professional Service Agents: Developing a Professional Identity** [[paper]](http://arxiv.org/abs/2501.14179v2)
100. [arxiv 2025.1] **Exploring the inquiry-diagnosis relationship with advanced patient simulators** [[paper]](http://arxiv.org/abs/2501.09484v2) [[project page]](https://github.com/PatientSimulator/PatientSimulator)
101. [arxiv 2025.1] **AutoCBT: An Autonomous Multi-agent Framework for Cognitive Behavioral Therapy in Psychological Counseling** [[paper]](http://arxiv.org/abs/2501.09426v1)
102. [medrxiv 2025.1] **Advancing the prediction and understanding of placebo responses in chronic back pain using large language models** [[paper]](https://doi.org/10.1101/2025.01.21.25320888)
103. [Nature] **Towards conversational diagnostic artificial intelligence** [[paper]](https://www.nature.com/articles/s41586-025-08866-7)
104. [Intelligent Medicine] **Evaluating large language models and agents in healthcare: key challenges in clinical applications** [[paper]](https://www.sciencedirect.com/science/article/pii/S2667102625000294)
105. [npj Digital Medicine] **Evaluating large language models as agents in the clinic** [[paper]](https://www.nature.com/articles/s41746-024-01083-y)
106. [Nature Medicine 2025] **An evaluation framework for clinical use of large language models in patient interaction tasks** [[paper]](https://doi.org/10.1038/s41591-024-03328-5)
107. [Nature Communications 2025] **An automated framework for assessing how well LLMs cite relevant medical references** [[paper]](https://doi.org/10.1038/s41467-025-58551-6)
108. [Nature BME 2025] **CRISPR-GPT for agentic automation of gene-editing experiments** [[paper]](https://doi.org/10.1038/s41551-025-01463-z)
109. [Nature Methods 2025] **GeneAgent: self-verification language agent for gene-set analysis using domain databases** [[paper]](https://doi.org/10.1038/s41592-025-02748-6)
110. [npj Digital Medicine] **CARE-AD: A Multi-Agent Large Language Model Framework for Alzheimer's Disease Prediction Using Longitudinal Clinical Notes** [[paper]](https://www.nature.com/articles/s41746-025-01940-4)
111. [npj Digital Medicine] **Vision-language model for report generation and outcome prediction in CT pulmonary angiogram** [[paper]](https://www.nature.com/articles/s41746-025-01807-8)
112. [npj Artificial Intelligence] **HealthcareAgent: Eliciting the Power of Large Language Models for Medical Consultation** [[paper]](https://www.nature.com/articles/s44387-025-00021-x.pdf)
113. [Scientific Reports 2025] **Democratizing cost-effective, agentic artificial intelligence to multilingual medical summarization through knowledge distillation** [[paper]](https://doi.org/10.1038/s41598-025-10451-x)
114. [Scientific Reports 2025] **A multi-agent system based on HNC for domain-specific machine translation** [[paper]](https://doi.org/10.1038/s41598-025-03414-9)
115. [biorxiv 2025.6] **HEAL-KGGen: A Hierarchical Multi-Agent LLM Framework with Knowledge Graph Enhancement for Genetic Biomarker-Based Medical Diagnosis** [[paper]](https://www.biorxiv.org/content/10.1101/2025.06.03.657521v1.full.pdf)
116. [JAMIA 2025] **Improving Large Language Model Applications in Biomedicine with Retrieval-Augmented Generation: A Systematic Review, Meta-Analysis, and Clinical Development Guidelines** [[paper]](https://doi.org/10.1093/jamia/ocaf008)
117. [JAMIA Open 2025] **Conversational health agents: a personalized large language model-powered agent framework** [[paper]](https://academic.oup.com/jamiaopen/article/8/4/ooaf067/8186991)
118. [JMIR] **The Effectiveness of a Custom AI Chatbot for Type 2 Diabetes Mellitus Health Literacy: Development and Evaluation Study** [[paper]](https://doi.org/10.2196/70131)
119. [JMIR Aging 2025] **The PDC30 Chatbot—Development of a Psychoeducational Resource on Dementia Caregiving Among Family Caregivers: Mixed Methods Acceptability Study** [[paper]](https://aging.jmir.org/2025/1/e63715)
120. [JoVE] **Evidence-based knowledge synthesis and hypothesis validation: Navigating biomedical knowledge bases via explainable ai and agentic systems** [[paper]](https://www.jove.com/v/67525/evidence-based-knowledge-synthesis-hypothesis-validation-navigating)
121. [arxiv 2024.8] **Drugagent: Multi-agent large language model-based reasoning for drug-target interaction prediction** [[paper]](https://arxiv.org/abs/2408.13378)
122. [Bioinformatics 2025] **ESCARGOT: an AI agent leveraging large language models, dynamic graph of thoughts, and biomedical knowledge graphs for enhanced reasoning** [[paper]](https://doi.org/10.1093/bioinformatics/btaf031)
123. [Healthcare (Basel) 2025] **MedScrubCrew: A Medical Multi-Agent Framework for Automating Appointment Scheduling Based on Patient-Provider Profile Resource Matching** [[paper]](https://doi.org/10.3390/healthcare13141649)
124. [Clinical Neurophysiology 2025] **Agent-guided AI-powered interpretation and reporting of nerve conduction studies and EMG (INSPIRE)** [[paper]](https://www.sciencedirect.com/science/article/pii/S1388245725006443)
125. [Expert Systems with Applications 2025] **A two-stage proactive dialogue generator for efficient clinical information collection using large language model** [[paper]](https://doi.org/10.1016/j.eswa.2025.127833)
126. [Physics in Medicine & Biology 2025] **A feasibility study of automating radiotherapy planning with large language model agents** [[paper]](https://doi.org/10.1088/1361-6560/adbff1)
127. [JCO 2025] **A large language model (LLM)-based multi-agent framework for risk stratification and treatment recommendations in localized prostate cancer (locPCa).** [[paper]](https://doi.org/10.1200/JCO.2025.43.16_suppl.5108)
128. [ICDH] **Voice-based AI Agents: Filling the Economic Gaps in Digital Health Delivery** [[paper]](https://ieeexplore.ieee.org/document/11120408/)
129. [IEEE EMBC 2025] **Knowledge-infused LLM-powered conversational health agent: A case study for diabetes patients** [[paper]](https://ieeexplore.ieee.org/document/10781547)
130. [ACL 2025] **Medical Graph RAG: Evidence-based Medical Large Language Model via Graph Retrieval-Augmented Generation** [[paper]](https://aclanthology.org/2025.acl-long.1381/)
131. [ACL Findings 2025] **MAM: Modular Multi-Agent Framework for Multi-Modal Medical Diagnosis via Role-Specialized Collaboration** [[paper]](https://aclanthology.org/2025.findings-acl.1298/)
132. [ACL Findings 2025] **ASTRID--An Automated and Scalable TRIaD for the Evaluation of RAG-based Clinical Question Answering Systems** [[paper]](https://aclanthology.org/2025.findings-acl.857/)
133. [NAACL 2025] **A Layered Debating Multi-Agent System for Similar Disease Diagnosis** [[paper]](https://aclanthology.org/2025.naacl-short.46/)
134. [NAACL 2025] **Menti: Bridging medical calculator and llm agent with nested tool calling** [[paper]](https://aclanthology.org/2025.naacl-long.263/)
135. [COLING 2025] **Unveiling performance challenges of large language models in low-resource healthcare: A demographic fairness perspective** [[paper]](https://aclanthology.org/2025.coling-main.485/)
136. [ICMI 2025] **An LLM-powered Socially Interactive Agent with Adaptive Facial Expressions for Conversing about Health** [[paper]](https://dl.acm.org/doi/10.1145/3686215.3688378)
137. [MICCAI 2025 (Oral)] **WSI-Agents: A Collaborative Multi-Agent System for Multi-Modal Whole Slide Image Analysis** [[Paper]](https://arxiv.org/abs/2507.14680) [[GitHub]](https://github.com/XinhengLyu/WSI-Agents)
138. [MICCAI 2025] **Multi-Agent Reasoning for Cardiovascular Imaging Phenotype Analysis** [[Paper]](http://arxiv.org/abs/2507.03460v2) [[GitHub]](https://github.com/MengyunQ/MESHAgents)
139. [MICCAI 2025] **DentEval: Fine-tuning-Free Expert-Aligned Assessment in Dental Education via LLM Agents** [[Paper]](https://link.springer.com/chapter/10.1007/978-3-032-04971-1_14) [[GitHub]](https://github.com/DXY0711/DentEval)
140. [MICCAI 2025] **CSAP-Assist: Instrument-Agent Dialogue Empowered Vision-Language Models for Collaborative Surgical Action Planning** [[Paper]](https://link.springer.com/chapter/10.1007/978-3-032-05114-1_14) [[GitHub]](https://github.com/einnullnull/Collaborative-Surgical-Action-Planning-Assist)  |
141. [ICT4AWE 2025] **MentalRAG: Developing an Agentic Framework for Therapeutic Support Systems** [[paper]](https://www.scitepress.org/Papers/2025/132674/132674.pdf)
142. [MLHC 2025] **Evaluation of Multi-Agent LLMs in Multidisciplinary Team Decision-Making for Challenging Cancer Cases** [[paper]](https://proceedings.mlr.press/v298/kim25a.html)
143. [Journal of imaging informatics in medicine] **AgentMRI: A Vison Language Model-Powered AI System for Self-regulating MRI Reconstruction with Multiple Degradations** [[paper]](https://link.springer.com/article/10.1007/s10278-025-01617-0)

## Year 2024

1.  [arxiv 2024.12] **KG4Diagnosis: A Hierarchical Multi-Agent LLM Framework with Knowledge Graph Enhancement for Medical Diagnosis** [[paper]](http://arxiv.org/abs/2412.16833v4)
2.  [arxiv 2024.12] **PsyDraw: A Multi-Agent Multimodal System for Mental Health Screening in Left-Behind Children** [[paper]](http://arxiv.org/abs/2412.14769v1)
3.  [IEEE Big Data] **SurgBox: Agent-Driven Operating Room Sandbox with Surgery Copilot** [[paper]](http://arxiv.org/abs/2412.05187v1) [[code]](https://github.com/franciszchen/SurgBox)
4.  [Bioinformatics] **AI-HOPE: an AI-driven conversational agent for enhanced clinical and genomic data integration in precision medicine research** [[paper]](https://academic.oup.com/bioinformatics/article/41/7/btaf359/8169327)
5.  [arxiv 2024.11] **Wearable Intelligent Throat Enables Natural Speech in Stroke Patients with Dysarthria** [[paper]](http://arxiv.org/abs/2411.18266v3)
6.  [arxiv 2024.11] **PIORS: Personalized Intelligent Outpatient Reception based on Large Language Model with Multi-Agents Medical Scenario Simulation** [[paper]](http://arxiv.org/abs/2411.13902v1) [[project page]](https://github.com/FudanDISC/PIORS)
7.  [arxiv 2024.10] **IMAS: A Comprehensive Agentic Approach to Rural Healthcare Delivery** [[paper]](http://arxiv.org/abs/2410.12868v1) [[project page]](https://github.com/uheal/imas)
8.  [arxiv 2024.10] **KGARevion: An AI Agent for Knowledge-Intensive Biomedical QA** [[paper]](http://arxiv.org/abs/2410.04660v2)
9.  [arxiv 2024.10] **Zodiac: A Cardiologist-Level LLM Framework for Multi-Agent Diagnostics** [[paper]](http://arxiv.org/abs/2410.02026v1)
10. [arxiv 2024.9] **Simulated patient systems are intelligent when powered by large language model-based AI agents** [[paper]](http://arxiv.org/abs/2409.18924v3)
11. [arxiv 2024.9] **On the limits of agency in agent-based models** [[paper]](http://arxiv.org/abs/2409.10568v3)
12. [arxiv 2024.9] **Chatting Up Attachment: Using LLMs to Predict Adult Bonds** [[paper]](http://arxiv.org/abs/2409.00347v1)
13. [MLHC 2024] **MALADE: Orchestration of LLM-powered Agents with Retrieval Augmented Generation for Pharmacovigilance** [[paper]](http://arxiv.org/abs/2408.01869v1) [[project page]](https://github.com/jihyechoi77/malade)
14. [arxiv 2024.8] **Agentic llm workflows for generating patient-friendly medical reports** [[paper]](http://arxiv.org/abs/2408.01112v2) [[project page]](https://github.com/malavikhasudarshan/Multi-Agent-Patient-Letter-Generation)
15. [arxiv 2024.7] **Compeer: A generative conversational agent for proactive peer support** [[paper]](http://arxiv.org/abs/2407.18064v2)
16. [arxiv 2024.7] **Cod, towards an interpretable medical agent using chain of diagnosis** [[paper]](http://arxiv.org/abs/2407.13301v2)
17. [arxiv 2024.7] **Cactus: Towards psychological counseling conversations using cognitive behavioral theory** [[paper]](http://arxiv.org/abs/2407.03103v2)
18. [TMI] **Integration of Multi-Source Medical Data for Medical Diagnosis Question Answering** [[paper]](https://ieeexplore.ieee.org/abstract/document/10752912)
19. [ICLR 2025 Oral] **Pathgen-1.6m: 1.6 million pathology image-text pairs generation through multi-agent collaboration** [[paper]](https://arxiv.org/abs/2407.00203) [[project page]](https://github.com/PathFoundation/PathGen-1.6M)
20. [arxiv 2024.7] **MentalAgora: A Gateway to Advanced Personalized Care in Mental Health through Multi-Agent Debating and Attribute Control** [[paper]](http://arxiv.org/abs/2407.02736v1)
21. [arxiv 2024.6] **Exploring llm multi-agents for icd coding** [[paper]](http://arxiv.org/abs/2406.15363v2)
22. [arxiv 2024.12] **Enhancing LLMs for Impression Generation in Radiology Reports through a Multi-Agent System** [[paper]](https://arxiv.org/abs/2412.06828)
23. [ICML 2024 AI for Science Workshop] **TriageAgent: Towards Better Multi-Agents Collaborations for Large Language Model-Based Clinical Triage** [[paper]](https://openreview.net/forum?id=9b5Z1t2EO3)
24. [KDD'24 Workshop] **EHRFlow: A Large Language Model-Driven Iterative Multi-Agent Electronic Health Record Data Analysis Workflow** [[paper]](https://www.pure.ed.ac.uk/ws/portalfiles/portal/487318240/EHRFlow_WU_DOA28062024_VOR_CC-BY.pdf)
25. [arxiv 2024.12] **Agents on the Bench: Large Language Model Based Multi-Agent Framework for Trustworthy Digital Justice** [[paper]](https://arxiv.org/abs/2412.18697)
26. [arxiv 2024.6] **Clinicallab: Aligning agents for multi-departmental clinical diagnostics in the real world** [[paper]](http://arxiv.org/abs/2406.13890v2)
27. [MLHS 2025] **Path-RAG: Knowledge-Guided Key Region Retrieval for Open-ended Pathology Visual Question Answering** [[paper]](https://proceedings.mlr.press/v259/naeem25a.html)
28. [NeurIPS 2024] **MEDIQ: Question-Asking LLMs and a Benchmark for Medical Information-Seeking** [[paper]](https://proceedings.neurips.cc/paper_files/paper/2024/file/32b80425554e081204e5988ab1c97e9a-Paper-Conference.pdf) [[project page]](https://github.com/stellalisy/mediQ)
29. [arxiv 2024.6] **CliBench: A Multifaceted and Multigranular Evaluation of Clinical Diagnosis with LLMs** [[paper]](https://arxiv.org/abs/2406.09923)
30. [arxiv 2024.5] **AgentClinic: a multimodal agent benchmark to evaluate AI in simulated clinical environments** [[paper]](https://arxiv.org/abs/2405.07960)
31. [arxiv 2024.5] **Inquire, Interact, and Integrate: A Proactive Agent Collaborative Framework for Zero-Shot Multimodal Medical Reasoning** [[paper]](http://arxiv.org/abs/2405.11640v1)
32. [AAAI 2025 workshop AI4Research] **Drugagent: Automating ai-aided drug discovery programming through llm multi-agent collaboration** [[paper]](https://arxiv.org/abs/2411.15692)
33. [arxiv 2024.5] **Agent Hospital: A Simulacrum of Hospital with Evolvable Medical Agents** [[paper]](http://arxiv.org/abs/2405.02957v3)
34. [EMNLP 2024] **Ehragent: Code empowers large language models for few-shot complex tabular reasoning on electronic health records** [[paper]](https://aclanthology.org/2024.emnlp-main.1245/)
35. [NeurIPS 2024 Oral] **Mdagents: An adaptive collaboration of llms for medical decision-making** [[paper]](https://proceedings.neurips.cc/paper_files/paper/2024/hash/90d1fc07f46e31387978b88e7e057a31-Abstract-Conference.html)  [[project page]](https://github.com/mitmedialab/MDAgents)
36. [arxiv 2024.3] **Llms-based few-shot disease predictions using ehr: A novel approach combining predictive agent reasoning and critical agent instruction** [[paper]](http://arxiv.org/abs/2403.15464v1)
37. [arxiv 2024.2] **AgentMD: Empowering Language Agents for Risk Prediction with Large-Scale Clinical Tool Learning** [[paper]](https://arxiv.org/abs/2402.13225)
38. [npj Digital Medicine] **PRISM: Patient Records Interpretation for Semantic Clinical Trial Matching using Large Language Models** [[paper]](https://www.nature.com/articles/s41746-024-01274-7)
39. [arxiv 2024.1] **A general-purpose AI avatar in healthcare** [[paper]](http://arxiv.org/abs/2401.12981v1)
40. [The Lancet Digital Health] **A future role for health applications of large language models depends on regulators enforcing safety standards** [[paper]](https://www.thelancet.com/journals/landig/article/PIIS2589-7500(24)00124-9/fulltext)
41. [npj Digital Medicine] **Autonomous medical evaluation for guideline adherence of large language models** [[paper]](https://www.nature.com/articles/s41746-024-01356-6)
42. [Diagn Interv Radiol 2024] **Large language models in radiology: fundamentals, applications, ethical considerations, risks, and future directions** [[paper]](https://www.anatolianjmed.org/pdf/beb8919b-f013-4ea1-b1c8-40332e840fe1/issues/2024-030-002.pdf#page=11)
43. [PACIFIC SYMPOSIUM ON BIOCOMPUTING 2024] **A conversational agent for early detection of neurotoxic effects of medications through automated intensive observation** [[paper]](https://www.worldscientific.com/doi/abs/10.1142/9789811286421_0003)
44. [JAMIA Open 2024] **Conversational health agents: A personalized llm-powered agent framework** [[paper]](https://academic.oup.com/jamiaopen/article/8/4/ooaf067/8186991) [[project page]](https://github.com/Institute4FutureHealth/CHA)
45. [JMIR 2024] **Mitigating cognitive biases in clinical decision-making through multi-agent conversations using large language models: simulation study** [[paper]](https://doi.org/10.2196/59439)
46. [JMIR 2024] **A language model--powered simulated patient with automated feedback for history taking: Prospective study** [[paper]](https://doi.org/10.2196/59213)
47. [arxiv 2024.2] **Development and Testing of a Novel Large Language Model-Based Clinical Decision Support Systems for Medication Safety in 12 Clinical Specialties** [[paper]](https://arxiv.org/abs/2402.01741)
48. [IEEE SoftCOM 2024] **A multi-agent architecture for privacy-preserving natural language interaction with FHIR-based electronic health records** [[paper]](https://ieeexplore.ieee.org/document/10721684/)
49. [IEEE ISDFS 2024] **Llm-based framework for administrative task automation in healthcare** [[paper]](https://ieeexplore.ieee.org/document/10527275)
50. [IEEE Access 2024] **Knowledge-Routed Automatic Diagnosis With Heterogeneous Patient-Oriented Graph** [[paper]](https://ieeexplore.ieee.org/iel8/6287639/10380310/10552852.pdf)
51. [EMNLP Findings 2024] **MMedAgent: Learning to Use Medical Tools with Multi-modal Agent** [[paper]](https://aclanthology.org/2024.findings-emnlp.510/)
52. [ACL Findings 2024] **Benchmarking large language models on communicative medical coaching: a dataset and a novel system** [[paper]](https://aclanthology.org/2024.findings-acl.94/)
53. [ACL Findings 2024] **Medagents: Large language models as collaborators for zero-shot medical reasoning** [[paper]](https://aclanthology.org/2024.findings-acl.33/)
54. [CHI 2024] **Understanding the impact of long-term memory on self-disclosure with large language model-driven chatbots for public health intervention** [[paper]](https://dl.acm.org/doi/full/10.1145/3613904.3642420)
55. [CHI EA 2024] **Conversational AI in health: Design considerations from a Wizard-of-Oz dermatology case study with users, clinicians and a medical LLM** [[paper]](https://dl.acm.org/doi/10.1145/3613905.3651891)
56. [ACM IMWUT 2024] **Talk2Care: An LLM-based Voice Assistant for Communication between Healthcare Providers and Older Adults** [[paper]](https://dl.acm.org/doi/10.1145/3659625)
57. [ArabicNLP 2024] **Synthetic arabic medical dialogues using advanced multi-agent llm techniques** [[paper]](https://aclanthology.org/2024.arabicnlp-1.2/)
58. [ECCV Workshop 2024] **Medco: Medical education copilots based on a multi-agent framework** [[paper]](https://link.springer.com/chapter/10.1007/978-3-031-91813-1_8)
59. [Healthcare Information 2024] **A Medical Consultation System for Geriatric Disease Based on Multi-agent Architecture and Knowledge Graph** [[paper]](https://link.springer.com/chapter/10.1007/978-981-96-5597-7_28)
60. [Biocomputing 2025] **Using large language models for efficient cancer registry coding in the real hospital setting: A feasibility study** [[paper]](https://doi.org/10.1142/9789819807024_0010)

## Year 2023

1.  [NeurIPS workshop 2023] **Are we going mad? benchmarking multi-agent debate between language models for medical q\&a** [[paper]](https://openreview.net/forum?id=Bfr0m4Ucl6)
2.  [arxiv 2023.1] **Talk2Care: Facilitating asynchronous patient-provider communication with large-language-model** [[paper]](https://arxiv.org/abs/2309.09357)
4.  [AMIA Annual Symposium Proceedings] **Understanding the benefits and challenges of using large language model-based conversational agents for mental well-being support** [[paper]](http://arxiv.org/abs/2307.15810v1)
5.  [Clinical NLP 2023] **DERA: enhancing large language model completions with dialog-enabled resolving agents** [[paper]](http://arxiv.org/abs/2303.17071v1) [[dataset]](https://github.com/curai/curai-research/tree/main/DERA)
6.  [JMIR] **The ChatGPT (generative artificial intelligence) revolution has made artificial intelligence approachable for medical professionals** [[paper]](https://doi.org/10.2196/48392)
7.  [JMIR] **Automated monitoring of adherence to evidenced-based clinical guideline recommendations: design and implementation study** [[paper]](https://www.jmir.org/2023/1/e41177/)
8.  [JMIR Med Educ 2023] **Using ChatGPT for clinical practice and medical education: cross-sectional survey of medical students’ and physicians’ perceptions** [[paper]]([https://mededu.jmir.org/2023/1/e48336](https://mededu.jmir.org/2023/1/e50658/))
9.  [CHI 2023] **Assertiveness-based agent communication for a personalized medicine on medical imaging diagnosis** [[paper]](https://dl.acm.org/doi/10.1145/3544548.3580682)



# Papers by Category

---

## **1. Clinical Agents**

### **1.1 Multi-Modal Agents**
*(Agents designed to process and reason over multiple data types like images, text, and structured data)*

| Title | Venue | Date | Paper Link | Project Page |
| :--- | :--- | :--- | :--- | :--- |
| **AURA: A Multi-modal Medical Agent for Understanding, Reasoning & Annotation** | arXiv | 2025.07 | [Paper](http://arxiv.org/abs/2507.16940v1) | ![Star](https://img.shields.io/github/stars/nimafathi/AURA.svg?style=social&label=Star) <br> [GitHub](https://github.com/nimafathi/AURA) |
| **MedAgent-Pro: Towards Evidence-based Multi-modal Medical Diagnosis via Reasoning Agentic Workflow** | arXiv | 2025.03 | [Paper](https://arxiv.org/abs/2503.18968) | ![Star](https://img.shields.io/github/stars/jinlab-imvr/MedAgent-Pro?style=social&label=Star) <br> [GitHub](https://github.com/jinlab-imvr/MedAgent-Pro) |
| **M^3Builder: A Multi-Agent System for Automated Machine Learning in Medical Imaging** | arXiv | 2025.02 | [Paper](https://arxiv.org/abs/2502.20301) | ![Star](https://img.shields.io/github/stars/MAGIC-AI4Med/M3Builder?style=social&label=Star) <br> [GitHub](https://github.com/MAGIC-AI4Med/M3Builder) |
| **MAM: Modular Multi-Agent Framework for Multi-Modal Medical Diagnosis via Role-Specialized Collaboration** | ACL | 2025 | [Paper](https://aclanthology.org/2025.findings-acl.1298/) | ![Star](https://img.shields.io/github/stars/yczhou001/MAM.svg?style=social&label=Star) <br> [GitHub](https://github.com/yczhou001/MAM) |
| **MMedAgent: Learning to Use Medical Tools with Multi-modal Agent** | EMNLP | 2024 | [Paper](https://aclanthology.org/2024.findings-emnlp.510/) | ![Star](https://img.shields.io/github/stars/Wangyixinxin/MMedAgent.svg?style=social&label=Star) <br> [GitHub](https://github.com/Wangyixinxin/MMedAgent) |


### **1.2 Radiology Agents (CT, X-ray, MRI etc.)**

| Title | Venue | Date | Paper Link | Project Page |
| :--- | :--- | :--- | :--- | :--- |
| **A Multi-Agent System for Complex Reasoning in Radiology Visual Question Answering** | arXiv | 2025.08 | [Paper](http://arxiv.org/abs/2508.02841v1) | Not Available |
| **AT-CXR: Uncertainty-Aware Agentic Triage for Chest X-rays** | arXiv | 2025.08 | [Paper](http://arxiv.org/abs/2508.19322v1) | ![Star](https://img.shields.io/github/stars/XLIAaron/uncertainty-aware-cxr-agent.svg?style=social&label=Star) <br> [GitHub](https://github.com/XLIAaron/uncertainty-aware-cxr-agent) |
| **PASS: Probabilistic Agentic Supernet Sampling for Interpretable and Adaptive Chest X-Ray Reasoning** | arXiv | 2025.08 | [Paper](http://arxiv.org/abs/2508.10501v1) | ![Star](https://img.shields.io/github/stars/ys-feng/PASS-Code.svg?style=social&label=Star) <br> [GitHub](https://github.com/ys-feng/PASS-Code) |
| **RadFabric: Agentic AI System with Reasoning Capability for Radiology** | arXiv | 2025.06 | [Paper](https://arxiv.org/abs/2506.14142) | [Project](https://yidong11.github.io/Towards-Multi-Modal-Agentic-AI-System-for-Chest-X-Ray/) |
| **A Multimodal Multi-Agent Framework for Radiology Report Generation** | arXiv | 2025.05 | [Paper](http://arxiv.org/abs/2505.09787v1) | Not Available |
| **CT-Agent: A Multimodal-LLM Agent for 3D CT Radiology Question Answering** | arXiv | 2025.05 | [Paper](http://arxiv.org/abs/2505.16229v1) | Not Available |
| **MedRAX: Medical reasoning agent for chest x-ray** | arXiv | 2025.02 | [Paper](http://arxiv.org/abs/2502.02673v2) | ![Star](https://img.shields.io/github/stars/bowang-lab/MedRAX.svg?style=social&label=Star) <br> [GitHub](https://github.com/bowang-lab/MedRAX) |
| **Vision-language model for report generation and outcome prediction in CT pulmonary angiogram** | npj Digital Medicine | 2025 | [Paper](https://www.nature.com/articles/s41746-025-01807-8) | ![Star](https://img.shields.io/github/stars/zzs95/CTPA-Agent.svg?style=social&label=Star) <br> [GitHub](https://github.com/zzs95/CTPA-Agent) |
| **AgentMRI: A Vison Language Model-Powered AI System for Self-regulating MRI Reconstruction with Multiple Degradations** | Journal of imaging informatics in medicine | 2025 | [Paper](https://link.springer.com/article/10.1007/s10278-025-01617-0) | Not Available |
| **Enhancing LLMs for Impression Generation in Radiology Reports through a Multi-Agent System** | arXiv | 2024.12 | [Paper](https://arxiv.org/abs/2412.06828) | Not Available |

### **1.3 Pathology Agents**

| Title | Venue | Date | Paper Link | Project Page |
| :--- | :--- | :--- | :--- | :--- |
| **GMAT: Grounded Multi-Agent Clinical Description Generation for Text Encoder in Vision-Language MIL** | arXiv | 2025.08 | [Paper](http://arxiv.org/abs/2508.01293v1) | Not Available |
| **Patho-AgenticRAG: Towards Multimodal Agentic Retrieval-Augmented Generation for Pathology VLMs** | arXiv | 2025.08 | [Paper](http://arxiv.org/abs/2508.02258v1) | ![Star](https://img.shields.io/github/stars/Wenchuan-Zhang/Patho-AgenticRAG.svg?style=social&label=Star) <br> [GitHub](https://github.com/Wenchuan-Zhang/Patho-AgenticRAG) |
| **Evidence-based diagnostic reasoning with multi-agent copilot for human pathology** | arXiv | 2025.06 | [Paper](http://arxiv.org/abs/2506.20964v1) | Not Available |
| **CPathAgent: An Agent-based Foundation Model for Interpretable High-Resolution Pathology Image Analysis** | arXiv | 2025.05 | [Paper](http://arxiv.org/abs/2505.20510v1) | Not Available |
| **PathFinder: A Multi-Modal Multi-Agent System for Medical Diagnostic Decision-Making Applied to Histopathology** | arXiv | 2025.02 | [Paper](https://arxiv.org/abs/2502.08916) | [project](https://pathfinder-dx.github.io/) |
| **WSI-Agents: A Collaborative Multi-Agent System for Multi-Modal Whole Slide Image Analysis** | MICCAI (Oral) | 2025 | [Paper](https://arxiv.org/abs/2507.14680) | ![Star](https://img.shields.io/github/stars/XinhengLyu/WSI-Agents.svg?style=social&label=Star) <br> [GitHub](https://github.com/XinhengLyu/WSI-Agents) |
| **Path-RAG: Knowledge-Guided Key Region Retrieval for Open-ended Pathology Visual Question Answering** | MLHS | 2025 | [Paper](https://proceedings.mlr.press/v259/naeem25a.html) | ![Star](https://img.shields.io/github/stars/embedded-robotics/path-rag.svg?style=social&label=Star) <br> [GitHub](https://github.com/embedded-robotics/path-rag) |
| **Pathgen-1.6m: 1.6 million pathology image-text pairs generation through multi-agent collaboration** | ICLR (Oral) | 2024.07 | [Paper](https://arxiv.org/abs/2407.00203) | ![Star](https://img.shields.io/github/stars/PathFoundation/PathGen-1.6M.svg?style=social&label=Star) <br> [GitHub](https://github.com/PathFoundation/PathGen-1.6M) |

### **1.4 Cardiovascular Imaging**

| Title | Venue | Date | Paper Link | Project Page |
| :--- | :--- | :--- | :--- | :--- |
| **Multi-Agent Reasoning for Cardiovascular Imaging Phenotype Analysis** | MICCAI | 2025.07 | [Paper](http://arxiv.org/abs/2507.03460v2) | ![Star](https://img.shields.io/github/stars/MengyunQ/MESHAgents.svg?style=social&label=Star) <br> [GitHub](https://github.com/MengyunQ/MESHAgents) |

### **1.5 Sonography / Ultrasound**

| Title | Venue | Date | Paper Link | Project Page |
| :--- | :--- | :--- | :--- | :--- |
| **Intelligent Virtual Sonographer (IVS): Enhancing Physician-Robot-Patient Communication** | arXiv | 2025.07 | [Paper](http://arxiv.org/abs/2507.13052v1) | ![Star](https://img.shields.io/github/stars/stytim/IVS.svg?style=social&label=Star) <br> [GitHub](https://github.com/stytim/IVS) |

### **1.6 Radiotherapy**

| Title | Venue | Date | Paper Link | Project Page |
| :--- | :--- | :--- | :--- | :--- |
| **Autonomous Radiotherapy Treatment Planning Using DOLA: A Privacy-Preserving, LLM-Based Optimization Agent** | arXiv | 2025.03 | [Paper](http://arxiv.org/abs/2503.17553v1) | Not Available |
| **A feasibility study of automating radiotherapy planning with large language model agents** | Physics in Medicine & Biology | 2025 | [Paper](https://doi.org/10.1088/1361-6560/adbff1) | Not Available |

### **1.7 Dermatology**

| Title | Venue | Date | Paper Link | Project Page |
| :--- | :--- | :--- | :--- | :--- |
| **Conversational AI in health: Design considerations from a Wizard-of-Oz dermatology case study with users, clinicians and a medical LLM** | CHI 'EA | 2024 | [Paper](https://dl.acm.org/doi/10.1145/3613905.3651891) | Not Available |

### **1.8 Dental Agents**

| Title | Venue | Date | Paper Link | Project Page |
| :--- | :--- | :--- | :--- | :--- |
| **DentEval: Fine-tuning-Free Expert-Aligned Assessment in Dental Education via LLM Agents** | MICCAI | 2025 | [Paper](https://link.springer.com/chapter/10.1007/978-3-032-04971-1_14) | ![Star](https://img.shields.io/github/stars/DXY0711/DentEval.svg?style=social&label=Star) <br> [GitHub](https://github.com/DXY0711/DentEval) |

### **1.9 Genomics & Biomarker Agents**

| Title | Venue | Date | Paper Link | Project Page |
| :--- | :--- | :--- | :--- | :--- |
| **Geneagent: self-verification language agent for gene-set analysis using domain databases** | Nature Methods | 2025 | [Paper](https://doi.org/10.1038/s41592-025-02748-6) | ![Star](https://img.shields.io/github/stars/ncbi-nlp/GeneAgent.svg?style=social&label=Star) <br> [GitHub](https://github.com/ncbi-nlp/GeneAgent) |
| **CRISPR-GPT for agentic automation of gene-editing experiments** | Nature BME | 2025 | [Paper](https://doi.org/10.1038/s41551-025-01463-z) | ![Star](https://img.shields.io/github/stars/cong-lab/crispr-gpt-pub.svg?style=social&label=Star) <br> [GitHub](https://github.com/cong-lab/crispr-gpt-pub) |
| **HEAL-KGGen: A Hierarchical Multi-Agent LLM Framework for Genetic Biomarker-Based Medical Diagnosis** | biorxiv | 2025 | [Paper](https://www.biorxiv.org/content/10.1101/2025.06.03.657521v1) | ![Star](https://img.shields.io/github/stars/Ayanami-E/HEAL-KGGen.svg?style=social&label=Star) <br> [GitHub](https://github.com/Ayanami-E/HEAL-KGGen) |
| **AI-HOPE: An AI-Driven conversational agent for enhanced clinical and genomic data integration** | Bioinformatics | 2024.12 | [Paper](https://academic.oup.com/bioinformatics/article/41/7/btaf359/8169327) | ![Star](https://img.shields.io/github/stars/Velazquez-Villarreal-Lab/AI-HOPE.svg?style=social&label=Star) <br> [GitHub](https://github.com/Velazquez-Villarreal-Lab/AI-HOPE)  |

### **1.10 EHR & Clinical Note Agents**

| Title | Venue | Date | Paper Link | Project Page |
| :--- | :--- | :--- | :--- | :--- |
| **Automated Clinical Problem Detection from SOAP Notes using a Collaborative Multi-Agent LLM Architecture** | arXiv | 2025.08 | [Paper](http://arxiv.org/abs/2508.21803v1) | Not Available |
| **SNOW: Agent-Based Feature Generation from Clinical Notes for Outcome Prediction** | arXiv | 2025.08 | [Paper](http://arxiv.org/abs/2508.01956v1) | [Project](https://joyeewang01.github.io/medical_data_scientist/) |
| **Trustworthy Agents for Electronic Health Records through Confidence Estimation** | arXiv | 2025.8 | [Paper](https://arxiv.org/abs/2508.19096) | ![Star](https://img.shields.io/github/stars/ldi-kyunghee/TrustEHRAgent.svg?style=social&label=Star) <br> [GitHub](https://github.com/ldi-kyunghee/TrustEHRAgent) |
| **Infherno: End-to-end agent-based FHIR resource synthesis from free-form clinical notes** | arXiv | 2025.07 | [Paper](http://arxiv.org/abs/2507.12261v1) | ![Star](https://img.shields.io/github/stars/j-frei/Infherno.svg?style=social&label=Star) <br> [GitHub](https://github.com/j-frei/Infherno) |
| **From EHRs to Patient Pathways: Scalable Modeling of Longitudinal Health Trajectories with LLMs** | arXiv | 2025.6 | [Paper](https://www.arxiv.org/abs/2506.04831) | Not Available |
| **CARE-AD: a multi-agent large language model framework for Alzheimer’s disease prediction** | npj Digital Medicine | 2025 | [Paper](https://www.nature.com/articles/s41746-025-01940-4) |  ![Star](https://img.shields.io/github/stars/alicelee1/ad_care.svg?style=social&label=Star) <br> [GitHub](https://github.com/alicelee1/ad_care) |
| **Colacare: Enhancing electronic health record modeling through large language model-driven multi-agent collaboration** | arXiv | 2024.10 | [Paper](https://arxiv.org/abs/2410.02551) | [[project]](https://colacare.netlify.app/) |
| **EHRFlow: A Large Language Model-Driven Iterative Multi-Agent Electronic Health Record Data Analysis Workflow** | KDD'24 Workshop | 2024.06 | [Paper](https://www.pure.ed.ac.uk/ws/portalfiles/portal/487318240/EHRFlow_WU_DOA28062024_VOR_CC-BY.pdf) | ![Star](https://img.shields.io/github/stars/PKU-AICare/EHRFlow.svg?style=social&label=Star) <br> [GitHub](https://github.com/PKU-AICare/EHRFlow)  |
| **A multi-agent architecture for privacy-preserving natural language interaction with FHIR-based electronic health records** | IEEE SoftCOM | 2024 | [Paper](https://ieeexplore.ieee.org/document/10721684/) | Not Available |

### **1.11 Surgical Agents**

| Title | Venue | Date | Paper Link | Project Page |
| :--- | :--- | :--- | :--- | :--- |
| **CSAP-Assist: Instrument-Agent Dialogue Empowered Vision-Language Models for Collaborative Surgical Action Planning** | MICCAI | 2025 | [Paper](https://link.springer.com/chapter/10.1007/978-3-032-05114-1_14) | ![Star](https://img.shields.io/github/stars/einnullnull/Collaborative-Surgical-Action-Planning-Assist.svg?style=social&label=Star) <br> [GitHub](https://github.com/einnullnull/Collaborative-Surgical-Action-Planning-Assist)  |
| **Privacy-Preserving Operating Room Workflow Analysis using Digital Twins** | arXiv | 2025.4 | [Paper](https://arxiv.org/abs/2504.12552) | Not Available  |


### **1.12 Reasoning & Multi Agents**

| Title | Venue | Date | Paper Link | Project Page |
| :--- | :--- | :--- | :--- | :--- |
| **ConfAgents: A Conformal-Guided Multi-Agent Framework for Cost-Efficient Medical Diagnosis** | arXiv | 2025.08 | [Paper](https://arxiv.org/abs/2508.04915) | ![Star](https://img.shields.io/github/stars/PKU-AICare/ConfAgents.svg?style=social&label=Star) <br> [GitHub](https://github.com/PKU-AICare/ConfAgents)  |
| **Tree-of-Reasoning: Towards Complex Medical Diagnosis via Multi-Agent Reasoning with Evidence Tree** | arXiv | 2025.08 | [Paper](http://arxiv.org/abs/2508.03038v1) | ![Star](https://img.shields.io/github/stars/tsukiiiiiiiii/TOR.svg?style=social&label=Star) <br> [GitHub](https://github.com/tsukiiiiiiiii/TOR) |
| **End-to-End Agentic RAG System Training for Traceable Diagnostic Reasoning** | arXiv | 2025.8 | [Paper](http://arxiv.org/abs/2508.15746) | ![Star](https://img.shields.io/github/stars/MAGIC-AI4Med/Deep-DxSearch.svg?style=social&label=Star) <br> [GitHub](https://github.com/MAGIC-AI4Med/Deep-DxSearch) |
| **A Multi-Agent Approach to Neurological Clinical Reasoning** | arXiv | 2025.8 | [Paper](https://arxiv.org/abs/2508.14063) | Not Available |
| **KERAP: A knowledge-enhanced reasoning approach for accurate zero-shot diagnosis prediction** | arXiv | 2025.07 | [Paper](http://arxiv.org/abs/2507.02773v2) | ![Star](https://img.shields.io/github/stars/constantjxyz/KERAP.svg?style=social&label=Star) <br> [GitHub](https://github.com/constantjxyz/KERAP) |
| **An agentic system for rare disease diagnosis with traceable reasoning** | arXiv | 2025.06 | [Paper](https://arxiv.org/abs/2506.20430) | [[demo]](https://raredx.cn/doctor#/) |
| **MedOrch: Medical Diagnosis with Tool-Augmented Reasoning Agents for Flexible Extensibility** | arXiv | 2025.06 | [Paper](https://arxiv.org/abs/2506.00235) | Not Available |
| **The Optimization Paradox in Clinical AI Multi-Agent Systems** | arXiv | 2025.6 | [Paper](http://arxiv.org/abs/2506.06574) | ![Star](https://img.shields.io/github/stars/som-shahlab/opt-paradox.svg?style=social&label=Star) <br> [GitHub](https://github.com/som-shahlab/opt-paradox) |
| **DoctorAgent-RL: A Multi-Agent Collaborative Reinforcement Learning System for Multi-Turn Clinical Dialogue** | arXiv | 2025.5 | [Paper](https://arxiv.org/abs/2505.19630) | ![Star](https://img.shields.io/github/stars/JarvisUSTC/DoctorAgent-RL.svg?style=social&label=Star) <br> [GitHub](https://github.com/JarvisUSTC/DoctorAgent-RL) |
| **Silence is Not Consensus: Disrupting Agreement Bias in Multi-Agent LLMs via Catfish Agent for Clinical Decision Making** | arXiv | 2025.5 | [Paper](http://arxiv.org/abs/2505.21503) | Not Available |
| **MDTeamGPT: A Self-Evolving LLM-Based Multi-Agent Framework for Multi-Disciplinary Team Medical Consultation** | arXiv | 2025.03 | [Paper](http://arxiv.org/abs/2503.13856v1) | ![Star](https://img.shields.io/github/stars/KaiChenNJ/MDTeamGPT.svg?style=social&label=Star) <br> [GitHub](https://github.com/KaiChenNJ/MDTeamGPT) |
| **The Application of MATEC (Multi-AI Agent Team Care) Framework in Sepsis Care** | arXiv | 2025.03 | [Paper](http://arxiv.org/abs/2503.16433) | Not Available |
| **Agentic Medical Knowledge Graphs Enhance Medical Question Answering: Bridging the Gap Between LLMs and Evolving Medical Knowledge** | arXiv | 2025.02 | [Paper](http://arxiv.org/abs/2502.13010) | ![Star](https://img.shields.io/github/stars/MrRezaeiUofT/AMG-RAG.svg?style=social&label=Star) <br> [GitHub](https://github.com/MrRezaeiUofT/AMG-RAG) |
| **A Layered Debating Multi-Agent System for Similar Disease Diagnosis** | NAACL | 2025 | [Paper](https://aclanthology.org/2025.naacl-short.46/) | Not Available |
| **KG4Diagnosis: A Hierarchical Multi-Agent LLM Framework with Knowledge Graph Enhancement** | arXiv | 2024.12 | [Paper](http://arxiv.org/abs/2412.16833v4) | Not Available |
| **Zodiac: A Cardiologist-Level LLM Framework for Multi-Agent Diagnostics** | arXiv | 2024.10 | [Paper](http://arxiv.org/abs/2410.02026v1) | Not Available |
| **MedAgents: Large Language Models as Collaborators for Zero-shot Medical Reasoning** | ACL 2024 Findings | 2023.11 | [Paper](https://arxiv.org/abs/2311.10537) | ![Star](https://img.shields.io/github/stars/gersteinlab/MedAgents.svg?style=social&label=Star) <br> [GitHub](https://github.com/gersteinlab/MedAgents) |



## **2. Patient-Facing Applications**

### **2.1 Mental Health & CBT Agents**

| Title                                                                                                             | Venue          | Date    | Paper Link                                 | Project Page                                                                                                                                                                  |
| :---------------------------------------------------------------------------------------------------------------- | :------------- | :------ | :----------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ChatThero: An LLM-Supported Chatbot for Behavior Change and Therapeutic Support in Addiction Recovery** | arXiv          | 2025.08 | [Paper](http://arxiv.org/abs/2508.20996) |  ![Star](https://img.shields.io/github/stars/believewhat/ChatThero.svg?style=social\&label=Star) <br> [GitHub Reproduce](https://github.com/believewhat/ChatThero)                                                                                                                                                                  |
| **VChatter: Exploring Generative Conversational Agents for Simulating Exposure Therapy to Reduce Social Anxiety** | arXiv          | 2025.06 | [Paper](http://arxiv.org/abs/2506.03520v1) | Not Available                                                                                                                                                                 |
| **AnnaAgent: Dynamic Evolution Agent System with Multi-Session Memory for Realistic Seeker Simulation**                                 | arXiv  | 2025.06 | [Paper](http://arxiv.org/abs/2506.00551)  | ![Star](https://img.shields.io/github/stars/sci-m-wang/AnnaAgent.svg?style=social\&label=Star) <br> [GitHub](https://github.com/sci-m-wang/AnnaAgent) |
| **MIND: Towards Immersive Psychological Healing with Multi-Agent Inner Dialogue**                                 | ICML workshop  | 2025.02 | [Paper](https://arxiv.org/abs/2502.19860)  | ![Star](https://img.shields.io/github/stars/leoliu0618/mind-therapy-app.svg?style=social\&label=Star) <br> [GitHub Reproduce](https://github.com/leoliu0618/mind-therapy-app) |
| **Cami: A counselor agent supporting motivational interviewing through state inference and topic exploration**    | arXiv          | 2025.02 | [Paper](http://arxiv.org/abs/2502.02807v1) | ![Star](https://img.shields.io/github/stars/IzzetYoung/CAMI.svg?style=social\&label=Star) <br> [GitHub](https://github.com/IzzetYoung/CAMI)                                   |
| **Autocbt: An autonomous multi-agent framework for cognitive behavioral therapy in psychological counseling**     | arXiv          | 2025.01 | [Paper](http://arxiv.org/abs/2501.09426v1) | Not Available                                                                                                                                                                 |
| **PsyDraw: A Multi-Agent Multimodal System for Mental Health Screening in Left-Behind Children**                  | arXiv          | 2024.12 | [Paper](http://arxiv.org/abs/2412.14769v1) | ![Star](https://img.shields.io/github/stars/LYiHub/psydraw.svg?style=social\&label=Star) <br> [GitHub](https://github.com/LYiHub/psydraw)    |
| **Cactus: Towards psychological counseling conversations using cognitive behavioral theory**                      | EMNLP Findings | 2024.07 | [Paper](http://arxiv.org/abs/2407.03103v2) | ![Star](https://img.shields.io/github/stars/coding-groot/cactus.svg?style=social\&label=Star) <br> [GitHub](https://github.com/coding-groot/cactus)                           |
| **MentalAgora: A Gateway to Advanced Personalized Care in Mental Health through Multi-Agent Debating**            | arXiv          | 2024.07 | [Paper](http://arxiv.org/abs/2407.02736v1) | ![Star](https://img.shields.io/github/stars/jennylee03/MentalAgora.svg?style=social\&label=Star) <br> [GitHub](https://github.com/jennylee03/MentalAgora)                     |
| **Compeer: A generative conversational agent for proactive peer support** | arXiv | 2024.07 | [Paper](http://arxiv.org/abs/2407.18064v2) | ![Star](https://img.shields.io/github/stars/liutj9/ComPeer.svg?style=social\&label=Star) <br> [GitHub](https://github.com/liutj9/ComPeer)  |
| **Understanding the benefits and challenges of using large language model-based conversational agents for mental well-being support** | AMIA Annual Symposium Proceedings | 2023.07 | [Paper](http://arxiv.org/abs/2307.15810v1) | Not Available |


### **2.2 Clinical Communication & Intake Agents**

| Title                                                                                             | Venue                            | Date   | Paper Link                                                              | Project Page                                                                                                                                                      |
| :------------------------------------------------------------------------------------------------ | :------------------------------- | :----- | :---------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **AI Agents for Conversational Patient Triage: Preliminary Simulation-Based Evaluation with Real-World EHR Data**     | arXiv                       | 2025.6   | Not Available |
| **A two-stage proactive dialogue generator for efficient clinical information collection**        | Expert Systems with Applications | 2025   | [Paper](https://doi.org/10.1016/j.eswa.2025.127833)                     | Not Available                                                                                                                                                     |
| **PIORS: Personalized Intelligent Outpatient Reception based on Large Language Model with Multi-Agents Medical Scenario Simulation** | arXiv | 2024.11 | [Paper](http://arxiv.org/abs/2411.13902v1) | ![Star](https://img.shields.io/github/stars/FudanDISC/PIORS.svg?style=social&label=Star) <br> [GitHub](https://github.com/FudanDISC/PIORS) |
| **A language model--powered simulated patient with automated feedback for history taking: Prospective study** | JMIR | 2024 | [Paper](https://doi.org/10.2196/59213) | Not Available |
| **Conversational health agents: a personalized large language model-powered agent framework**     | JAMIA Open                       | 2024   | [Paper](https://academic.oup.com/jamiaopen/article/8/4/ooaf067/8186991) | ![Star](https://img.shields.io/github/stars/Institute4FutureHealth/CHA.svg?style=social\&label=Star) <br> [GitHub](https://github.com/Institute4FutureHealth/CHA) |
| **Talk2Care: Facilitating asynchronous patient-provider communication with large-language-model** | arXiv                            | 2023.9 | [Paper](https://arxiv.org/abs/2309.09357)                               | Not Available    

### **2.3 Screening & Personalized Care Agents**

| Title                                                                                                                       | Venue                             | Date    | Paper Link                                                                  | Project Page                                   |
| :-------------------------------------------------------------------------------------------------------------------------- | :-------------------------------- | :------ | :-------------------------------------------------------------------------- | :--------------------------------------------- |
| **AI-VaxGuide: An Agentic RAG-Based LLM for Vaccination Decisions**                                                         | arXiv                             | 2025.07 | [Paper](http://arxiv.org/abs/2507.03493v1)                                  | [huggingface](https://huggingface.co/VaxGuide) |
| **A Conversational Agent for Early Detection of Neurotoxic Effects of Medications through Automated Intensive Observation** | PACIFIC SYMPOSIUM ON BIOCOMPUTING | 2024    | [Paper](https://www.worldscientific.com/doi/abs/10.1142/9789811286421_0003) | Not Available                                  |

### **2.4 General-purpose Healthcare Avatars**

| Title                                         | Venue | Date    | Paper Link                                 | Project Page  |
| :-------------------------------------------- | :---- | :------ | :----------------------------------------- | :------------ |
| **The Anatomy of a Personal Health Agent** | arXiv | 2025.08 | [Paper](http://arxiv.org/abs/2508.20148v1) | Not Available |
| **A general-purpose AI avatar in healthcare** | arXiv | 2024.01 | [Paper](http://arxiv.org/abs/2401.12981v1) | Not Available |



## **3. Drug Discovery & Development**

| Title | Venue | Date | Paper Link | Project Page |
| :--- | :--- | :--- | :--- | :--- |
| **BioScientistAgent: Designing LLM-Biomedical Agents with KG-Augmented RL Reasoning Modules** | biorxiv | 2025.08 | [Paper](https://www.biorxiv.org/content/10.1101/2025.08.08.669291) | Not Available |
| **RAG-Enhanced Collaborative LLM Agents for Drug Discovery** | arXiv | 2025.02 | [Paper](http://arxiv.org/abs/2502.17506v2) | Not Available |
| **Large Language Model Agent for Modular Task Execution in Drug Discovery** | arXiv | 2025.07 | [Paper](https://arxiv.org/abs/2507.02925) | ![Star](https://img.shields.io/github/stars/hoon-ock/AgentD.svg?style=social&label=Star) <br> [GitHub](https://github.com/hoon-ock/AgentD)  |
| **AUTOCT: Automating Interpretable Clinical Trial Prediction with LLM Agents** | arXiv | 2025.06 | [Paper](http://arxiv.org/abs/2506.04293v1) | ![Star](https://img.shields.io/github/stars/lclarice/autoct.svg?style=social&label=Star) <br> [GitHub](https://github.com/lclarice/autoct) |
| **Llm agent swarm for hypothesis-driven drug discovery** | arXiv | 2025.04 | [Paper](http://arxiv.org/abs/2504.17967v1) | Not Available |
| **Txgemma: Efficient and agentic llms for therapeutics** | arXiv | 2025.04 | [Paper](https://arxiv.org/abs/2504.06196) | Not Available |
| **TrialGenie: Empowering Clinical Trial Design with Agentic Intelligence and Real World Data** | medRxiv | 2025.04 | [Paper](https://www.medrxiv.org/content/10.1101/2025.04.17.25326033) | Not Available |
| **TxAgent: An AI agent for therapeutic reasoning across a universe of tools** | arXiv | 2025.03 | [Paper](http://arxiv.org/abs/2503.10970v1) | ![Star](https://img.shields.io/github/stars/mims-harvard/TxAgent.svg?style=social&label=Star) <br> [GitHub](https://github.com/mims-harvard/TxAgent) |
| **Drugagent: Automating ai-aided drug discovery programming through llm multi-agent collaboration** | AAAI 2025 workshop AI4Research | 2024.11 | [Paper](https://arxiv.org/abs/2411.15692) |  ![Star](https://img.shields.io/github/stars/FermiQ/drugagent.svg?style=social&label=Star) <br> [GitHub](https://github.com/FermiQ/drugagent)  |
| **Drugagent: Multi-agent large language model-based reasoning for drug-target interaction prediction** | arXiv | 2024.08 | [Paper](https://arxiv.org/abs/2408.13378) |  ![Star](https://img.shields.io/github/stars/zatpds/drugagent.svg?style=social&label=Star) <br> [GitHub](https://github.com/zatpds/drugagent)  |
| **PRISM: Patient Records Interpretation for Semantic Clinical Trial Matching using Large Language Models** | npj Digital Medicine | 2024.01 | [Paper](https://www.nature.com/articles/s41746-024-01274-7) | Not Available |
| **MALADE: Orchestration of LLM-powered Agents with Retrieval Augmented Generation for Pharmacovigilance** | MLHC | 2024 | [Paper](http://arxiv.org/abs/2408.01869v1) | ![Star](https://img.shields.io/github/stars/jihyechoi77/malade.svg?style=social&label=Star) <br> [GitHub](https://github.com/jihyechoi77/malade) |

## **4. Healthcare Administration & Workflow**

| Title | Venue | Date | Paper Link | Project Page |
| :--- | :--- | :--- | :--- | :--- |
| **ShortageSim: Simulating Drug Shortages under Information Asymmetry** | arXiv | 2025.09 | [Paper](http://arxiv.org/abs/2509.01813v1) | ![Star](https://img.shields.io/github/stars/Lemutisme/ShortageSim.svg?style=social&label=Star) <br> [GitHub](https://github.com/Lemutisme/ShortageSim)  |
| **Code Like Humans: A Multi-Agent Solution for Medical Coding** | arXiv | 2025.09 | [Paper](http://arxiv.org/abs/2509.05378v1) | Not Available |
| **Resilient Multi-Agent Negotiation for Medical Supply Chains: Integrating LLMs and Blockchain** | arXiv | 2025.07 | [Paper](http://arxiv.org/abs/2507.17134v1) | Not Available |
| **Standard Applicability Judgment and Cross-jurisdictional Reasoning: A RAG-based Framework for Medical Device Compliance** | arXiv | 2025.06 | [Paper](http://arxiv.org/abs/2506.18511v1) | Not Available |
| **Operating room workflow analysis via reasoning segmentation over digital twins** | arXiv | 2025.03 | [Paper](http://arxiv.org/abs/2503.21054v1) | Not Available |
| **MedScrubCrew: A Medical Multi-Agent Framework for Automating Appointment Scheduling** | Healthcare (Basel) | 2025 | [Paper](https://doi.org/10.3390/healthcare13141649) | Not Available |
| **IMAS: A Comprehensive Agentic Approach to Rural Healthcare Delivery** | arXiv | 2024.10 | [Paper](http://arxiv.org/abs/2410.12868v1) | ![Star](https://img.shields.io/github/stars/uheal/imas.svg?style=social&label=Star) <br> [GitHub](https://github.com/uheal/imas) |
| **Exploring llm multi-agents for icd coding** | arXiv | 2024.06 | [Paper](http://arxiv.org/abs/2406.15363v2) | Not Available |
| **Llm-based framework for administrative task automation in healthcare** | IEEE ISDFS | 2024 | [Paper](https://ieeexplore.ieee.org/document/10527275) | Not Available |

## **5. Datasets & Benchmarks**

| Title | Venue | Date | Paper Link | Project Page |
| :--- | :--- | :--- | :--- | :--- |
| **MedAgentBoard: Benchmarking Multi-Agent Collaboration with Conventional Methods for Diverse Medical Tasks** | arXiv | 2025.05 | [Paper](http://arxiv.org/abs/2505.12371v1) | ![Star](https://img.shields.io/github/stars/yhzhu99/MedAgentBoard.svg?style=social&label=Star) <br> [GitHub](https://github.com/yhzhu99/MedAgentBoard) |
| **MedAgentsBench: Benchmarking Thinking Models and Agent Frameworks for Complex Medical Reasoning** | arXiv | 2025.03 | [Paper](http://arxiv.org/abs/2503.07459v2) | ![Star](https://img.shields.io/github/stars/gersteinlab/medagents-benchmark.svg?style=social&label=Star) <br> [GitHub](https://github.com/gersteinlab/medagents-benchmark) |
| **MedAgentBench: A Realistic Virtual EHR Environment to Benchmark Medical LLM Agents** | arXiv | 2025.01 | [Paper](http://arxiv.org/abs/2501.14654v2) | ![Star](https://img.shields.io/github/stars/stanfordmlgroup/MedAgentBench.svg?style=social&label=Star) <br> [GitHub](https://github.com/stanfordmlgroup/MedAgentBench) |
| **CliBench: A Multifaceted and Multigranular Evaluation of Clinical Diagnosis with LLMs** | arXiv | 2024.06 | [Paper](https://arxiv.org/abs/2406.09923) | ![Star](https://img.shields.io/github/stars/clibench/clibench.svg?style=social&label=Star) <br> [GitHub](https://github.com/clibench/clibench) |
| **MediQ: Question-Asking LLMs for Adaptive and Reliable Clinical Reasoning** | arXiv | 2024.06 | [Paper](https://arxiv.org/abs/2406.00922) | ![Star](https://img.shields.io/github/stars/stellalisy/mediQ.svg?style=social&label=Star) <br> [GitHub](https://github.com/stellalisy/mediQ) |
| **AgentClinic: a multimodal agent benchmark to evaluate AI in simulated clinical environments** | arXiv | 2024.05 | [Paper](https://arxiv.org/abs/2405.07960) | ![Star](https://img.shields.io/github/stars/samuelschmidgall/agentclinic.svg?style=social&label=Star) <br> [GitHub](https://github.com/samuelschmidgall/agentclinic) |
| **Agent Hospital: A Simulacrum of Hospital with Evolvable Medical Agents** | arXiv | 2024.05 | [Paper](http://arxiv.org/abs/2405.02957v3) | ![Star](https://img.shields.io/github/stars/wisdom-pan/Agent_Hospital.svg?style=social&label=Star) <br> [GitHub](https://github.com/wisdom-pan/Agent_Hospital)  |


# Acknowledgement

This page is contributed and maintained by a collaborative effort.
