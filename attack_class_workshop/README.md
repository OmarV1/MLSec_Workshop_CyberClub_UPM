# Intrusion_detection_ANN
Intrusion detection system using Artificial Neural Network

The dataset used is Canadian Institute for cyber security intrusion detection system (CICIDS-2017) which includes 86 features with 6 types of attack and those are ('BENIGN', 'DoS slowloris', 'DoS Slowhttptest', 'DoS Hulk', 'DoS GoldenEye', 'Heartbleed'). The attacks are mapped to label BENIGN -> 1 and all other as 0 so as to make a binary classification between normal and dos attack. ANN is applied for the detection of the attack and different feature selection algorithm is used to clean the data having correlated features, constant and quasi constant features, duplicate features and misiing values as well as -inf and inf values. Further different performance metric is used for prediction and analysis.
