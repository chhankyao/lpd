# Discovering 3D Parts from Image Collections


<p style="text-align: center;">
<a href="https://www.chhankyao.com/" style="color: ##6495ED"> Chun-Han Yao </a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://hfslyc.github.io" style="color: ##6495ED"> Wei-Chih Hung </a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="http://varunjampani.github.io" style="color: ##6495ED"> Varun Jampani </a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="http://faculty.ucmerced.edu/mhyang/" style="color: ##6495ED"> Ming-Hsuan Yang </a>
</p>
<p>&nbsp;</p>


## Abstract

Reasoning 3D shapes from 2D images is an essential yet challenging task, especially when only single-view images are at our disposal.
While an object can have a complicated shape, individual parts are usually close to geometric primitives and thus are easier to model. 
Furthermore, parts provide a mid-level representation that is robust to appearance variations across objects in a particular category.
In this work, we tackle the problem of 3D part discovery from only 2D image collections.
Instead of relying on manually annotated parts for supervision, we propose a self-supervised approach, latent part discovery (LPD).
Our key insight is to learn a novel part shape prior that allows each part to fit an object shape faithfully while constrained to have simple geometry.
Extensive experiments on the synthetic ShapeNet, PartNet, and real-world Pascal 3D+ datasets show that our method discovers consistent object parts and achieves favorable reconstruction accuracy compared to the existing methods with the same level of supervision.

<center>
<figure>
    <div id="projectid">
    <img src="https://chhankyao.github.io/lpd/cover.png" width="900px" />
    </div>
    <br />
    <figcaption>
	Our method (LPD) enables self-supervised 3D part discovery while learning to reconstruct object shapes from single-view images. Compared to other methods using different part constraints, LPD discovers more faithful and consistent parts, which improve the reconstruction quality and allow part reasoning/manipulation.
    </figcaption>
</figure>
</center>


## Paper & Code

- Paper: [PDF](https://arxiv.org/pdf/2107.13629.pdf)

- Supplementary: [PDF](https://chhankyao.github.io/papers/yao21_lpd_supp.pdf)

- PyTorch Code: [Github](https://github.com/chhankyao/lpd)


## Video

<center>
<iframe width="900" height="500" src="https://youtube.com/embed/erNQANNwK6k" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</center>


## Bibtex

```markdown
@inproceedings{yao2021discovering,
  title={Discovering 3D Parts from Image Collections},
  author={Yao, Chun-Han and Hung, Wei-Chih and Jampani, Varun and Yang, Ming-Hsuan},
  booktitle={Proceedings of the IEEE/CVF International Conference on Computer Vision},
  year={2021}
}
```
