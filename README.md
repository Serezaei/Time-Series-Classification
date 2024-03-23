# Time-Series-Classification
Sensor Resluts Classification

In this project, I'll classify 60-second sequences of sensor data, indicating whether a subject was in either of two activity states for the duration of the sequence.


train.csv - the training set, comprising ~26,000 60-second recordings of thirteen biological sensors for almost one thousand experimental participants

sequence - a unique id for each sequence

subject - a unique id for the subject in the experiment

step - time step of the recording, in one second intervals

sensor_00 - sensor_12 - the value for each of the thirteen sensors at that time step

train_labels.csv - the class label for each sequence.

sequence - the unique id for each sequence.

state - the state associated to each sequence. This is the target which I predict.

I used BiDirectional LSTM for this problem and I got 95% train accuracy and 85% tesst accuracy which is shows an accurate model.
