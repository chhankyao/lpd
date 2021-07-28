## Discovering 3D Parts from Image Collections

You can use the [editor on GitHub](https://github.com/chhankyao/lpd/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

## Abstract

Reasoning 3D shapes from 2D images is an essential yet challenging task, especially when only single-view images are at our disposal.
While an object can have a complicated shape, individual parts are usually close to geometric primitives and thus are easier to model. 
Furthermore, parts provide a mid-level representation that is robust to appearance variations across objects in a particular category.
In this work, we tackle the problem of 3D part discovery from only 2D image collections.
Instead of relying on manually annotated parts for supervision, we propose a self-supervised approach, latent part discovery (LPD).
Our key insight is to learn a novel part shape prior that allows each part to fit an object shape faithfully while constrained to have simple geometry.
Extensive experiments on the synthetic ShapeNet, PartNet, and real-world Pascal 3D+ datasets show that our method discovers consistent object parts and achieves favorable reconstruction accuracy compared to the existing methods with the same level of supervision.

![Image](https://chhankyao.github.io/papers/cover.png)


## Paper & Code

- Paper: [PDF](https://chhankyao.github.io/papers/yao21_lpd.pdf)

- Supplementary: [PDF](https://chhankyao.github.io/papers/yao21_lpd_supp.pdf)

- Bibtex

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

- PyTorch Code: [Github](https://github.com/chhankyao/lpd)


## Video



Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
