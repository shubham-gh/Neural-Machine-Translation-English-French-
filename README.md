Date Translator: NMT with Attention

This project uses an attention-based Neural Machine Translation (NMT) model to translate various human-readable dates into a standard YYYY-MM-DD format.



Core Features

Attention Mechanism: Focuses on relevant parts of the input to generate correct output.

Bidirectional LSTM Encoder: Reads dates forwards and backwards for full context.

LSTM Decoder: Generates the output date one character at a time.

Attention Visualization: Shows the model's focus during translation.

Quickstart

1. Install Dependencies:



pip install tensorflow keras numpy faker babel matplotlib tqdm termcolor

2. Run Notebook:

Launch Neural machine translation with attention_latest.ipynb. Running the cells will build and train the model, though pre-trained weights can be loaded to skip this.



Project Files

The main logic is in the .ipynb notebook. nmt_utils.py contains data helpers, and test_utils.py verifies model components.



Acknowledgements

Based on an assignment from the Coursera Deep Learning Specialization by deeplearning.ai.
