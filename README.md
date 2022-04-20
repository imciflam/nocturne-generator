# nocturne-generator

classical music generation based on Chopin's Nocturnes using RNNs.

attention: current version is on tf v1.13.0

To create a folder in the save directory with generated MIDI files from a trained model on Bach's Chorales:

python BachProp.py ChoralesMusic21 load

To train and save a model on DATASET (provided the midi data are in a midi folder inside a directory named DATASET in the data directory):

python BachProp.py DATASET train
