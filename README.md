# sonar_mines_rock
https://archive.ics.uci.edu/ml/datasets/Connectionist+Bench+(Sonar,+Mines+vs.+Rocks)


 Problem Definition (Sonar return data) - The task is to train a network to discriminate between sonar signals bounced off a 
metal cylinder and those bounced off a roughly cylindrical rock.
 Step 1: Loaded the Dataset.
 Step 2: Analyzed the Data - Observation: same scale but different distributions of data, meaning varying mean
 Step 3: Evaluated the Algorithms - Observatiob: KNN was the better model out the 6 models, with accuracy of 0.808088
 Step 4: Evaluated Algorithms considering Standardization. Observation - KNN and SVM had the better outcome with accuracy of 0.825735 and 
0.836397 respectively.
 Step 5: Algorithm Tuning ( K=1 for KNN was good with accuracy of 0.849398, while SVM with an RBF kernel and C=1.5 was
best with accuracy of 0.867470.
 Step 6: Ensemble Methods (Bagging and Boosting, not quite as good as SVM).
 Finalize Model (use all training data and confirm using validation dataset).On the validation, we got an accuracy of 0.857142 using the SVM
model. 
