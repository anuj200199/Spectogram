# Spectogram 

Spectogram represent variation in frequency with respect to time. 

Create spectogram from all audio files in a folder 

![Spectogram](https://user-images.githubusercontent.com/51110977/68996155-5750ac00-08bc-11ea-98ff-571020d92ef3.jpg)

For dataset to work on generating spectogram from audio files, you can refer to the link in the data file inside dataset 
folder.

To create spectograms of all audio files, i have used an for loop which will take all files from folder containing the audio file.
(In my .py file, all files are stored in train/ASVspoof2017_V2_train folder).



To create the spectogram of only one file, remove the for loop and make appropiate changes in the plotstft function inside the for loop.

REFERENCE: http://www.frank-zalkow.de/en/code-snippets/create-audio-spectrograms-with-python.html?i=1
