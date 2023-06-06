# Emotion Recognition in Arabic Tweets
> Team 8:
> - Maryam ElOraby
> - Rawan Reda
> - Salma El-Shafey




# Breif overview
this project compares the performance of multiple BERT-based models for the task of Emotion recognition in Arabic Tweets.
Our approach compares 7 BERT models:
1. AraBERT-base
2. AraBERT-Twitter-base 
3. MARBERT
4. CAMELBERT-DA
5. CAMELBERT-MSA
6. CAMELBERT-MSA-16th
7. mBERT

All the experiments are avaialble in [Experiments Directory](./Experiments). The model that achieved the highest accuracy is MARBERT. Its notebook is available in [MARBERT.ipynb](/MARBERT.ipynb) with some added inference examples in the end.

If you wish to experiment with other models or redo an experiment, you can simply open the Jupyter notebook in Google Colab or Kaggle, connect to a GPU, and paste the desired model path from Hugging Face into the ```model_path``` parameter. Run all the cells if you don't wish to adjust any more parameters and dataset will be automatically imported, processed, and the model will be fine-tuned on the dataset and evaluated.





