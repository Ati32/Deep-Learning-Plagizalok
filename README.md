# Deep-Learning-Plagizalok

**Team:** Plagizálók<br>
**Members:** Ragács Attila, Urbanics András, Pfeifer Dániel

**Goal:** Solving the <a href="https://www.kaggle.com/c/spooky-author-identification">Spooky Author Identification excercise on Kaggle</a>, identifying the author of English sentences and deciding between Edgar Allan Poe, Mary Shelley, or HP Lovecraft.

**Methods:** Simple statistical methods; Neural Networks: Dense, Convolutional, Hyperparameter-optimization.

**Files:**
- Anything that contains the word "**milestone**" is a previous state of our work that we have already submitted (*plagizalok_milestone1.ipynb, plagizalok_milestone1_plus_baseline.ipynb, plagizalok_milestone2.ipynb*).
- **train.csv**, **test.csv**: Data files.
- **author_identification_dense_model.h5**, **author_identification_multiconv_model.h5**, **hyperparam1_best_model.h5**, **hyperparam2_best_model.h5**: Saved Keras models.
- **Author_Identification_Evaluation.ipynb:** *RUNNABLE* Notebook to show our work on **ANY** English sentence. It encodes the sentence and predicts who could have written it. It uses **train.csv** and **author_identification_multiconv_model.h5**.
- **dense_neural_network.ipynb**: Run this for the reproduction of the Dense Neural Network, it uses the file **train.csv** and **author_identification_dense_model.h5** in the end. Also the FastText wordembeddings can be downloaded with the code included in the notebook (it is commented out originally).
- **Author_Identification_Dense_and_CNN_Networks.ipynb**: This file isn't necesseraly runnable, because fitting the Neural Networks took ~10 hours each, however, it includes comments and shows how the Dense and Convolutional Networks have been constructed.
- **Simple_Word2vec_model.ipynb**: This solution used only our data. With this method we have automatically detected the bigram from a stream of sentences without Neural Networks
- In the **documentation** folder we have the .pdf file with the actual documentation of the project and in the .zip file the source files for this pdf (pictures, .tex file, .bib file with the references)
