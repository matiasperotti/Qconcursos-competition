The Adaptive Learning Challenge from Qconcursos

DataSet

For this challenge we have made available two data sets that, put together, concentrate qualitative information about the users, information about the questions and about the performance in each resolution. It should also be noted that the data was anonymized so that it is impossible to identify any person in the example.

The Challenge

Participants are requested to create a model to rank the answer to the 101st question, given a set of 100 answers to questions answered sequentially by 20,000 users.

The Dataset_Model database contains the answers to 100 questions answered sequentially by 20,000 users and should be used to train the model.

The subjects_question file contains additional information about the questions, mapping the questions to subjects. It's important to note that each question may contain more than one subjects.

The file Submit.csv is the file that contains the data about the 101st question for each user. Your model should score the "Acertou" (in english "got it right") column, containing "0" for wrong or "1" for correct.

You must submit a .csv file containing 20,000 rows and only one column containing the 0's and 1's that your model calculated.