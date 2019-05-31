# Spectogram
Create spectogram from all audio files in a folder 

For dataset to work on generating spectogram from audio files, you can refer to the link in the data file inside dataset 
folder.

To create spectograms of all audio files, i have used an for loop which will take all files from folder containing the sudio file.
(In my example, all files are stored in train/ASVspoof2017_V2_train folder.

To create the spectogram of only one file, remove the for loop and make appropiate changes in the plotstft function inside the for loop.

