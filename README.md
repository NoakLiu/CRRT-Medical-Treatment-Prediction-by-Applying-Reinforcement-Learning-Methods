# CRRT-Medical-Treatment-Prediction-by-Applying-Reinforcement-Learning-Methods
This is a research project I worked as an internship in by Tsinghua University, cooperated withPeking University People's Hospital.

The contribution can be summarized as follows:

1. I extracted data by using PostgreSQL from MIMIC IV.

2. I realized the data interpolation by using the SAITS model.

3. I build two prediction model for CRRT treatment:

   3.1 LSTM+Conv model

   3.2 CTRL

   ​	3.2.1 UCB

   ​	3.2.2 Regression Model 

   ​	3.2.2 Delayed Reward 

   ​	3.2.3 Bad Action Reward Decreasing

   ​	3.2.4 Vital Sign Group Reward
