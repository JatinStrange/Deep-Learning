<h1>Abstractive-Text-Summarization</h1>
The objective of this project was to build an Abstractive Text Summarizer using Sequence-to-Sequence Recurrent Neural Networks. For this project Amazon Fine Food Reviews dataset from Kaggle was used which has 500,000 reviews from 1999-2012. In the modern Internet age, textual data is ever increasing. We need to condense this data while preserving the information and meaning. We need to summarize textual data for that.

Text summarization is the process of automatically generating natural language summaries from an input document while retaining the important points. It would help in easy and fast retrieval of information. Abstractive summarization systems generate new phrases, possibly rephrasing or using words that were not in the original text.

During implementation a 3 Layer Stacked LSTM Encoder-Decoder model with Global Attention Mechanism was used. With this model I was able to get an accuracy of 65.89% on training set (constituting 80% of the dataset).

Dataset: "https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews?resource=download"

Libraries:
<ul>
<li>Pandas</li>
<li>Re</li>
<li>gensim</li>
<li>Tensorflow</li>
</ul>
