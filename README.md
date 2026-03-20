# matsci465-project
course repository for 465 project
Project Objectives: 
This project aims to develop a reproducible computational workflow to quantitatively evaluate 
crystal orientation consistency in SnTe nanowires using high-resolution TEM (HRTEM) images and 
selected-area electron diffraction (SAED) patterns. A secondary objective is to assess the 
applicability of the same analysis pipeline to a second material system (Au₂Al), thereby examining 
sensitivity to different crystal symmetries. 
Methods & Approach: 
As a baseline, global 2D Fast Fourier Transform (FFT) will be applied to each HRTEM image to 
extract dominant lattice orientations from reciprocal-space peak positions. To improve spatial 
resolution, a multi-window FFT approach will be implemented: images will be divided into 
overlapping local regions, local FFTs will be computed, and orientation angles will be automatically 
extracted to construct spatial orientation maps and angle distributions. Quantitative metrics such as 
mean orientation and variance will be used to evaluate intra-wire and inter-wire consistency. 
Lightweight unsupervised learning methods (e.g., PCA or clustering) will be applied to FFT-derived 
feature vectors to examine structural consistency without large-scale supervised training. Finally, 
orientation results will be compared with SAED symmetry (e.g., cubic [100] relationships) for 
physics-based validation. 
 
Dataset Description: 
The dataset consists of published HRTEM images and SAED patterns of SnTe nanowires (PRL 
Fig.2 and Supplementary Fig.S2), including multiple regions from the same nanowire and additional 
nanowires. Limited Au₂Al HRTEM and SAED images from the Supplementary Material will be 
used for cross-material validation. 
 
Expected Outcomes: 
The expected outcome is a quantitative demonstration of structural coherence in SnTe nanowires and 
a validated, reproducible FFT-based analysis pipeline applicable to crystalline nanowire systems.
