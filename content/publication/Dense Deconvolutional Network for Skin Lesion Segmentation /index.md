---
title: "An example conference paper"
authors:
- admin
date: "2013-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Journal of Biomedical and Health Informatics*
publication_short: In *JBHI*

abstract: Automatic delineation of skin lesion contours from dermoscopy images is a basic step in the process of diagnosis and treatment of skin lesions. However, it is a challenging task due to the high variation of appearances and sizes of skin lesions. In order to deal with such challenges, we propose a new dense deconvolutional network (DDN) for skin lesion segmentation based on residual learning. Specifically, the proposed network consists of dense deconvolutional layers (DDLs), chained residual pooling (CRP), and hierarchical supervision (HS). First, unlike traditional deconvolutional layers, DDLs are adopted to maintain the dimensions of the input and output images unchanged. The DDNs are trained in an end-to-end manner without the need of prior knowledge or complicated postprocessing procedures. Second, the CRP aims to capture rich contextual background information and to fuse multilevel features. By combining the local and global contextual information via multilevel feature fusion, the high-resolution prediction output is obtained. Third, HS is added to serve as an auxiliary loss and to refine the prediction mask. Extensive experiments based on the public ISBI 2016 and 2017 skin lesion challenge datasets demonstrate the superior segmentation results of our proposed method over the state-of-the-art methods.

tags:
- Source Themes
featured: true

links:
url_pdf: https://ieeexplore-ieee-org.ezproxy.cul.columbia.edu/stamp/stamp.jsp?tp=&arnumber=8419237

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).

