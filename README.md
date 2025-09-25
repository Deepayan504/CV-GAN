# CV-GAN
GAN based Emulator for global monthly SST data, capable of generating maps for 1000 years

Earth System Models like atmosphere-ocean coupled climate models (AOGCMs) attempt to simulate the worldwide climate for
both historical periods and the future, under various forcings. While these models often do a reasonably good job of representing
the variability of many climatic variables, but they suffer from limitations in representing the underlying processes fully and
accurately, spatial and temporal biases in their simulations and deviating from the observed variability. The rapid advances in
application of AI models to weather prediction opens the possibility of applying similar data-driven models to emulate climate
variability better than AOGCMs. Generative Models like Generative Adversarial Networks, Variational Autoencoders are
capable of synthesizing new realistic data, making them suitable for such emulation. This work introduces Climate Variability
Generative Adversarial Network (CV-GAN) - a generative model based on Pix2Pix Conditional Generative Adversarial Network
(GAN) to emulate global SST variability. We aim to use it to generate worldwide SST data more efficiently and accurately than
AOGCMs, while retaining the variability captured by AOGCMs. For this purpose, CV-GAN is first trained using AOGCM
simulation data to learn the variability and then fine-tuned with observational data to remove the biases in the AOGCM. A
1000-year simulation by CV-GAN is found to overcome major biases of AOGCM simulations and also simulate SST variability
significantly closer to observation than the AOGCMs. These results indicate that CV-GAN has the potential to evolve into
a foundation model for worldwide climate for seasonal and decadal climate simulations more accurately than AOGCM with
significantly less computational requirements.

DOI: 10.22541/essoar.174671893.31045476/v1



