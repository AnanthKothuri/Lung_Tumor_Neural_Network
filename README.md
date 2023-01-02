# Lung_Tumor_Neural_Network

This repo contains two models to identify tumor nodules in the CT scans of lungs. One is a segmentation module to find "nodules", or candidates for tumors, and the other is an identification model to correctly identify tumors from the candidates.

These models were created with pytorch and are saved in the corresponding formats. By using the torch.load(PATH) method, the models can be accessed and used accordingly.

We made modifications to the loading and saving of the model to work around our various hardware constraints. With that said, a large majority of the code is from the book Deep Learning With PyTorch by Eli Stevens, Luca Antiga and Thomas Viehmann and is protected by its corresponding copyright laws (for commercial use). The link to their github repository is provided here: https://github.com/deep-learning-with-pytorch/dlwpt-code
