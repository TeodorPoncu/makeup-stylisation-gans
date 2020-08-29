## Local Adversarial Networks for Facial Makeup Stylisation using refference tags and features.

# Project description

This project aims at delving in the subject of morphing local features in images by using Generative-Adversarial Methods. Provided the image of a face and another refference image of a face with makeup applied, we want to apply the same makeup style to the initial image.

![image](https://github.com/TeodorPoncu/makeup-stylisation-gans/blob/gh-pages/LSDGAN.png)

It's main objective is that of building on the top of existing **CycleGAN based methods**. Current methods require explicit refference images such that the method can understand the style differences between the two and moddify the source image accordingly. In scenarios such as make-up transfer in which style has to be modelled only around speciffic local regions in the image, processing a refference image is a computationally expensive operation.

Because both the source image and refference image are passed through simillar networks, there is no guarantee that the optimisable parameter space is fully used at it's potential for the transfer task.  We aim at **finding alternatives to refference images by using labels or higher order features** that do not directly correlate to the source images. Such generative models require designing both architectures and specific training algorithms in order to jointly optimise some import classic computer vision tasks:
 
1. **Feature Localisation**
2. **Style Transfer**
3. **Generative Image Modelling**



You can use the [editor on GitHub](https://github.com/TeodorPoncu/makeup-stylisation-gans/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/TeodorPoncu/makeup-stylisation-gans/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
