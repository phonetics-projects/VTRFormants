**Vowel Formant Trajectories Database**

This repository contains the Deng et al. (2006) Vocal Tract Resonance (VTR) database.  This is a collection of hand edited vowel formant trajectories for over 500 short (2-3 second) audio clips from the TIMIT corpus of read speech, which has been used in speech research as a set of "ground truth" vowel formant measurements against which to evaluate automatic formant tracking algorithms.

The repository contains the original database 'rar' compressed file, and a translation of the formant files from binary format to comma separated text files, as well as translations of the phone and word tag files into Praat TextGrid format files.  This version of the database is in the VTR_phonlab subdirectory, and the ipython notebook that was used to do the format translations is included in 'read_deng_et_al_corpus.ipynb".

There is a user manual and set of example images from the original Deng corpus.  The structure of the VTR_phonlab folder mirrors the original structure of TIMIT with `test` and `train` subdirectories which contain examples of speech recorded in eight dialect regions of the US, and a separate subdirectory for each speaker who are identified by gender "f" or "m" and three letters, the initials of their first, middle and last name. Within each speaker's directory there are .wav, .csv, and .TextGrid files for each audio clip (usually a short sentence). 

Licensing - the corpus comes with a Microsoft Research License Agreement which specifies that the corpus be used for any non-commercial purpose.

> Deng, Li; Cui, Xiaodong; Pruvenok, Robert; Huang, Jonathan; Momen, Safiyy; Chen, Yanyi and Alwan, Abeer (2006) "A Database of vocal tract resonance trajectories for research in speech processing." *Proceedings of the IEEE International Conference on Acoustics, Speech, and Signal Processing (ICASSP)*, Toulouse, France.
