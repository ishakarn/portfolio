## 🎓 Education  
**Ph.D. in Computer Science** (Incoming) 
University of Massachusetts Amherst  
(Expected May 2030)

**M.S. in Computer Science** (GPA: 3.8) 
University of Massachusetts Amherst  
(Expected May 2026)

**B.Tech. in Computer Science and Engineering** (GPA: 3.65) 
Vellore Institute of Technology, Chennai
(Expected May 2026)

## 🧠 About Me  
I’m an incoming PhD student in Computer Science at UMass Amherst working on interpretable and trustworthy machine learning, with a focus on graph learning and evaluation via controlled interventions/ablations. I also work on molecular property prediction with graph-based models. 

In my free time, I love to play video games and paint (need to do that more often though).

## 🔬 Research Interests  
- Trustworthy / Interpretable ML
- Graph Neural Networks (GNNs) and LLM-based representation learning
- Molecular graphs for bioinformatics / property prediction  

## 📌 Ongoing Work 
### Highlighting Modes of Information in Graph Learning Evaluation (September 2025 - Present)
- I am developing an evaluation framework that decomposes performance of GNNs on graphs into four modes of information: node features, edge features, graph features, and graph topology/structure, using controlled interventions to test what signal a model is actually using.
- Implemented controlled ablations (feature shuffling, label permutations, synthetic generators controlling structure vs feature informativeness).
- Unified 10-fold stratified CV harness with per-epoch logs, learning curves, and confidence intervals across Baseline GNN models (GCN/GAT/GraphSAGE/GIN) and structure agnostic baseline (MLP).
- Analysis spans over 6 datasets across domains (social + molecular benchmarks).

## 🧾 Publications and Manuscripts
### (Accepted at JCIM 2026) MycoPermeNet-v2: Improved Prediction of Mycomembrane Permeation via Feature Fusion and Noisy Student Self-Distillation.
Link: (Under Construction)

### (Preprint - 2025) The Impact of Data Characteristics on GNN Evaluation for Detecting Fake News
Link: [arXiv](https://arxiv.org/abs/2512.06638)

### (ICONAT 2023) Disseminating the Process of Hurricane Path Prediction using Multilayer Perceptron and Support Vector Machine upon Varied Kernel Functions
[DOI: 10.1109/ICONAT57137.2023.10080280](https://doi.org/10.1109/ICONAT57137.2023.10080280)

## 💼 Experience
### Teaching Assistant - COMPSCI 589 Machine Learning, UMass Amherst (Jan 2026 – Present)
- Grading and feedback for ML topics (supervised learning, optimization, evaluation metrics) with consistent rubrics and clear explanations.

### Research Assistant - Science for AI Governance (S4AIG), UMass Amherst (May 2025 - Present)
- Built an automated benchmark pipeline for causal reasoning in LLMs/LMMs, generating 10K+ in-context/counterfactual/interventional prompt variants and evaluating 7 models at scale.
- Implemented controlled interventions (polarity flips, variable/value swaps, distractor injections, consistency checks) and intervention-aware scoring over 50K+ model responses, reducing manual evaluation substantially.
- Developed analysis + visualization tooling (robustness profiles, deltas by intervention type, confusion matrices/error taxonomies) and a version-controlled, CI-backed pipeline for reproducible reporting.

## 🚀 Selected Projects
### Causal Reasoning Benchmarking for LLMs (S4AIG)
- Investigating CLADDER-style causal reasoning evaluations by applying small, targeted **interventions** to causal queries (e.g., polarity flips, variable/value swaps, distractor injections) to test whether model behavior is robust to changes that preserve causal structure.
- Built an end-to-end pipeline for intervention generation, automated scoring, and visualization, enabling large-scale comparison across multiple LLMs and intervention types.

### Evaluating the Role of Graph Structure in Fake News Detection
- Investigated whether Graph Neural Networks (GNNs) genuinely leverage structural information in benchmark fake news datasets.
- Replicated the UPFD framework and implemented GAT, GCN, and MLP models using PyTorch Geometric; performed controlled ablation to isolate structural vs. feature contributions.
- Designed and generated custom synthetic ego-graphs with controlled feature/structure separability to validate findings beyond real-world bias.
- Found small GNN gains on ego-centric graphs with highly informative node embeddings; ran feature/structure randomization + synthetic studies to show when structure truly helps.

### MycoPermeNet-v2 (SAGE Lab)
- Implemented Noisy Student self-distillation for Chemprop/DMPNN; built fusion pipeline combining DMPNN embeddings + RDKit descriptors with clean ablation switches.
- Owned harness: scaffold-balanced splits, reproducible seeds, checkpointing, sweep execution, calibration/error analysis.

## 📄 Resume / CV
[CV](https://drive.google.com/file/d/1pUdz-BBJjaXevOQebpbGb4wCXmY5IRIE/view?usp=drive_link)

## 🔗 Connect with Me  
- [Email](ikarn@umass.edu)
- [Website](https://ishakarn.github.io/portfolio)
- [LinkedIn](https://www.linkedin.com/in/isha-karn)  
- [GitHub](https://github.com/ishakarn)
