# Handwriting Generation
Forked from [wezteoh's implementation of handwriting generation] (https://github.com/wezteoh/handwriting_generation) to allow running on [Google Colab](https://colab.research.google.com/).

Original scripts were updated to allow compatibility with pytorch 1.4.0.

It can be run in a local machine but the model requires gpu power and the training takes a lot of time. This implementation uses wezteoh's already set weights in a modified implementation of Alex Graves' paper: [Generating Sequences With Recurrent Neural Networks](https://arxiv.org/abs/1308.0850) using pytorch.

### Running on Google Colab
Run the notebook *Handwriting Generator for colab.ipynb* either on Colab or local machine. The results can be saved into Drive as well -to do so mount drive with the instructions in the notebook.
#### Notes:
- This notebook requires Python2.7.
- The optimum length of text fed into conditional handwriting generator is ~50-65.
- To obtain different kinds of handwritings change `random_state`, `bias`, and `bias2` parameters in generate functions.

### Original Implementation
For original implementation, please see [here] (https://github.com/wezteoh/handwriting_generation).


