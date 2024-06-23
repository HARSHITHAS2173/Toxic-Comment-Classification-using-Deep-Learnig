Comment Toxicity Model using Deep Learning

The goal of this project is to develop a deep learning model that can automatically detect and classify toxic comments in online comments. Toxic comments include those that are disrespectful,inflammatory,or offensive in nature. By identifying and flagging these comments, online platforms can improve the quality of discussions and create safer environments for users. We also find the toxicity score and classes to which a comment belongs which helps us in identifying how provocative a comment is.

Running the Code

1. Environment Setup:
	Make sure you have Python installed on your system. You can download it from Python's official website.
2. Dependencies Installation:
	Install the required Python packages using pip. You can install them by running:
	pip install numpy pandas tensorflow keras
3. Dataset:
	The dataset used by us is the “jigsaw-toxic-comment-classification-challenge” from kaggle.It has the 8 features namely id, comment_text, toxic, severe_toxic, obscene, threat, insult, identity_hate and 159571 rows.
4. Code Execution:
	After setting up the environment and installing dependencies, you can run the code. 
	Make sure to execute it in a Python environment where the required packages are installed.
	You can execute the code in a Python script or a Jupyter Notebook.

Pre-trained Word Embeddings

The code utilizes pre-trained word embeddings to represent words as dense vectors in the model. Specifically, it uses the glove.840B.300d.txt file, which contains GloVe embeddings trained on the Common Crawl corpus with 840 billion tokens and 300-dimensional vectors.

Download GloVe Embeddings
1. Download GloVe Embeddings:
	You can obtain the GloVe embeddings from the GloVe website. The glove.840B.300d.txt file corresponds to embeddings trained on a large corpus and includes 300-dimensional vectors for each word.
2. Place the Embedding File:
	After downloading the glove.840B.300d.txt file, place it in the appropriate directory where your code expects to find it. You may need to update the file path in the code if it's located in a different directory.

Project Credits
This project was developed by:
M P Deepti - PES2UG21CS259
Marada Likitha - PES2UG21CS282
Nikitha V - PES2UG21CS338
Harshitha S - PES2UG21CS912