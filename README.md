# english-french-nmt-mini-chatgpt
"A mini ChatGPT-style English to French translation model using TensorFlow &amp; Keras"
A sequence-to-sequence (seq2seq) model built using TensorFlow that translates English sentences into French. 
Includes data preprocessing, positional encoding, and a transformer-style attention mechanism. 
Simulates a mini ChatGPT-style translation model for research.
## Features
- English → French sentence translation
- Data normalization and tokenization
- Transformer-style encoder-decoder with attention
- Positional embeddings
- Training history visualization (loss & accuracy plots)
- Dummy fallback translation for unseen sentences
## How to Run
1. Clone the repository:
   git clone <your-repo-link>
2. Open `main.ipynb` in Google Colab or Jupyter Notebook.
3. Run each cell sequentially.
4. Ensure you have TensorFlow and Matplotlib installed:
   pip install tensorflow matplotlib
5. Input English sentences to get French translations.

## Sample Output
English: Good morning
Translated: Bonjour

English: I love you
Translated: Je t'aime

