# Enhancing Recommendation Systems: A Comparative Analysis of Multimodal Feature Representations 

- 📢 Published In: This work was published as a book chapter in Springer’s Proceedings of International Conference on Recent Trends in Computing ICRTC, 2024 https://link.springer.com/chapter/10.1007/978-981-97-8946-7_23
- Explored multimodal recommendation systems by integrating text, image, and metadata features through deep 
learning-based fusion techniques, and conducted a comparative analysis of modality combinations to address 
the cold-start problem. 

- Co-authored as part of a collaborative research project during undergrad. Gained hands-on experience in 
academic writing, model evaluation, and presenting research findings at a national-level conference.

📊 Table 1: Combination of 2 Modalities (with Meta)
| **Modality** | **RMSE** | **Precision (%)** | **Recall (%)** |
| ------------ | -------- | ----------------- | -------------- |
| Meta + Text  | 1.1835   | 65                | 61             |
| Meta + Audio | 1.1743   | 66                | 62             |
| Meta + Video | 1.2010   | 64                | 58             |


📊 Table 2: Combination of 2 Modalities (without Meta)
| **Modality**  | **RMSE** | **Precision (%)** | **Recall (%)** |
| ------------- | -------- | ----------------- | -------------- |
| Text + Audio  | 1.1486   | 68                | 59             |
| Text + Video  | 1.1539   | 71                | 57             |
| Audio + Video | 1.1982   | 67                | 58             |


📊 Table 3: Combination of 3 Modalities
| **Modality**                      | **RMSE** | **Precision (%)** | **Recall (%)** |
| --------------------------------- | -------- | ----------------- | -------------- |
| Meta + Video + Audio              | 1.1211   | 63                | 62             |
| Meta + Text + Audio               | 1.1593   | 65                | 63             |
| Video + Audio + Text              | 1.1535   | 67                | 62             |
| Meta + Text + Video               | 1.1296   | 67                | 66             |
| All (Meta + Text + Video + Audio) | 1.1635   | 66                | 63             |


🎯 Goal of the Research
Aimed to improve the performance of recommendation systems by using multimodal data — meaning data from multiple types of content sources:
- Meta
- Text
- Audio
- Video

The goal was to:
- See how these different modalities contribute to recommendation accuracy.
- Find the best-performing combination of modalities for predicting user preferences.
- Incorporate self-supervised learning techniques to make better use of unlabelled data.

Evaluation:
- Ran multiple experiments using different modality combinations.
- Used metrics: RMSE, Precision, Recall, F1-Score

📌 Best Overall Performance:
- Meta + Text + Video gave the most balanced and best results across all metrics.

🧠 Final Conclusion
- Multimodal data improves recommendation performance.
- It is evident that, when considering the primary metric of 
  RMSE, a combination of all currently available 
  representations yields the best results. With no discernible 
  difference between the two, we can see that Meta + Text is 
  the next best combination in terms of performance. Therefore, 
  it is possible to draw the conclusion that the architecture and 
  methodology used in this study are effective for the 
  information that is most directly related, such as the movie's 
  description and meta data about its genre and directors. 
  Although audio and video are obviously significant signals, 
  the way they are currently used in this work is not ideal and 
  needs further research.  
