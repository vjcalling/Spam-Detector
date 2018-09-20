# Spam-Detector
python flask webapp which deals with youtube comments and classify them as spam or a valid comment

**Libraries used:**  
a. EDA: Numpy, Pandas  
b. ML: sklearn (CountVectorizer, train_test_split, MultinomialNB)  
c. persistance: Pickle  


**Code structuring:**  
This project follows cookie-cutter template.  

a. data: holds all data. 2 subfolders (raw and processed). raw folder contains the raw youtube comments csv, whereas processed folder contains the merged csv post processing.  
b. model: contains the NB model.  
c. notebook: contains the jupyter notebook having entire logic of how data is processed and model is generated/persisted.  
d. static: contains static content like css  
e. templates: contains the html pages used in application.  
f. Procfile, requirements.txt, runtime.txt: these files are used to deploy the application on heroku  
g. app.py (starting point)  


# Application Screenshots  

**Main Application**  
![Alt text](./screenshots/main_app.png?raw=true "Home Page")  

**Entering a spam comment**  
![Alt text](./screenshots/spam_comment.png?raw=true)  


**Classifying the comment as spam**  
![Alt text](./screenshots/classfied_as_spam.png?raw=true)  


**Entering a valid comment**  
![Alt text](./screenshots/valid_comment.png?raw=true)  


**Classifying the comment as not a spam**  
![Alt text](./screenshots/not_a_spam.png?raw=true)  
