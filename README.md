# ML_Project_PanicDisorder

### Project Overview
Contains my first project, that demonstrate how the Panic Disorder do based on data. This project used a several machine learning to compare each effectiveness.

### Problem and Data Overview
Panic attacks are feelings of intense fear and anxiety. Anxiety is a feeling of discomfort, such as worry or fear, that can be mild or severe.
A total of 120,000 rows of data were obtained which contained the daily reports of respondents with various backgrounds back against a condition that leads to "Panic Disorder". For the hope of the output is how a reader or society sees a condition with broad background
I used dataset from https://www.kaggle.com/datasets/muhammadshahidazeem/panic-disorder-detection-dataset

### Data PreProcessing
I do a duplicated data checking, data engineering (One Hot Encoding for value in columns that can be ranked, and Label encoding for value that can't be ranked).

### Modelling and Recommendation
From Baseline modelling, the highest Recall is used Gradient Boosting (Recall score is 1.00). Because the target is Imbalanced, so need to check with Undersampling Data. The result is best model is Gradient Boosting with Recall Score is 1.00, f1 Score is 0.969, and Accuracy is 0.997.
From best model, got most influential variables in panic disorder are Lifestyle, Symptom, Severity, Current Stressor, Impact On Life of the respondent's life, Family History, Social Support, and Coping Mechanisms.

### Society Insight
Panic attack is a sudden onset of intense fear and triggers a severe physical reaction when perceived danger. When a panic attack occurs, it can result in losing control, or even having a heart attack. For some people, panic disorder can lead to agoraphobia (phobia of crowded environments).
Based on the best model chosen, it is hoped that it can more quickly detect a person or patient who is suspected of having Panic Disorder. Because the faster the first treatment of a patient can increase the percentage of recovery from that patient.

Several factors become the main cause of panic disorder, and the way to solve it requires things that are around us

### Files Guidance
1. Do You Get Panic Now (Information).txt : contain the details meaning each columns
2. Panic Disorder Presentation.pdf : contain the presentation file for this project
3. Panic Disorder Script.ipynb : Contain the data work process of Panic Disorder in Python Programming Language
4. `panic_disorder_dataset_testing.csv` and `panic_disorder_dataset_training.csv` : contain the dataset of Panic Disorder.

### NOTE
1. In files `Panic Disorder Script.ipynb` if you want run it and import the csv dataset file on desktop, you can erase or skip run the code with the heading `Import File Using PyDrive`. If you run on Google Colab, run the code sequentially.
2. Get all of files in one folder (either use desktop or google colab).
3. If you run using Google Colab, on code with the heading `Import File Using PyDrive`, row with command `drive.CreateFile` fill the `id:` with the ID from share link the .csv files. For example, after you get share link on one .csv file, open it into new tab, and you get web address line like "https://drive.google.com/file/d/1gBIB1n1l_EV0mmV0DdYRdBWj_cPYP/view". The .csv ID is "1gBIB1n1l_EV0mmV0DdYRdBWj_cPYP"



I think that's what i can explain, if you have any criticism and suggestions, don't hesitate to contact me anytime
Thankyou



#Project #DataScientist #DataAnalyst #MachineLearning #Panic #Disorder #Analysis #Learning



Burhan Rafid Ekatama
b.rafidekatama@gmail.com
https://www.linkedin.com/in/burhanrafidekatama/
