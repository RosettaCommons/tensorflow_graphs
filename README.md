# Rosetta Tensorflow graph repository submodule

A submodule containing Tensorflow models for various machine learning-based protocols.

## History

* Created as "trRosetta" repo on 21 Jan 2021 by Vikram K. Mulligan, Flatiron Institute (vmulligan@flatironinstitute.org).
* Renamed to "tensorflow\_graphs" repo on 22 Jan 2021.
* VKM added deepFRI neural network on 27 April 2021.

## Contents

### deepFRI

A neural network combining an LSTM (long short-term memory) model with a deep graph convolutional neural network to predict protein function from sequence and structure.  Sequence is processed by the LSTM language model, and structure by the deep graph convolutional neural network.

### trRosetta

A machine learning model that takes an input multiple sequence alignment and produces an output estimate of pairwise residue distances and angles, useful for protein structure prediction.

### predict_PTMs
Several machine learning models that take structural and sequence information as input features and predict various post-translational modifications, meant to be used with Rosettas `PTMPredictionMetric`.


### ESM
Contains the Evolutionary Scaling Modeling language model family from the FAIR team, adapted from PyTorch to Tensorflow by Huggingface.
