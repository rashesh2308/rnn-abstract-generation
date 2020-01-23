# rnn-abstract-generation
Project using Recurrent Neural Network 

Building a model: 
Step 1: Add embedding layer If not trainable -> Add Embedding, and then Masking layer If trainable -> Add embedding 
Step 2: Add LSTM layer If more than 1 LSTM layer: return_sequences=True If Bidirectional: Add Bidirectional Layer & return_sequences = False (for 1 layer) If not Bidirectional: No Bidirectional Layer & return_sequences = False (for 1 layer) Step 3: Add Dense Layer for ReLU
Step 4: Add Dropout layer for regularization 
Step 5: Add output Layer with activation: softmax 
Step 6: Compile the model 
