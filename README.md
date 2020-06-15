# DCASE 2020 Challenge: Task 5 - JHKim

1. Must be located the path(data/audio) the train and validate data

2. Check the SONYC_UST_PATH in "train_start.sh"

3. Create folder "embeddings_ef_3ch_5s_train"

4. run ./train_start.sh


Info

train_start.sh --> Project Sequence shell

src/feature_extraction.py --> Prepare the feature for train

src/classify.py --> Train, create Model and predict validate set

src/evaluate_predictions.py --> Evaluate the predicted validate set

proposed_evaluation_output.json --> Best result of task5 in our model
