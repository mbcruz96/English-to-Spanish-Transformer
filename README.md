# English-to-Spanish Transformer from scratch
- Original implementation of the paper "Attention is All You Need" using the original architecture from the experiment along with personally selected learning hyperparameters. 
- The model was trained for the downstream task of text-to-text language translation, specifically from english to spanish.
- Most of the hyperparameters of the model architecture are identical to the specifications of the paper including.
- Dataset: opus_books en-es 93k
**Hyper-parameters**
  - Epochs: 20
  - Learning rate: .001
  - Sequence length: 350
  - Batch size: 8
  - Optimizer: Adam
  - Decay: 1e-9
