### miniGPT 

A PyTorch re-implementation of GPT, both training and inference. Currently in built. 

### How GPT Works: Brick-by-Brick

- The Embedding Layer transforms input tokens into dense vector representations of fixed size, capturing the semantic meaning of words. Positional embeddings are added to encode the sequence order of tokens.

- The Transformer Block, the core of GPT, is composed of several components.

- The Multi-Head Self-Attention (MHSA) mechanism allows the model to focus on different parts of the input sequence simultaneously by computing attention scores and blending information across tokens.

- The Feedforward Network (FFN) applies a position-wise neural network to enhance the token representations.

- Each block is wrapped with Layer Normalization, which stabilizes training and improves convergence.

- The stacked Transformer Blocks collectively capture complex patterns in text, enabling GPT to generate coherent and contextually relevant outputs.

#### Output 
![](https://github.com/sreedeepEK/miniGPT/blob/0a8e825ea3b14e651ac5680e7299660c9712e8ba/output.png)
