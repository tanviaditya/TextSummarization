Text Summariztion is used to summarize huge text into small summary for easy understanding. 
It wraps up a text to a short length and condenses a long article to main points.

A pre-trained model facebook/bart-large-cnn is used here to summarize the text. BART model pre-trained on English language, and fine-tuned on CNN Daily Mail.
Further this model is used on the news article dataset which includes long articles and they are summarized using the mentioned model.

Results are as follows:
![summarized_text](https://user-images.githubusercontent.com/47853977/166142580-a2f0e03b-ed93-4750-8a7e-13d266b4c0ed.png)

Link to Dataset: https://www.kaggle.com/datasets/ruchi798/source-based-news-classification

Link to colab file: https://colab.research.google.com/drive/1HHefxOqwo0oh2roE_Y0KijSFrZgfhTdf?usp=sharing

Model used: https://huggingface.co/facebook/bart-large-cnn

