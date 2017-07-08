# Healthcare-Robotics

*LuminoTotem* is based on the idea of providing additional support to the Deaf and Hard of hearing people. The commonly existing support for these subset involve learning sign languages, having a stenographer to transcribe the conversations of subjects. We plan to add emotions to this technique to enhance the social context.

We plan to portray 4 major and easily distinguishable emotions viz. Happy, Sad, Angry and Neutral. After training and testing a few classifiers for accuracy, we used XGBoost Classifier. We pass real-time audio data and pass that to our classifier, which extracts an emotion and send this information wirelessly to our mobile totem.

#Results:

An accuracy of 81.68% was achieved using XGBoost classifer (better than the average of 75% accuracy in classifying emotions from real-time audio).
