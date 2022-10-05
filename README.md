# WGAN-for--Synuclein-endothelial-cell
Code for paper "α-Synuclein induces endothelial disruption mediated by NF-κB-regulated inflammatory responses".
\\<!--Please read our preprint at the following link:""-->
![WGAN_overveiw](https://user-images.githubusercontent.com/57948381/194007259-31720723-3108-4624-9a94-2b861db24a2a.PNG)

Abstract:  Disruption ofthe the blood– brain barrier (BBB), a special vascular system in the brain. Recent studies have provided evidence that the disruption of BBBthe integrity of the BBB is highly correlated with neurodegenerative diseasethe progression of neurodegenerative diseases. In tThis study, we have aimed to reveal the pathological role of α-sSynuclein (α-sSyn), whichthat is athe pathological inducer offor Parkinson’s dDisease (PD) and Lewy bBody dDementia (LBD), on the integrity and function of the BBB. . For this, Wwe usedhave utilized an animal model of α-sSynucleinopathy (G2-3) and an in vitro BBB model to test the effect of the α-Syn on the BBB integrity. We have observed that the integrity of the BBB integrity was severely compromisedharmed in both the in vivo and in vitro models. Generative adversarial networks (GANs) were applied for RNA sequencing of human brain endothelial cells (ECs) upon treatment with α-syn. α-syn could induce significant upregulation of pathways related to various immune responses. GAN analysis revealed that genes are governed by TNFα-associated signaling and nuclear factor-kappa B (NF-B) associated responses. We have demonstrated that TNFα- associated signaling inhibition can preserve the integrity of the BBB integrity from the pathological effect of α-sSyn’s pathological effect. through an in vitro inhibition assay. Overall, tConversely, thehis suggests that the pathological α-sSyn can indeed induce harmful effects on the BBB that areis mediated through TNFα- related inflammatory responses in the brain ECs.

## Dependencies 

This software was originally designed and run on a system running Ubuntu 18.04 with Python 3.3.6. For neural network model training and interpretation, we used a single Nvidia GeForce GTX 980 Ti GPU, though we anticipate that other GPUs will also work. Standard python software packages used: Tensorflow (1.3.0), Keras (2.0.4), numpy (1.17.3), pandas (0.24.1), scipy (1.3.1), scikit-learn (0.21.3), matplotlib (3.1.2), seaborn (0.9.0), h5py (2.9.0). We additionally used the following Python software packages available here: [IntegratedGradients](https://github.com/hiranumn/IntegratedGradients), and [GSEApy](https://pypi.org/project/gseapy/). 

## Acknowledgments  

This work supported by KBRI basic research program through KBRI funded by the Ministry of Science, ICT & Future Planning (grant numbers: ~~~~~ to M.C. and 22-BR-02-04 and 22-BR-04-01 to D.G.K.) and by a grant from the National Research Foundation of Korea (NRF-~~~~ to D.G.K.).
