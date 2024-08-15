# Text Generator
----------------
## Streamlit Application Link:
[Text Generator](https://skynet-text-generator-ml.streamlit.app/)

## Model used
This text generator predicts the next character based on the last k characters (this is the block size). This is done by using a vanilla neural network. The architecture (ie; the embedding size) and the value of k can be modified in the app.

This model was trained on the English Corpus: Guilliver's travels.

## Interesting Observations
This model involves a vanilla nueral network, with only 2 hidden layers. The training dataset used is also around 600 kB. Yet, this model has learnt various semantics of English language. This include the use of punctuations, a capital letter after every full stop, capital 'I' when present individually, small otherwise and use of quotation marks.  Even the words and phrases generated are very close to valid English text.

Run the model and  change the parameters to observe these results! For better results, please provide some seed text, use embedding size of 15 and block size of 15.
