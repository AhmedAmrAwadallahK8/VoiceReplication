# Voice Replication
Small step in an overall project to create a voice mimic tool. What this currently does is take an
audio clips frequency space data and a "fresh" list of harmonic waves ranging from 20 hz to
20000 hz at 20 hz intervals. By weighting the frequencies according to the frequency space data
a sound clip can then be replicated. This was also performed in batches on the audio data as 
frequency space data loses all time data so by performing the process in batches some 
semblance of time information is still retained.