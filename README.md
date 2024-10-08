This repository contains the dataset used in the Smooth InfoMax paper (see [GitHub](https://github.com/fdenoodt/Smooth-InfoMax/)). The dataset consists of raw speech signals of fixed length, sampled at 44.1 kHz. There are 851 audio files, randomly shuffled and split into 80% training data (680 files) and 20% test data (171 files). Each audio file consists of a single spoken sound made up of three consonants and three vowels, where the consonants and vowels alternate. Some examples are the sounds "gi-ga-bu" and "ba-bi-gu." The words consist of three syllables chosen from the following list: ba, bi, bu, da, di, du, ga, gi, and gu. All the sounds are spoken by the same person in a constant tone (see `./reshuffledv2`).

We have also split the audio files into single syllables being pronounced. These files are then padded to have a fixed length (see `./split up data padded`).

## Acknowledgements

This dataset is based on audio recordings originally created by Bart de Boer, with modifications including a new train-test split and the addition of syllable-split audio files. The original dataset can be found at [TODO].
