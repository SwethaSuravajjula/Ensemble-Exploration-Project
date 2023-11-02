# Ensemble_Exploration
Ensemble Exploration Project
## Large Language Models
- DL with massive neural networks 
-in combination with huge amounts of data 
-aligned to human values
-to create a reasoning engine

## Modern LLMS

- GPT-3.5 : 175 Billion parameters(neurons)
- GPT-4:1.76 trillion parameters(neurons)

## Application of LLMS

- Translation
-Speech Recognition
- Automatic Summary Generation

## Steps
- Text Pre-Processing(textual data is transformed into numerical data)
- Random Parameter initialisation(model's parameters are initialised randomly)
-inputting numeric data(numerical representation is fed into the model for processing) model architecture is typically transformers( which helps in understanding the contexual patterns)
- Loss Function Calculation 
-Parameter Optimization ( Gradiant Descent)
-Iterative training
LLM enables the model to identify relationships between words in a sentence,irrespctive of their position in sequence
Transformer neural networks employ self-attention as their primary mechanism
Self-Attention calculates attention scores that determine their importance of each token with respect to the other tokens in the text of sequence, facilitating the modelling of intricate relationships within the data.

## Detailed Architecture of LLMS:
1.**Transformer Architecture**:  It relies on a mechanism called self-attention to process input sequences in parallel, making it highly efficient and well-suited for large-scale models.
2. **Attention Mechanism**: The heart of the Transformer is the attention mechanism. This mechanism allows the model to focus on different parts of the input sequence when generating output. It calculates attention scores for each input token and assigns weights to them based on their relevance to the current output. This enables the model to capture long-range dependencies and context.
3.**Multi-Head Attention**: In large language models, multi-head attention mechanisms are used to enhance the model's ability to capture various types of dependencies. Multi-head attention allows the model to attend to different positions and aspects of the input, providing richer representations.
4.**Encoder-Decoder Architecture**: Transformers are often composed of an encoder and a decoder. The encoder processes the input sequence, and the decoder generates the output sequence. This architecture is commonly used in machine translation tasks, where the input and output may have different lengths.
5. **Positional Encoding**: Since Transformers process tokens independently, they do not have any inherent notion of token position in the input sequence. To incorporate positional information, positional encodings are added to the input embeddings. These encodings help the model understand the order of tokens in a sequence.
6. **Layer Normalization**: Layer normalization is applied after each sub-layer within the Transformer architecture to stabilize training. It helps in mitigating issues like vanishing gradients and accelerates training convergence.
7. **Feed-Forward Neural Networks**: Transformers also incorporate feed-forward neural networks after each attention mechanism. These networks enable the model to learn complex relationships and transformations between tokens.
8. **Input and Output Layers**: LLMs take text input, typically in the form of tokens (words or subwords), and generate text output. They can be used for various natural language understanding (NLU) and natural language generation (NLG) tasks.
9. **Parameter Scaling**: Large language models have millions or even billions of parameters. These models are scaled up in terms of the number of layers, heads in multi-head attention, and dimensions of embeddings. The increase in parameters helps in capturing more complex language patterns and generalizing across various tasks.
10.**Pre-training and Fine-tuning**: Most large language models follow a two-step process: pre-training on a massive corpus of text and fine-tuning on specific downstream tasks. Pre-training allows the model to learn language understanding, while fine-tuning tailors it to perform specific tasks effectively.
11. **Prompting**: To use an LLM, you typically provide a text "prompt" or context, and the model generates text based on that prompt. The quality of the generated text is highly dependent on the quality and specificity of the prompt.

Links:https://www.youtube.com/watch?v=UU1WVnMk4E8
