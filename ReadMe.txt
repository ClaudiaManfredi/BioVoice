---
title: "BioVoice"
authors: "Maria Sole Morelli, Silvia Orlandi, Claudia Manfredi"
date: '22/05/20'
---

## BioVoice
BioVoice is a user-friendly software platform designed to perform acoustical analysis of the human voice. BioVoice was developed at the Biomedical Engineering Lab, Universita’ degli Studi di Firenze. It allows recording the human voice from the newborn to the elder and performing both time and frequency analysis, estimating more than 20 acoustical parameters. 
The user has to follow few mandatory steps to perform voice analysis. First, the user selects and uploads at least one audio file. Only .wav files can be analysed.

Before starting the analysis, the user has to specify the settings of the audio file(s). Specifically, age (newborn, child, adult), gender (male or female), and kind of vocal emission (voiced, singing, cry) must be selected. When the analysis starts, BioVoice first performs the selection of voiced/unvoiced (V/UV) audio segments. Then, all the parameters of interests are extracted from each voiced segment. Specifically, in time domain, information about the number and length of voiced segments, length of silence segments and percentage of voiced segments are extracted and saved in an excel table. 

In the frequency domain, fundamental frequency (F0), formant frequencies (F1, F2, F3), noise level (Normalized Noise Energy) and jitter are estimated. For F0 and for each formant, the mean, median, standard deviation, maximum and minimum values are calculated and saved in excel tables.
Furthermore, differently from other automatic software tools, BioVoice implements specific tools both for the newborn cry, the child and the singing voice. Specifically, for newborn cry and child voice, it computes the melodic shape of F0, automatically identifying up to 12 melodic shapes: (rising R, falling F, symmetric S, plateau P, low-up LU, up-low UL, double D, frequency step FS, complex C, unstructured U, not a cry NC, other O). It also allows performing the perceptual melodic analysis: the user looks at the shape of each F0 voiced frame and classifies it manually. Objective and perceptual results are then compared and the percentage of the match is displayed. In the singing voice case F0 is displayed in cents (100 cents = 1 semitone = 1/12 octave). Two more formants are computed (F4 and F5) as well as the quality ratio (QR) and parameters concerning vibrato (rate and extent) and its regularity (jitter and shimmer).

At the end of the analysis, BioVoice results and pictures are saved in a specific folder created in the same directory of the audio file. Tables (in Excel format) contain F0 and formants values and statistical information about the parameters. Colour figures (.jpeg) include: V/UV selection, F0 shape and spectrogram with formants values superimposed, for each detected voiced frame.

## Requirements and Running
BioVoice is a software platform designed in MATLAB® (R2019a).
Here it executable beta version is available,  that does not require the installation of the MATLAB® software.

The computer must be equipped with at least an Intel® Core™i3 processor with a 64-bit card. Windows OS (from Windows 7 on) is required. It does not run under Mac OS. 

To run BioVoice, download the file `BioVoice.exe` and once unzipped, launch the application. Follow the instructions to install BioVoice.

## Distribution restrictions
BioVoice is the exclusive property of Universita’ degli Studi di Firenze, and is distributed free of charge on this platform. Any unauthorized use or its marketing will be legally prosecuted.

## References
Please use the following references when you cite BioVoice:

1. Orlandi, S., Dejonckere, P. H., Schoentgen, J., Lebacq, J., Rruqja, N., & Manfredi, C. (2013). Effective pre-processing of long term noisy audio recordings: An aid to clinical monitoring. Biomedical Signal Processing and Control, 8(6), 799-810.[Link](https://doi.org/10.1016/j.bspc.2013.07.009)

2. Rruqja, N., Dejonckere, P. H., Cantarella, G., Schoentgen, J., Orlandi, S., Barbagallo, S. D., & Manfredi, C. (2014). Testing software tools with synthesized deviant voices for medicolegal assessment of occupational dysphonia. Biomedical Signal Processing and Control, 13, 71-78. [Link](https://doi.org/10.1016/j.bspc.2014.03.011)

3. Morelli, M.S., Orlandi, S., Manfredi, C., BioVoice: a multipurpose tool for voice analysis, Proc. 11th Int. Workshop Models and Analysis of Vocal Emissions for Biomedical Applications, MAVEBA 2019, December, 17-19, 2019, Firenze University Press, (2019) 261-264. [Link](https://flore.unifi.it/retrieve/handle/2158/1191438/475083/Morelli.pdf)

## Related publications
1. Manfredi, C., Bocchi, L., & Cantarella, G. (2009). A multipurpose user-friendly tool for voice analysis: application to pathological adult voices. Biomedical Signal Processing and Control, 4(3), 212-220. [Link](https://doi.org/10.1016/j.bspc.2008.11.006)
2. Orlandi, S., Garcia, C. A. R., Bandini, A., Donzelli, G., & Manfredi, C. (2016). Application of pattern recognition techniques to the classification of full-term and preterm infant cry. Journal of Voice, 30(6), 656-663. [Link](https://doi.org/10.1016/j.jvoice.2015.08.007)
3. Bandini, A., Giovannelli, F., Orlandi, S., Barbagallo, S. D., Cincotta, M., Vanni, P., ... & Manfredi, C. (2015). Automatic identification of dysprosody in idiopathic Parkinson's disease. Biomedical Signal Processing and Control, 17, 47-54. [Link](https://doi.org/10.1016/j.bspc.2014.07.006)
4. Manfredi, C., Bandini, A., Melino, D., Viellevoye, R., Kalenga, M., & Orlandi, S. (2018). Automated detection and classification of basic shapes of newborn cry melody. Biomedical Signal Processing and Control, 45, 174-181. [Link](https://doi.org/10.1016/j.bspc.2018.05.033)
5. Orlandi, S., Bandini, A., Fiaschi, F. F., & Manfredi, C. (2017). Testing software tools for newborn cry analysis using synthetic signals. Biomedical Signal Processing and Control, 37, 16-22. [Link](https://doi.org/10.1016/j.bspc.2016.12.012)
6. Manfredi, C., Viellevoye, R., Orlandi, S., Torres-García, A., Pieraccini, G., & Reyes-García, C. A. (2019). Automated analysis of newborn cry: relationships between melodic shapes and native language. Biomedical Signal Processing and Control, 53, 101561. [Link](https://doi.org/10.1016/j.bspc.2019.101561)
7. Manfredi, C., Giordano, A., Schoentgen, J., Fraj, S., Bocchi, L., & Dejonckere, P. H. (2012). Perturbation measurements in highly irregular voice signals: Performances/validity of analysis software tools. Biomedical signal processing and control, 7(4), 409-416. [Link](https://doi.org/10.1016/j.bspc.2011.06.004)
8. Manfredi, C., Bocchi, L., Orlandi, S., Calisti, M., Spaccaterra, L., & Donzelli, G. P. (2008, August). Non-invasive distress evaluation in preterm newborn infants. In 2008 30th Annual International Conference of the IEEE Engineering in Medicine and Biology Society (pp. 2908-2911). IEEE. [Link](http://doi.org/10.1109/IEMBS.2008.4649811)
9. Manfredi, C., Barbagallo, D., Baracca, G., Orlandi, S., Bandini, A., & Dejonckere, P. H. (2015). Automatic assessment of acoustic parameters of the singing voice: application to professional western operatic and jazz singers. Journal of Voice, 29(4), 517-e1. [Link](https://doi.org/10.1016/j.jvoice.2014.09.014)
10. Dejonckere, P. H., Giordano, A., Schoentgen, J., Fraj, S., Bocchi, L., & Manfredi, C. (2012). To what degree of voice perturbation are jitter measurements valid? A novel approach with synthesized vowels and visuo-perceptual pattern recognition. Biomedical Signal Processing and Control, 7(1), 37-42. [Link](https://doi.org/10.1016/j.bspc.2011.05.002)
11. DeJonckere, P., Schoentgen, J., Giordano, A., Fraj, S., Bocchi, L., & Manfredi, C. (2011). Validity of jitter measures in non-quasi-periodic voices. Part I: perceptual and computer performances in cycle pattern recognition. Logopedics Phoniatrics Vocology, 36(2), 70-77. [Link](https://doi.org/10.3109/14015439.2011.578078)
12. Manfredi, C., Giordano, A., Schoentgen, J., Fraj, S., Bocchi, L., & Dejonckere, P. (2011). Validity of jitter measures in non-quasi-periodic voices. Part II: The effect of noise. Logopedics Phoniatrics Vocology, 36(2), 78-89. [Link](https://doi.org/10.3109/14015439.2011.578077)
13. Orlandi, S., Bocchi, L., Donzelli, G., & Manfredi, C. (2012). Central blood oxygen saturation vs crying in preterm newborns. Biomedical Signal Processing and Control, 7(1), 88-92. [Link](https://doi.org/10.1016/j.bspc.2011.07.003)