# Data_inference

**conf_mat.csv**
confusion matrix - confusion between the data labels (hdtb test data file and predicted file)
each cell is the number of times the row header is confused as the column header.

**result_file.csv**
prediction file obtained using diaparser

**final_file1.csv**
test data file with only required columns along with added columns - DOC_NO, SENT_ID, ID (word ID within sentence)
**Note** - In the code, this file is added with columns having corresponding predictions (head and dependency relation) from the predicted file.

**label_meanings.csv** 
Contains kaaraka labels used in the dataset and their meanings in Sanskrit and English

**final_file_train.tsv**
https://drive.google.com/file/d/1uXL47zPQO3TF616m-ZmcKQf7j3TIeHoi/view?usp=sharing

file used to display some ground-truth examples for labels.

**test_sent.csv**
mapping of sentence IDs with the complete sentences.
