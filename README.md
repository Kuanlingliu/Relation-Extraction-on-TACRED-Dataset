# Text-Mining-crousework

Link for Google Drive:
Our submission was large, we couldn’t include all of it on blackboard.
Please access our files through this link and download Submission.zip
https://drive.google.com/drive/folders/1_mp0ha7zhWLf9OI7PipAGZuJgeHifToT

•   Folder Structure:
|— user_interface.ipynb    # this notebook serves as the user interface
|— choose_model_test.py    # this script loads the pre-trained models for prediction
|— data                # this folder contains the dataset
          |— train.json
          |— test.json
          |— dev.json
|— models        #this folder has the scripts to initialize and load the pre trained model
          |— bert_relation_only.py                       # this BERT script is for BERT relation only model
          |— bert.py                                          # this BERT script is for BERT all relations model
          |— lstm_relation_only.py                       # this LSTM script is for LSTM relation only model
          |— lstm.py                                          # this LSTM script is for LSTM all relations model
          |— svm_predict.py                              # this SVM script is for SVM all relations model
          |— svm_predict.py                              # this SVM script is for SVM all relations model

|— models_paremeters                                                     #this folder contains the weights and parameters for the  pre-trained models
                  |— bertmodel.pt                                            #this is our pre-trained BERT weights for all relations
                  |— bertmodelnorelation.pt                                #this is our pre-trained BERT weights for relation only classes
                  |— lstm_model_no_releation_filtered.pt            #this is our pre-trained LSTM weights for relation classes
                  |— lstm_model.pt                                             #this is pre-trained LSTM weights for all relations
                  |— svm pickle files                                           # these pickle files are for our SVM pre-trained model
                  |— gpt_model_full.pth and gpt_model_relation_only               # pre-trained GPT model
		
|—  notebooks                #this folder has the full notebooks of our implementations for training the models
                  |— SVM.ipynb
                  |— BERT.ipynb
                  |— LSTM.py
                  |— LSTM._relation_only.py
                  |— RE_GPT_(Relation_Only).ipynb
                  |— RE_GPT.ipynb
		


Our “user_interface.ipynb” script serves as the central interface for integrating and linking our models. It imports other models and their scripts, which merges the branches of our different models.

•   How to run:
1. Download Submission zip file
2. Open the Submission folder in an IDE
3. Install the following packages:
⁃    Following are the packages to install before running user_interface.ipynb:
              	- nltk
                  - torch
                  - transformers
                  - imblearn
                  - scipy
                  - sklearn
4. Run “user_interface.ipynb” in the IDE:
  •    Example:
 











Result in the notebook




•   Disclaimer:
- If you encounter this error while running the user_interface notebook, run choose_model_test.py instead to predict the relation instead:

The output when running choose_model_test.py will be like this:



- Since both Bert and GPT both follows transformer approach, we decided to implement both of them. However, we decided to submit Bert as our official approach of using deep-learning with transformer for this assignment.

•   Notebooks to mark:
We have included all of our implementations, However, please mark:
(1)     BERT.ipynb
(2)     LSTM.ipynb



If you experience any issues please contact us!

Student IDs:
Bader Shalata - 14121917
Dimitrii Naumov - 11480525
Minh Duc Pham - 14127802
Kuan-Ling Liu - 14141925


•   Use of Generative AI Tools:
We used ChatGPT for exploration of coding syntax and debugging

 
