## 🎓 Education  
**M.S. in Computer Science** (GPA: 3.8) 
University of Massachusetts Amherst  
(Expected May 2026)

## 🧠 About Me  
I'm a graduate student passionate about using machine learning to solve real-world problems in science and society. My recent work explores how structural and feature-based signals affect GNN performance in fake news detection. I'm also beginning work on molecular property prediction using graph-based models in bioinformatics.

## 🔬 Research Interests  
- Machine Learning & AI Interpretability  
- Graph Neural Networks (GNNs)  
- Bioinformatics & Molecular Graph Analysis  
- Social Network Analysis  
- Misinformation and Fake News Detection

## 📌 Ongoing Work 
- Analyzing the role of graph structure vs. node features in fake news detection (AAAI submission in progress)  
- Exploring GNN-based molecular modeling for bioinformatics research  
- Learning about AI governance and ethical AI applications

## Past Projects
### Evaluating the Role of Graph Structure in Fake News Detection (2024)
- Investigated whether Graph Neural Networks (GNNs) genuinely leverage structural information in benchmark fake news datasets.
- Replicated the UPFD framework and implemented GAT, GCN, and MLP models using PyTorch Geometric; performed controlled ablation to isolate structural vs. feature contributions.
- Designed and generated custom synthetic ego-graphs with controlled feature/structure separability to validate findings beyond real-world bias.
- Found that a 3-layer MLP rivaled GCN performance (94.81% vs. 95.48% on GossipCop), indicating that user embeddings, not graph topology, primarily drive prediction accuracy when these user embeddings are linearly separable and hence highly informative.
- Technologies used: PyTorch Geometric, Pytorch, Network X, Visualization libraries (Seaborn, Matplotlib)

### Sentiment Analysis on Gendered Patterns in STEM (2024)
- Conducted a large-scale analysis of gender bias in audience engagement across STEM YouTube channels.
- Developed a scraping pipeline using the YouTube Data API to collect thousands of comments, annotated with gender markers and sentiment scores using spaCy, VADER, and rule-based filters.
- Analyzed differences in comment tone, content, and intensity based on the perceived gender of video hosts.
- Found that women in authoritative STEM roles experienced higher rates of personal attacks and sentiment volatility, while male-presenting hosts triggered more technical discussion, revealing subtle but consistent gendered engagement patterns.
- Technologies used: YouTube Data API, NumPy, TensorFlow, Keras, spaCy, NLTX, VADER, Visualization libraries (Seaborn, Matplotlib)

### EEG Recurrence Plot Analysis for Attention Detection (2023)
- Designed a deep learning pipeline to detect user attention states from EEG signals using recurrence-based spatial encoding.
- Processed over 300,000 EEG signal samples and transformed them into recurrence plots to capture non-linear temporal dependencies.
- Trained a ConvMixer model in TensorFlow, leveraging spatial convolutions on the 2D plots to classify attentional states.
- Achieved 99.62% accuracy, demonstrating the effectiveness of combining recurrence plot representations with convolutional token mixing for neurocognitive modeling.
- Technologies used: TensorFlow, Keras, NumPy, Scipy, Visualization libraries (Seaborn, Matplotlib)

### Gender Bias in STEM Twitter Discourse (2023)
- Explored online perceptions of women in STEM by conducting a large-scale sentiment analysis of over 1 million tweets.
-Scraped X to collect domain-relevant data and fine-tuned a RoBERTa transformer model for high-fidelity sentiment classification.
- Performed linguistic and thematic analysis to uncover bias patterns, hate speech, and differing framing in tweets referencing women vs. men in STEM.
- Identified a recurring presence of personal attacks, gender stereotyping, and underrepresentation, providing empirical insights into the inclusivity challenges faced by women in technical fields.
- Technologies used: TensorFlow, spaCy, NLTK, snscrape, HuggingFace Transformer API, Visualization libraries (Seaborn, Matplotlib)

### Hurricane Path Prediction using MLP and SVM (2023)
- Published findings in IEEE ICONAT 2023, highlighting practical implications for disaster modeling and the design of low-cost trajectory forecasting systems. [DOI: 10.1109/ICONAT57137.2023.10080280](https://doi.org/10.1109/ICONAT57137.2023.10080280)
- Investigated the effectiveness of kernel-based and neural models for forecasting hurricane trajectories using historical meteorological data.
- Engineered spatiotemporal features from NOAA datasets and implemented both Support Vector Machines and Multi-Layer Perceptrons for path prediction.
- Conducted a comprehensive performance comparison and found that kernel selection significantly impacted predictive accuracy.
- Technologies used: R, ggplot

## 📄 Resume / CV

## 🔗 Connect with Me  
- [LinkedIn](https://www.linkedin.com/in/isha-karn-8a9b6a261/)  
- [GitHub](https://github.com/ishakarn)  
