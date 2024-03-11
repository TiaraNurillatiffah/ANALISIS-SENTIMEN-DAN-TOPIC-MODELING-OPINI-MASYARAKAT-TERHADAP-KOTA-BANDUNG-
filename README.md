My undergraduate thesis research project, conducted on Google Colab due to the constrained system specifications of my laptop/PC, focuses on employing Machine Learning with TensorFlow as the framework to classify opinions from residents of Bandung city and model topics using Bidirectional Gated Recurrent Unit and Latent Dirichlet Allocation algorithms.

Link to Colab : https://colab.research.google.com/drive/15CNZ6Vc-Eu8BdKJJ-auZFoPs6GFxT_rm?usp=sharing
(Or you can open the "**Syntax Code**" file)

For the opinion classification model dataset, comments from the public were utilized, sourced from social media spanning from January 2022 to July 2023. The dataset file is named "**data_label_0_1**"
For the topic modeling dataset, comments from the public were sourced from social media from October 2023 to November 2023. The dataset file is named "**data_baru_klasifikasi**"

Both text classification model training and topic modeling involve employing Hyperparameter tuning techniques to obtain optimal parameters. The Adam optimizer is used for text classification models. Additionally, to minimize overfitting, dropout techniques are utilized along with callbacks, including early stopping and model checkpoint, in the text classification model.

Save the model to Google Drive, then save the model in (*.h5) format to Google Drive (only save the best model to Google Drive). The best model is named as the file "**best_model_6**"
