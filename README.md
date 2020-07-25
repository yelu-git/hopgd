## HOPGD

HOPGD, abbreviation for Higher-Order Proper Generalized Decomposition, is a multi-dimensional arrays decomposition method. Similarly to PARAFAC, it can be used to compress multi-dimensional arrays to multiple simple vectors. But differently, it determines automatically the necessary number of vectors for a given approximation accuracy. 

Beside data compression, HOPGD can be used for surrogate modeling,  model calibration and optimization, uncertainty quantification, as well as real-time simulation of complex systems.

This website summarizes our recent work on HOPGD and shares some implementation examples. If you use the codes, please consider citing our work.

### Standard implementation

Standard implementation of HOPGD is based on full order arrays without unknown values for the components.

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

### Implementation in case of gappy data



1. Lu, Y., Blal, N., & Gravouil, A. (2019). Datadriven HOPGD based computational vademecum for welding parameter identification. Computational Mechanics. [DOI](10.1007/s00466-018-1656-8)

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/yelu-git/hopgd/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Contact

Contact me: ye.lu@northwestern.edu, if you have any questions.

We would like to acknowledge Dr. Shuai chen for his help in the database generation for our work.

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
