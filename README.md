# AUDIO_DATA_PREPROCESSING
Here we used the audio data and took its fourier transform to make its components and tried to make Spectogram so we dont lose information of time and frequency




The Task in this code was to preprocess the Audio Data 
We used the libraries such as librosa to take the Audio Signals and Visulaize it 
We make a signal in which we use the sample rate of 22050
sr * time -> 22050*20 then according to this we load our file
on the y axis we plotted the Amplitude and on x axis we plotted the time 
So we can see the signals amplitude according to the time 
Then We took the Fast Fourier Transform which decomposes the signal into different frequency signals and we plotted the specotogram of the 
Signal we are using 
It gives a mirror images of both sides so we took only one side of fast fourier transform and plotted it according to the time 
After that we realized that by taking fast fourier transform we have information about frquency but we lost the information of time so
We tried taking short fourier tranform so we have information at a particular instant 
Hop length of this parameter tells us that how much it will jump in a signal while taking the short fourier tranform after that we Converted the scale into decible and we get our original spectogram
