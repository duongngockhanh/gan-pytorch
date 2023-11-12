# Implementation of Generative Adversarial Network in PyTorch
This is a very basic implementation of the original version of Generative Adversarial Network.

## Run
1. Make sure you use **GPU** (you can use Collab).
2. Make sure that before running, delete the **results** folder.

## Discussion
As you can see, the resulting image set in the last epochs contains a lot of 1's. This phenomenon is called **Mode Collapse**. You can learn more about this phenomenon with the keyword **Mode Collapse GAN** on Google Search.

![epoch_19](https://github.com/duongngockhanh/original-gan/assets/87640587/895ba32b-a87d-47c1-bab4-a3c06dd620e5)

Currently, most of the papers on GANs produced are to handle this phenomenon. It has 3 approaches, including:
1. Loss function (**Wasserstein GAN** solves this problem quite well).
2. Network architecture.
3. Training techniques.
