# Enhancing Recommendation Systems: A Comparative Analysis of Multimodal Feature Representations 

- Explored multimodal recommendation systems by integrating text, image, and metadata features through deep 
learning-based fusion techniques, and conducted a comparative analysis of modality combinations to address 
the cold-start problem. 

- Co-authored as part of a collaborative research project during undergrad. Gained hands-on experience in 
academic writing, model evaluation, and presenting research findings at a national-level conference.

📊 Table 1: Combination of 2 Modalities (with Meta)
Modality	RMSE	Precision (%)	Recall (%)
Meta + Text	1.1835	65	61
Meta + Audio	1.1743	66	62
Meta + Video	1.2010	64	58

📊 Table 2: Combination of 2 Modalities (without Meta)
Modality	RMSE	Precision (%)	Recall (%)
Text + Audio	1.1486	68	59
Text + Video	1.1539	71	57
Audio + Video	1.1982	67	58

📊 Table 3: Combination of 3 Modalities
Modality	RMSE	Precision (%)	Recall (%)
Meta + Video + Audio	1.1211	63	62
Meta + Text + Audio	1.1593	65	63
Video + Audio + Text	1.1535	67	62
Meta + Text + Video	1.1296	67	66
All (Meta + Text + Video + Audio)	1.1635	66	63

