# DeepLearning_ShortStory
# Research paper  :High-Resolution Image Synthesis with Latent Diffusion Models. 
# Link : https://arxiv.org/pdf/2112.10752v2.pdf


![image](https://user-images.githubusercontent.com/77387431/163652361-cc98a427-b3b4-4ea6-a510-32101b3b8a75.png)


Diffusion models: built from a hierarchy of denoising autoencoders, have achieved impressive results in image synthesis and illustrate the state-of-the-art in image synthesis and super-resolution.
Being likelihood-based models, heavily using parameter sharing, they can model highly complex distributions of natural images and overcome the drawbacks of AR models and GANs.

These are a natural fit to the inductive biases of image-like data when their underlying neural backbone is implemented as a UNet and this drives their generative power. Still Evaluating and optimizing these models in pixel space, however, has the downside of low inference speed and very high training costs. We address both drawbacks with our proposed LDMs, which work on a compressed latent space of lower dimensionality.

In contrast to previous work, there is no need to rely on excessive spatial compression, as DMs get trained in the learned latent space, demonstrating better-scaling properties with respect to spatial dimensionality.
It reduced complexity, providing efficient image generation from the latent space with a single network pass.
This github repository will cover the basic introduction of image generation methods and recent advancements with Diffusion Models for image synthesis. I will review a paper called High-Resolution Image Synthesis with Latent Diffusion Models to understand this better.

![image](https://user-images.githubusercontent.com/77387431/163652348-6b02d0b8-67fc-4028-b94d-3ab9c1f05270.png)


After getting trained unconditional models of images on CelebA-HQ, FFHQ , LSUN-Churches, and -Bedrooms [102], the sample quality and their coverage of the data manifold were evaluated using ii) FID and ii) Precision-and-Recall.
We can see On CelebA-HQ, reports a new state-of-the-art FID of 5.11, outperforming previous likelihood-based models and GANs.

![image](https://user-images.githubusercontent.com/77387431/163652313-0b1373b5-78f0-45ec-8d2d-21d361588217.png)


A substantial advantage of this approach is that we require to train the universal autoencoding stage only once and can reuse it for multiple DM training or to explore maybe wholly different tasks.

# Conclusion: “As proposed by the Paper, latent diffusion models are a simple and efficient way that improve both the training and sampling efficiency of denoising diffusion models while retaining their quality”.




# Medium Article Link: https://medium.com/@rawatakanksha2020/latent-diffusion-models-high-resolution-image-synthesis-3d8af37b4d73

# Slideshare Presentation: https://www.slideshare.net/AkankshaRawat53/ldmimagesythesispptx

# Video: https://drive.google.com/drive/u/1/folders/1NHsO325rUNgd98rBE-bwpxp2UMa4TmUM


https://www.youtube.com/watch?v=QVf9-V4Ll-g



References:
https://paperswithcode.com/paper/high-resolution-image-synthesis-with-latent
https://arxiv.org/pdf/2112.10752v2.pdf
https://www.analyticsinsight.net/understanding-importance-generative-adversarial-networks-gans/
https://analyticsindiamag.com/diffusion-models-vs-gans-which-one-to-choose-for-image-synthesis/
https://cg.cs.tsinghua.edu.cn/people/~kun/papers/gan_survey_final.pdf
