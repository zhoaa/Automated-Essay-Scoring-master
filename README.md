# Automated Essay Scoring
> A Deep Learning model that predicts the score of a given input essay. 

Dataset is from Kaggle ASAP competition which was provided by The Hewlett Foundation.

The **mysite** folder contains the Django app.

Look in here for GloVe files and embedding.pickle.
https://drive.google.com/drive/folders/1-3XuK_uylbd1llpBLGpI4xHVpB5r8Y7x?usp=sharing


## Requirements
```
pip install django
pip install tensorflow
pip install keras
pip install gensim
pip install pyspellchecker
pip install --upgrade language_tool_python
pip install nltk

```

## Installation 
- Clone the repo
- cd ./ into the **mysite** folder
- Get pickle + GloVe files from Google Drive (or create your own) and place it into the DeepLearningFiles folder in mysite\grader
- Run the following:
```
python manage.py migrate
python manage.py runserver
```

## References
1. [A Neural Approach to Automated Essay Scoring](http://aclweb.org/anthology/D/D16/D16-1193.pdf) </br>
2. [Automatic Text Scoring Using Neural Networks](https://arxiv.org/pdf/1606.04289.pdf)
