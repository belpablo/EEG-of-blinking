# EEG-of-blinking

Main goal: Develop an EEG authentication algorithm based on blinks. 

Based on the EEG blink recordings made by the NeuroPlay-8Cap device from a certain group of people, it is required to train an identifier that can later determine from new EEG recordings which person from the group they belong to.

1) Evgeny_1, Evgeny_2, .., Pavel_5 contain recordings of electroencephalograms of forced blinks of 4 people. Blinks were performed at frequencies of 38, 45, and 50 units per second.

2) DB2_CrossVal.ipynb contains classification based on 2-nd order Daubechies wavelet 3-Level transform.

3) PSD_one_file.ipynb contains classification based on power spectral density of signal (Welch algorithm).
