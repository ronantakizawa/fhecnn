# fhecnn
A CNN for Emotion Detection that is Fully Homomorphically Encrypted.

Using the ICML Face Dataset, I built a CNN that works with encrypted face data using PyTorch. To run this encrypted model, I compressed the image inputs and quantizated the CNN model so the weights and vectors of the model can works with the TFHE FHE scheme.


Based on this model: https://github.com/emil-ayv/Emotion_Recognition_Project/blob/main/emotion_pred.ipynb

More on Fully Homomorphically Encrypted Models: https://github.com/zama-ai/concrete-ml/tree/main
