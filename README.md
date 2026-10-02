# NLP_NeuralClassifier
This project is a small neural network model that predicts whether a sentence is positive or negative. It uses a simple text processing pipeline and a feed forward neural network built with PyTorch.

 # How it works
1. Tokenization  
Text is lowercased and split into individual words.

2. Vocabulary Building  
Each unique word is assigned an index. Unknown words map to <UNK>.

3. Embedding Layer  
Words are converted into dense vectors that represent their meaning.

4. Mean Pooling  
The model averages all word embeddings in a sentence.

5. Neural Network  
A hidden layer learns patterns that indicate sentiment, and an output layer predicts positive or negative.

# Features
- Simple preprocessing
- Custom vocabulary
- Embedding & hidden layer neural network
- Training loop with accuracy reporting
- Easy prediction function for new sentences
