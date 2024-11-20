```mermaid
graph TB
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

    %% Styles with black text
    classDef default font-family:arial,font-weight:normal,font-size:12px
    classDef node fill:#e3f2fd,color:black
    
    %% Apply styles to all nodes
    class AI,ML,DL,SL,UL,RL,CNN,RNN,LSTM,Trans,NLP,LLM,FM,GPT,BERT,T5,RAG,GenAI,CV,ASR,TTS,MLOps,XAI,AGI,MoE,ES,FewShot,ZeroShot node
