# Phoneme-Analysis-and-Classification

This project builds a K-Nearest Neighbours Algorithm to classify phonemes from a data-set.

## Part 1: Dataset Collection 
Given a very large dataset of speech from the British Isles, all were manually inputted into the .csv file attached by generating an average value for each of the 3 formants present in the audio.


![An-example-of-segmentation-with-phonemes-words-and-sentences-on-a-Textgrid-file-of-Praat](https://user-images.githubusercontent.com/73174341/128985985-022c811e-3334-4cc2-b356-6b90923e19e5.png)

The audio was cut up and analysed using the free-ware Praat

## Part 2: Classification 
The scope of the project was to be able to classify the phonemes from one another. Therefore, a KNN was built in order to do just that. Resulting in an average accuracy of 89%, the notebook with the code can be found in the repository as 'Phoneme Recognition.ipynb'
