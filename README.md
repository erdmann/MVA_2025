# MVA 2025: AI and Computer Vision for Cultural Heritage

This is the github repo for the 2025 version of the ENS MVA course on [AI and Computer Vision for Cultural Heritage](https://www.master-mva.com/cours/ai-and-computer-vision-for-cultural-heritage/), taught by Prof. Dr. Robert G. Erdmann (r.g.erdmann@uva.nl).

- Assignments are in the [assignments](https://github.com/erdmann/MVA_2025/tree/main/assignments) folder
- Notebooks, for example those developed in class, are in the [notebooks](https://github.com/erdmann/MVA_2025/tree/main/notebooks) folder
- Data are, where possible, in the [data](https://github.com/erdmann/MVA_2025/tree/main/data) folder, but in cases in which the files are too large, they may also appear in the [releases](https://github.com/erdmann/MVA_2025/releases) section.

# News

2025-03-20

- [Assignment 3](https://github.com/erdmann/MVA_2025/blob/main/assignments/MVA_2025_AICVCH_Assignment_3.ipynb) is posted.  I gave explicit instructions for most all of the steps, so it should be relatively straightforward.  It's due on March 27.


2025-03-14
- Some additional links are posted below for some lecture notes and other useful information.
- A new notebook has been added for download of a 14k image dataset of posters from the BnF.
- A painting radiograph corresponding to Rijksmuseum object number [SK-C-207](https://www.google.com/search?q=SK-C-207+Rijksmuseum) (A waterfall, Adam Pijnacker, 1649 - 1673) is posted in the data section, as a demonstration for performing canvas analysis.


2025-03-06
- [Assignment 2](https://github.com/erdmann/MVA_2025/blob/main/assignments/MVA_2025_AICVCH_Assignment_2.ipynb) is posted.  It is due on March 17.

# Links

* **The Structure Tensor** 
  - [Lecture notes from Linköping University](https://web.archive.org/web/20210424061948/http://www.cvl.isy.liu.se/en/education/undergraduate/tsbb15/lectures/lecture-03.pdf) Provides a variety of motivations for the structure tensor and coherence measures.
  
* **International Image Interoperability Framework (IIIF)**
  - https://iiif.io/



# Papers

*   **RANSAC-Flow:**

    *   Title: RANSAC-Flow: generic two-stage image alignment
    *   Link: [arXiv:2004.01526](https://arxiv.org/abs/2004.01526)

*   **W-Net:**

    *   Title: The Little W-Net That Could: State-of-the-Art Retinal Vessel Segmentation with Minimalistic Models
    *   Link: [arXiv:2009.01907](https://arxiv.org/abs/2009.01907)

*   **U-Net:**

    *   Title: U-Net: Convolutional Networks for Biomedical Image Segmentation
    *   Link: [arXiv:1505.04597](https://arxiv.org/abs/1505.04597)

*   **Image Style Transfer:**

    *   Title: Image Style Transfer Using Convolutional Neural Networks
    *   Link: [CVPR Paper](https://www.cv-foundation.org/openaccess/content_cvpr_2016/html/Gatys_Image_Style_Transfer_CVPR_2016_paper.html)

*   **The Structure Tensor**
    * [Multiscale Texture Enhancement](https://kluedo.ub.rptu.de/frontdoor/deliver/index/docId/570/file/gruen_139.pdf)  Gives explicit derivations for the eigenvalues and eigenvectors of the structure tensor in Eqs. (10) and (11).

*   **ConvNeXt:**

    *   Title: A ConvNet for the 2020s
    *   Link: [arXiv:2201.03545](https://arxiv.org/abs/2201.03545)
    *   Also see: [GitHub Code Release](https://github.com/facebookresearch/ConvNeXt)

*   **ConvNeXt V2:**
    *   Title: ConvNeXt V2: Co-designing and Scaling ConvNets with Masked Autoencoders
    *   Link: [arXiv:2301.00808](https://arxiv.org/abs/2301.00808)

*   **ResNet50:**

    *   Title: Deep Residual Learning for Image Recognition
    *   Link: [arXiv:1512.03385](https://arxiv.org/abs/1512.03385)
    *   Also see: [Hugging Face Model Hub](https://huggingface.co/microsoft/resnet-50)

*   **UMAP:**

    *   Title: UMAP: Uniform Manifold Approximation and Projection for Dimension Reduction
    *   Link: [arXiv:1802.03426](https://arxiv.org/abs/1802.03426)
    *   Also see these alternative links: [GitHub](https://github.com/lmcinnes/umap), [Journal of Open Source Software](https://theoj.org/joss-papers/joss.00861/10.21105.joss.00861.pdf)

*   **t-SNE:**

    *   Title: Visualizing Data using t-SNE
    *   Link: [JMLR Paper](http://www.jmlr.org/papers/v9/vandermaaten08a.html)
    *   Also See: [t-SNE Homepage (Laurens van der Maaten)](https://lvdmaaten.github.io/tsne/)

*   **CLIP:**

    *   Title: Learning Transferable Visual Models From Natural Language Supervision
    *   Link: [arXiv:2103.00020](https://arxiv.org/abs/2103.00020)
    *   Also See: [Official OpenAI CLIP GitHub](https://github.com/openai/CLIP), [OpenCLIP (open-source implementation)](https://github.com/mlfoundations/open_clip)

*   **DINOv2:**

    *   Title: DINOv2: Learning Robust Visual Features without Supervision
    *   Link: [arXiv:2304.07193](https://arxiv.org/abs/2304.07193)
    *   Also See: [GitHub](https://github.com/facebookresearch/dinov2), [HuggingFace](https://huggingface.co/docs/transformers/main/en/model_doc/dinov2), and [Meta AI Demos](https://metademolab.com/projects/dino-v2)

# Online Interactive Visualizations

* R.G. Erdmann. “Automatically colorized radiograph for Vermeer’s Milkmaid, (Rijksmuseum SK-A-2344)”. 2023-01-08. Online at http://tinyurl.com/2pp9yd4s
* R.G. Erdmann. “Evidence of stress-induced craquelure through high-resolution image coherence angle analysis of Vermeer’s Milkmaid (Rijksmuseum SK-A-2344). images.erdmann.io, 2023-01-08. Online at http://tinyurl.com/r7w6vrru
* R.G. Erdmann. “Interactive visualization of canvas support thread angles in Vermeer’s Milkmaid (Rijksmuseum SK-A-2344)”, images.erdmann.io, 2023-01-10. Online at http://tinyurl.com/bdda4mvr
* R.G. Erdmann with RIS data collected by F. Gabrieli. “An online interactive tool for false-color image creation from a fused RIS-VNIR+RIS-SWIR dataset for Vermeer’s Milkmaid (Rijksmuseum SK-A-2344)”, images.erdmann.io, 2023-01-10. Online at http://tinyurl.com/4jrbjc8c
* R.G. Erdmann with MA-XRF data collected by A. van Loon. “Demonstration of a neural network-based approach for denoising and deconvolution of raw MA-XRF scans with several elemental maps from Vermeer’s Milkmaid (Rijksmuseum SK-A-2344)”, images.erdmann.io, 2023-01-12, Online at http://tinyurl.com/4t5dnm9c