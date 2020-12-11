# Deep-Learning-Plagizalok

**Team:** Plagizálók<br>
**Members:** Ragács Attila, Urbanics András, Pfeifer Dániel

**Goal:** Solving the <a href="https://www.kaggle.com/c/spooky-author-identification">Spooky Author Identification excercise on Kaggle</a>, identifying the author of English sentences and deciding between Edgar Allan Poe, Mary Shelley, or HP Lovecraft.

**Methods:** Simple statistical methods; Neural Networks: Dense, Convolutional, Hyperparameter-optimization.

**Files:**
- Anything that contains the word "**milestone**" is a previous state of our work that we have already submitted (*plagizalok_milestone1.ipynb, plagizalok_milestone1_plus_baseline.ipynb, plagizalok_milestone2.ipynb*).
- **train.csv**, **test.csv**: Data files.
- **author_identification_dense_model.h5**, **author_identification_multiconv_model.h5**: Saved Keras models.
- **Author_Identification_Evaluation.ipynb:** *RUNNABLE* Notebook to show our work on **ANY** English sentence. It encodes the sentence and predicts who could have written it. It uses **train.csv** and **author_identification_multiconv_model.h5**.
- dense_neural_network.ipynb: Run this for the reproduction of the Dense Neural Network, it uses the file **train.csv** and **author_identification_dense_model.h5** in the end. Also the FastText wordembeddings can be downloaded with the code included in the notebook (it is commented out originally). 

For the reproduction of the Dense Neural Network run the dense_neural_network.ipynb notebook, it uses the file train.csv and author_identification_dense_model.h5 in the end. Also the FastText wordembeddings can be downloaded with the code included in the notebook (it is commented out originally). 
