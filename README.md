# model_sqm_with_rnns
Lab Immersion in LSPY (EPFL) - Modelling the Sequential Metacontrast Paradigm with Recurrent Neural Networks (see pdf).

The Sequential Metacontrast Paradigm (SQM) is a practical tool to study temporal feature integration by the human visual system during object detection. 
As more realistic to model biological object detection than feedforward convolutional neural networks (ffCNNs), recurrent neural networks (RNNs) were explored to simulate human feature integration using the SQM. 
In this project, five RNNs were tested: vanilla RNN, LSTM, Gated recurrent unit (GRU), convolutional LSTM and PredNet. 
To model the SQM, a reconstruction-decoder framework was implemented.

This project was implemented using Google Colab, so certain lines could not compile/execute out of Colab.

Core features of the project:
 - Dataset generation for reconstruction, decoding and testing (i.e., SQM) frameworks
 - Motion generation for reconstruction, decoding and testing (examples of each "motion" function in "Motion_data/")
 - Training for reconstruction and decoding (300 epochs each)
 - Testing using the SQM (1000 examples), plotting central vernier dominance and model entropy.
 
To run the project:
 - Execute all cells until the reconstruction training
 - Then, train reconstruction, decoding, and finally test the model using the SQM.
