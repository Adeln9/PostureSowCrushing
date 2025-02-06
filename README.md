####### this is a code and dataset to create piglet crushing warning

the dataset folder include posture image with labeled in YOLO format, and thresholding_dataset230724.csv for PC analysis and crushing warning.

seven jupyter notebook consist of:
1. model_training: It is used to train sow posture detection model
2. posture_detection: It is a batch inference of video to gather and store posture each individual sow
3. PC_Dataset: it is used to create postueral change frequency dataset which is a dataset for decision tree, SVM, and threshold and voting
4. ID3_SVM_cbn: It is piglet crushing warning of decision tree and SVM. they are trained and evaluated from crushing day with before vs normal day
5. ID3_SVM_cn: It is piglet crushing warning of decision tree and SVM. they are trained and evaluated from crushing day vs normal day
6. voting_cbc_nc: It is piglet crushing warning of threshold and voting method. It used  crushing day with before vs normal day to evaluated
7. voting_cn_nc: It is piglet crushing warning of threshold and voting method. It used  crushing day vs normal day to evaluated
