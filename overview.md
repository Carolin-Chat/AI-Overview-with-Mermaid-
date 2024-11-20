# AI Technologies Overview

This diagram shows the relationships between various AI technologies.

```mermaid
[graph TB
    AI[Artificial Intelligence<br>1950s+]
    ES[Expert Systems<br>1960s+]
    ML[Machine Learning<br>1950s+]
    DL[Deep Learning<br>2000s+]
    
    %% Traditional ML branches
    SL[Supervised Learning<br>1950s+]
    UL[Unsupervised Learning<br>1950s+]
    RL[Reinforcement Learning<br>1980s+]
    
    %% Deep Learning architectures
    CNN[Convolutional Neural Networks<br>1980s+]
    RNN[Recurrent Neural Networks<br>1980s+]
    LSTM[Long Short-Term Memory<br>1997+]
    Trans[Transformers<br>2017+]
    
    %% NLP and related
    NLP[Natural Language Processing<br>1950s+]
    LLM[Large Language Models<br>2018+]
    FM[Foundation Models<br>2021+]
    GPT[GPT Models<br>2018+]
    BERT[BERT<br>2018+]
    T5[T5<br>2019+]
    
    %% Modern applications
    RAG[Retrieval Augmented Generation<br>2020+]
    GenAI[Generative AI<br>2020+]
    CV[Computer Vision<br>1960s+]
    ASR[Speech Recognition<br>1960s+]
    TTS[Text-to-Speech<br>1960s+]
    MLOps[MLOps<br>2015+]
    XAI[Explainable AI<br>2010+]
    
    %% Newer concepts
    AGI[Artificial General Intelligence<br>Concept]
    MoE[Mixture of Experts<br>2022+]
    FewShot[Few-Shot Learning<br>2015+]
    ZeroShot[Zero-Shot Learning<br>2015+]

    %% Define relationships
    AI --> ES
    AI --> ML
    
    ML --> SL
    ML --> UL
    ML --> RL
    ML --> DL
    ML --> NLP
    ML --> CV
    ML --> ASR
    ML --> TTS
    
    DL --> CNN
    DL --> RNN
    RNN --> LSTM
    DL --> Trans
    
    Trans --> LLM
    Trans --> BERT
    Trans --> T5
    
    LLM --> FM
    LLM --> GPT
    LLM --> MoE
    
    FM --> GenAI
    GPT --> GenAI
    RAG --> GenAI
    
    ML --> FewShot
    ML --> ZeroShot
    ML --> XAI
    ML --> MLOps

    style AI fill:#e3f2fd
    style ML fill:#e1f5fe
    style DL fill:#b3e5fc
    style SL fill:#b3e5fc
    style UL fill:#b3e5fc
    style RL fill:#b3e5fc
    style CNN fill:#81d4fa
    style RNN fill:#81d4fa
    style LSTM fill:#81d4fa
    style Trans fill:#4fc3f7
    style NLP fill:#b3e5fc
    style LLM fill:#4fc3f7
    style FM fill:#29b6f6
    style GPT fill:#03a9f4
    style BERT fill:#03a9f4
    style T5 fill:#03a9f4
    style RAG fill:#039be5
    style GenAI fill:#0288d1
    style CV fill:#b3e5fc
    style ASR fill:#b3e5fc
    style TTS fill:#b3e5fc
    style MLOps fill:#039be5
    style XAI fill:#039be5
    style AGI fill:#e1f5fe
    style MoE fill:#0288d1
    style ES fill:#e1f5fe
    style FewShot fill:#039be5
    style ZeroShot fill:#039be5]
