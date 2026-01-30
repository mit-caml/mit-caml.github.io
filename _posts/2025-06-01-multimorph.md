---
layout: post
type: "publication"
title:  "MultiMorph: On-demand Atlas Construction"
authors: "S. Mazdak Abulnaga, Andrew Hoopes, Neel Dey, Malte Hoffmann, Bruce Fischl, John Guttag, Adrian V. Dalca"
venue: "IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) 2025"
external-url: "https://openaccess.thecvf.com/content/CVPR2025/html/Abulnaga_MultiMorph_On-demand_Atlas_Construction_CVPR_2025_paper.html"
code: "https://github.com/mabulnaga/multimorph"
website: "https://people.csail.mit.edu/abulnaga/multimorph/index.html"
---
```
We present MultiMorph, a fast and efficient method for constructing anatomical atlases on the fly. Atlases capture the
canonical structure of a collection of images and are essential for quantifying anatomical variability across populations. However, current atlas construction methods often
require days to weeks of computation, thereby discouraging
rapid experimentation. As a result, many scientific studies
rely on suboptimal, precomputed atlases from mismatched
populations, negatively impacting downstream analyses.
MultiMorph addresses these challenges with a feedforward model that rapidly produces high-quality, populationspecific atlases in a single forward pass for any 3D brain
dataset, without any fine-tuning or optimization. MultiMorph is based on a linear group-interaction layer that aggregates and shares features within the group of input images. Further, by leveraging auxiliary synthetic data, MultiMorph generalizes to new imaging modalities and population groups at test-time. Experimentally, MultiMorph outperforms state-of-the-art optimization-based and learningbased atlas construction methods in both small and large
population settings, with a 100-fold reduction in time. This
makes MultiMorph an accessible framework for biomedical
researchers without machine learning expertise, enabling
rapid, high-quality atlas generation for diverse studies.
```
