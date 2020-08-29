## Local Adversarial Networks for Facial Makeup Stylisation using refference tags and features.

# Project description

This thesis aims at delving in the subject of morphing local features in images by using Generative-Adversarial Methods. Provided the image of a face and another refference image of a face with makeup applied, we want to apply the same makeup style to the initial image.

![image](https://github.com/TeodorPoncu/makeup-stylisation-gans/blob/gh-pages/LSDGAN.png)

It's main objective is that of building on the top of existing **CycleGAN based methods**. Current methods require explicit refference images such that the method can understand the style differences between the two and moddify the source image accordingly. In scenarios such as make-up transfer in which style has to be modelled only around speciffic local regions in the image, processing a refference image is a computationally expensive operation.

Because both the source image and refference image are passed through simillar networks, there is no guarantee that the optimisable parameter space is fully used at it's potential for the transfer task.  We aim at **finding alternatives to refference images by using labels or higher order features** that do not directly correlate to the source images. Such generative models require designing both architectures and specific training algorithms in order to jointly optimise some import classic computer vision tasks:
 
1. **Generative Image Modelling**
2. **Feature Localisation**
3. **Style Transfer**

## Key problems to be tackled

In this setting the above stated tasks will require a multi-step approach that can maximise the amount of information we are correlating between image patches and labels/higher order features such that the network will not generate an overexcessive amount of mutation on top of the source image. Some of the functionalities of this neural system are:

- Constructing in a data-driven fashion labels/features from images for speciffic makeup products.
- Correctly identifying what facial features are affected by a certain refference label/feature of a given product.
- Stylising the selected facial features accordingly to the label/features of the product.
- Ensuring that the stylisation is done in a human-like fashion that does not seem unrealistic
- Varying the intensity of the applied stylisitaion in a human-like fashion

## Number of students

This thesis is reserved for 1 student that will work alongside the thesis coordinator and another lab member that works in very closely related subjects. Both mathematical and coding guidance will be provided for this specific topic.

## Minimal Bibliography

[1] - Li, Tingting, et al. "Beautygan: Instance-level facial makeup transfer with deep generative adversarial network." Proceedings of the 26th ACM international conference on Multimedia. 2018.
[2] - Li, Yi, et al. "Anti-makeup: Learning a bi-level adversarial network for makeup-invariant face verification." arXiv preprint arXiv:1709.03654 (2017).
[3] - Zhang, Honglun, et al. "Disentangled Makeup Transfer with Generative Adversarial Network." arXiv preprint arXiv:1907.01144 (2019).
[4] - Jiang, Wentao, et al. "Psgan: Pose and expression robust spatial-aware gan for customizable makeup transfer." Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2020.
[5] - Chen, Hung-Jen, et al. "Beautyglow: On-demand makeup transfer framework with reversible generative network." Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2019.

The above mentioned papers will represent the basis of the work on which this thesis will be based.
