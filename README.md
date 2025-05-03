# Deepfake-Synthetic-Speech-Detection-using-ASVspoof-and-IEMOCAP-Datasets
Abstract—The generation, proliferation, and manipulation
of synthetic speech data have raised serious concerns
regarding its potential misuse for malicious purposes, such as
identity theft and misinformation. While many existing synthetic
speech detection models focus on spectral features, they often
overlook the role of emotional and prosodic characteristics that
could provide crucial distinctions between bonafide and spoofed
speech. This work introduces a novel deep neural network
approach for deepfake speech detection that integrates emotional
awareness by leveraging features extracted from the ASVspoof
2019 and IEMOCAP datasets. The model captures dependencies
in cepstral, prosodic, and emotional features, including variability
in pitch, energy, and the emotional resonance of the speaker
in both scripted and improvised environments. An ensemble
architecture combining sequence-to-sequence neural networks
with attention mechanisms is employed to classify synthetic and
real speech. Experimental results on the ASVspoof LA dataset
demonstrate a test accuracy of 88.98%, precision of 0.4722, recall
of 0.7829, and an F1-score of 0.5891. These results highlight the
potential of incorporating emotional and cognitive features into
deepfake speech detection systems. This study emphasizes the
importance of combining traditional spectral analysis with nonspectral,
emotionally-aware features to improve robustness and
reliability in detecting synthetic speech.

Index Terms—synthetic speech detection, deepfake, emotional
awareness, ASVspoof, IEMOCAP, prosodic features, sequenceto-
sequence, neural networks
