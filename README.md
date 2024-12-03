# TRACS-LLM_SURE
TRACS-LLM: LLM-based Traffic Accident Criminal Sentencing Prediction Focusing on Imprisonment, Probation, and Fines

Fault determination in traffic accidents require a careful analysis of various factors that could influence sentence severity and fairness in judgement. Traditional methods are subjective and often time-consuming, necessitating the need for an objective solution. Recently, large language models (LLMs) have garnered attention in the legal field and incorporating them into the legal process is beneficial. Moreover, there is lack of studies on sentence prediction both in the context of the Korean legal system and LLMs. We propose a traffic accident criminal sentencing prediction method based on large language models (TRACS-LLM), which analyzes legal texts related to traffic accident cases to predict three major legal outcomes, namely the length of imprisonment, whether probation is granted, and the amount of fines, through training from a large dataset of criminal traffic accident cases. A parallel structure that combines A lite bidirectional encoder representations from transformer (ALBERT) and bidirectional long short-term memory (Bi-LSTM) with grouped query attention (GQA) is leveraged to capture both the general language context and domain-specific legal information. In addition, we employ a multi-task learning approach, in which the model simultaneously predicts multiple legal outcomes by sharing information across tasks. We validated the feasibility and applicability of the proposed method through two ablation experiments, comparing the performance of the proposed model against baseline models and evaluating the impact of the proposed parallel combination with ALBERT. The results demonstrated that the proposed ALBERT+Bi-LSTM with GQA model achieved superior performance across all tasks, yielding the lowest RMSE for imprisonment and fine predictions and the highest F1-score for probation prediction. This study provides valuable insights for legal professionals by offering a data-driven, objective approach to sentencing, with potential applications beyond the Korean legal domain.
![TRACS-LLM](https://github.com/user-attachments/assets/8f39349f-5b36-4ad8-931a-6838d2025cb0)

"Full code coming soon"
