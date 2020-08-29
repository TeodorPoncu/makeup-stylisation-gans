## Local Adversarial Networks for Facial Makeup Stylisation using refference tags and features.

# Project description

![image](https://github.com/TeodorPoncu/makeup-stylisation-gans/blob/gh-pages/LSDGAN.png)

This project aims at delving in the subject of morphing local features in images by using Generative-Adversarial Methods. It's main objective is that of building on the top of existing CycleGAN based methods. Given a pair of source-refference images, from a set of selected features from the refference image a style is extracted and applied on the corresponding features from the source image. We aim at finding alternatives to refference images by using labels or higher order features that do not directly correlate to the source images. Such generative models require designing both architectures and specific training algorithms in order to jointly optimise some import classic computer vision tasks:
 
1. Feature Localisation
2. Style Transfer
3. Generative Image Modelling



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
