---
title: "Distributed compressed hyper spectral image sensing using ADMM"
authors:
- admin
- Kazuki Chigita
- Yoshimitsu Kuroki

# date: "2020-2-19 17:11:42"
doi: "10.1109/IWAIT.2018.8369758"

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
abstract: "This paper describes a distributed compressed sensing method of HSI (Hyper Spectral Image). Similar to conventional methods, our method transfers computational load from encoder to decoder, and divides images into key and non-key frames. In video coding schemes, decoders interpolate non-key frames using motion vector or optical flow referring decoded key frames. However, the adjacent frames in wavelength domain have strong correlation at the same spacial positions. The PNSR of interpolated non-key frames would be high; then, our method applies ADMM (Alternating Direction Method of Multipliers) not only to reconstruct key and non-key frames but also to design the dictionaries of non-key frames. Experimental results show that the PSNR values of our method are about 3 to 5 dB higher than those of the method using DCT (Discrete Cosine Transform) for the dictionaries."
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