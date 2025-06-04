# Code-TFM

This github includes the code that was used during the Master's Thesis "Evaluation of degeneration in multimodal AI loops". It consists of an study of the divergence or convergence of the content after several iterations, composed by alternations of text generation from an image and image generation from the text. 

There are 2 main directories, one for each model tested during the project. The main one is the one called flux_dev, which uses the final architecture chosen during the study. It is composed by Flux.1-dev and Phi-3.5-vision-instruct. The other directory called SD_phi uses the first architecture: StableDifussion and Phi-3.5-vision-intruct.

Within the flux_dev directory, there are 2 subdirectories. That is due to the fact that ir can be run with either one GPU, "vertically", or with 2 GPUs, which is the optimal way, implemeting one model per GPU. The SD_phi option just contemplates the use of 1 GPU.
