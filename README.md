# Awesone Neural Rendering (WiP)

A curated list of awesome neural rendering resources!

Neural rendering is emerging technology that envisons a way to render (mostly) 3D objects into 2D images with deep neural networks, instead of conventional rasterization and ray tracing. How awesome!

Enjoy the list, and [contribution](#contributing) is welcome!

**Table of Contents**

1. [Academic Publictions](#academic-publications)
    * [Surveys](#surveys)
    * [Neural Radiance Fields (NeRF)](#neural-radiance-fields-nerf)
    * [Neural Representation](#neural-representation)
    * [De-rendering](#de-rendering)
    * [Neural Integration](#neural-integration)
    * [MLP-based Architecture in general](#mlp-based-architecture-in-general)
    * [Neural Rendering and Differentiable Rendering in general](#neural-rendering-and-differentiable-rendering-in-general)
3. [Blog posts and Videos](#blog-posts-and-videos)
4. [Neural Rendering Development](#neural-rendering-development)
5. [Contributing](#contributing)

## Academic Publications

Note: due to lack of space, we wrote the first author only.

### Surveys

**2020**

| Author | Title | Venue | Project | Code | etc. |
|---|---|:---:|:---:|:---:|:---:|
| Ayush Tewari | [State of the Art on Neural Rendering](https://arxiv.org/abs/2004.03805) | Computer Graphics Forum | - | - | - |

### Neural Radiance Fields (NeRF)

**2020**

| Author | Title | Venue | Project | Code | etc. |
|---|---|:---:|:---:|:---:|:---:|
| Ben Mildenhall | [NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://arxiv.org/abs/2003.08934) | ECCV | [Project](https://www.matthewtancik.com/nerf) | [TF(Author)](https://github.com/bmild/nerf) | - |
| Keunhong Park | [Deformable Neural Radiance Fields](https://arxiv.org/abs/2011.12948) | arXiv | [Project](https://nerfies.github.io) | [TF(Author)](https://github.com/google/nerfies) |

**2021**

| Author | Title | Venue | Project | Code | etc. |
|---|---|:---:|:---:|:---:|:---:|
| Stephan J. Garbin | [FastNeRF: High-Fidelity Neural Rendering at 200FPS](https://arxiv.org/abs/2103.10380) | arXiv | - | - | - |
| Alex Yu | [PlenOctrees for Real-time Rendering of Neural Radiance Fields](https://arxiv.org/abs/2103.14024) | arXiv | - | - | - |
| Peter Hedman | [Baking Neural Radiance Fields for Real-Time View Syntheis](https://arxiv.org/abs/2103.14645) | arXiv | [Project](https://phog.github.io/snerg/) | - | - |

### Neural Representation

**2019**

| Author | Title | Venue | Project | Code | etc. |
|---|---|:---:|:---:|:---:|:---:|
| Jeong Joon Park | [DeepSDF: Learning Continous Signed Distance Functions for Shape Representation](https://openaccess.thecvf.com/content_CVPR_2019/html/Park_DeepSDF_Learning_Continuous_Signed_Distance_Functions_for_Shape_Representation_CVPR_2019_paper.html) | CVPR | - | - | - |
| Vincent Sitzmann | [Scene Representation Networks: Continous 3D-Structure-Aware Neural Scene Representations](https://arxiv.org/abs/1906.01618) | NeurIPS | [Project](https://vsitzmann.github.io/srns/) | [Code](https://github.com/vsitzmann/scene-representation-networks) | Honorable Mention |

**2020**

| Author | Title | Venue | Project | Code | etc. |
|---|---|:---:|:---:|:---:|:---:|
| Abhimitra Meka	| [Deep relightable textures: volumetric performance capture with neural rendering](https://dl.acm.org/doi/abs/10.1145/3414685.3417814) | ToG | - | - | - |


**2021**

| Author | Title | Venue | Project | Code | etc. |
|---|---|:---:|:---:|:---:|:---:|
| Yuzhe Lu | [Compressive Neural Representations of Volumetric Scala Fields](https://arxiv.org/abs/2104.04523) | arXiv | - | - | - |
| Towaki Takikawa | [Neural Geometric Level of Detail: Real-time Rendering with Implicit 3D Shapes](https://arxiv.org/abs/2101.10994) | arXiv | - | - | - |
| Alexandr Kuznetsov | [NeuMIP: Multi-Resolution Neural Materials](https://arxiv.org/abs/2104.02789) | arXiv | - | - | - |


### De-rendering

**2021**

| Author | Title | Venue | Project | Code | etc. |
|---|---|:---:|:---:|:---:|:---:|
| Shangzhe Wu | [De-rendering the World's Revolutionary Artefacts](https://arxiv.org/abs/2104.03954) | CVPR | [Project](https://sorderender.github.io/) | - | - |

### Neural Integration

**2021**

| Author | Title | Venue | Project | Code | etc. |
|---|---|:---:|:---:|:---:|:---:|
| David B. Lindell | [AutoInt: Automatic Integration for Fast Neural Volume Rendering](https://arxiv.org/abs/2012.01714) | CVPR | [Project](http://www.computationalimaging.org/publications/automatic-integration/) | - | - |
| Zongyi Li | [Fourier Neural Operator for Parametric Partial Differential Equations](https://arxiv.org/abs/2010.08895) | ICLR | - | - | - |

### MLP-based Architecture in general

**2020**

| Author | Title | Venue | Project | Code | etc. |
|---|---|:---:|:---:|:---:|:---:|
| Vincent Sitzmann | [Implicit Neural Representations with Periodic Acivation Functions](https://arxiv.org/abs/2006.09661) | NeurIPS | [Project](https://vsitzmann.github.io/siren/) | - | - |

**2021**

| Author | Title | Venue | Project | Code | etc. |
|---|---|:---:|:---:|:---:|:---:|
| Etai Littwin | [On Infinite-Width Hypernetworks](https://arxiv.org/abs/2003.12193) | arXiv | - | - | - |
| Emilien Dupont | [Generative Models as Distributions of Functions](https://arxiv.org/abs/2102.04776) | arXiv | - | - | - |
| Inhit Mehta | [Modulated Periodic Activations for Generalizable Local Functional Representations](https://arxiv.org/abs/2104.03960) | arXiv | - | - | - |


### Neural Rendering and Differentiable Rendering in general

**2018**

| Author | Title | Venue | Project | Code | etc. |
|---|---|:---:|:---:|:---:|:---:|
| SM Ali Eslami | [Neural scene representation and rendering](https://science.sciencemag.org/content/360/6394/1204.abstract) | Science | - | - | - |

## Blog posts and Videos

**2020**

| Author/Speaker | Title | Venue | Media |
|---|---|:---:|:---:|
| Frank Dellaert | [NeRF Explosion 2020](https://dellaert.github.io/NeRF/) | - | Blog |
| Matthias Neißner | [Why Neural Rendering is just Awesome](https://www.youtube.com/watch?v=zNvS5hQsWEo) | CMU AI Seminar | YouTube |
| Various speakers | [Neural Rendering - CVPR 2020 tutorial](https://www.neuralrender.com) | CVPR | YouTube |

## Neural Rendering Development

TBD (e.g., PyTorch3D)

## Contributing

Your contribution is always welcome!

Please share your materials (e.g., publications, blog posts) via Pull request.

### Maintainer

Please feel free to contact us!

[Jaewon Choi](https://sites.google.com/view/jaewon-choi), Ph.D. student at Yonsei University.

Seoyeon Stella Yang, Ph.D. candidate at Seoul National University

Neural Rendering Facebook group: [[Link]](https://www.facebook.com/groups/neuralrendering)
