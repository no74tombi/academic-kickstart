---
title: "Image recognition using multi-layer sparse feature extraction with ADMM"
authors:
- admin
- Kuntopng Wararatpanya
- Yoshimitsu Kuroki

# date: "2020-2-19 17:11:42"
doi: "10.1117/12.2521348"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
# publication: "*Journal of Source Themes, 1*(1)"
# publication_short: ""

# Summary. An optional shortened abstract.
# summary: Best Student Paper Award

#tags:
#- Source Themes
#featured: false

# links:
# - name: ""
#   url: ""
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#  focal_point: ""
#  preview_only: false
abstract: "Being motivated by the Saak (Subspace approximation with augmented kernels) transform, we propose an image recognition scheme using multi-layer sparse feature extraction with a convex solver ADMM (Alternating Direction Method of Multipliers). The Saak transform consists of a multi-layer PCA (Principal Component Analysis) and S/P (Sign-to-Position) conversion to avoid sign confusion. This paper adopts sparse representation instead of PCA and also compares the S/P conversion with the activation function ReLU (Rectified Linear Unit), which is realized by involving the projection mapping onto the non-negative set in convex formulas. The Saak transform uses PCA not only for feature extraction but also for dimension compression of feature vectors. We expect that our method does not need the dimension compression since sparse representation compresses features more than PCA. Experimental results on the MNIST and Fashion-MNIST dataset show that the proposed method is equivalent to the Saak transform in recognition accuracy, and that our method can make features more sparse and extract features that have high discriminant power locally."
# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% alert note %}}
Click the *Cite* button to import publication metadata into your reference management software.
{{% /alert %}}