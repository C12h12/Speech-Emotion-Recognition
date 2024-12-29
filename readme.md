<p>Speech Emotion Recognition, abbreviated as SER, is the act of attempting to recognize human emotion and affective states from speech. This is capitalizing on the fact that voice often reflects underlying emotion through tone and pitch. This is also the phenomenon that animals like dogs and horses employ to be able to understand human emotion</p>

<h2>Libraries:</h2>
<p>In this Python mini project, we will use the libraries librosa, soundfile, and sklearn (among others) to build a model using an MLPClassifier. This will be able to recognize emotion from sound files. </p>

<h2>Dataset:</h2>
<p>we’ll use the RAVDESS dataset; this is the Ryerson Audio-Visual Database of Emotional Speech and Song dataset, and is free to download</p>

<h2>Prerequisites:</h2>
<p>we’ll need to install the following libraries with pip:</p>

<p>pip install librosa soundfile numpy sklearn pyaudio</p>

<p>Observing 3 features for the sound file:<p>
<list>
<ol>
<li>mfcc: Mel Frequency Cepstral Coefficient, represents the short-term power spectrum of a sound</li>
<li>chroma: Pertains to the 12 different pitch classes</li>
<li>mel: Mel Spectrogram Frequency</li>
</ol>
</list>
