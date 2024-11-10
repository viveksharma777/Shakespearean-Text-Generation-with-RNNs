# Shakespearean-Text-Generation-with-RNNs
This project explores the application of Recurrent Neural Networks (RNNs) to generate text in the style of William Shakespeare. Using LSTM and GRU models, the project demonstrates text generation with a dataset based on Shakespeare's plays, emphasizing stylistic emulation through character-level language modeling.

### Project Objectives
* Develop an RNN model that generates text in Shakespeare's style.
* Compare LSTM and GRU architectures in their ability to capture character dependencies.
* Adjust the creativity of generated text with temperature tuning.

### Key Features
1. Dataset: The complete works of William Shakespeare, preprocessed into sequences for character-level training.
2. Model Architectures:
* LSTM Model: Includes embedding, LSTM, and dense layers for text prediction.
* GRU Model: Replaces LSTM with GRU for a comparative analysis of performance and efficiency.
3. Temperature Control: Adjusts randomness in text generation, allowing for varied output styles.
4. Training and Evaluation: Both models were trained using sparse categorical cross-entropy loss and the Adam optimizer.

### Usage
1. Clone this repository and download the Shakespeare dataset.
2. Preprocess the text into sequences and train the model using the provided configuration.
3. Use the trained model to generate text by adjusting the temperature parameter for diverse outputs.
