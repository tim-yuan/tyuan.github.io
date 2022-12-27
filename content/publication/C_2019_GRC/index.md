---
title: 'Rigid Seeding: A computationally efficient method to study heterogeneous nucleation in molecular simulations'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Ryan DeFever
  - Sapna Sarupria

## Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'
#
date: '2019-06-22T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
#publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Gordon Research Conference Crystal Growth and Assembly*
#publication_short: In **


abstract: Nucleation is the primary step towards crystallization and is significantly difficult to study in both experiments and simulations. The length and timescale resolution required to observe nucleation is difficult to access in experiments. In simulations, although the length and timescales are well-suited, the sampling required to get statistically relevant nucleation events is computationally prohibitive. Thus, novel methods are required that can enable us to study nucleation in molecular simulations in an efficient manner.  
  
  

  We present a computationally efficient method called Rigid Seeding (RSeed) to study heterogeneous nucleation. Heterogeneous nucleation refers to nucleation that occurs in the presence of a foreign particle (i.e. a surface). This methodology builds on the seeding method but enables accounting for the role of surface in determining the crystal structure that is nucleated on the surface. Briefly, in the RSeed method we place a rigid crystal seed on the surface and allow it to relax. During this process, the crystal seed is able to translate and rotate which enables the seed to identify the favorable seed- surface configuration.   
  

  We demonstrate the method through studies of heterogeneous ice nucleation. It has been shown that various polymorphs if ice such as hexagonal and cubic can form on surfaces and there is no obvious method to predict this. We study two surfaces, e.g., a flexible self-assembled monolayer (SAM) with COOH terminal group and a modified mineral kaolinite surface (kao m ). Using RSeed and all atom simulation we determine the ice nucleating behavior of each surface. We find that RSeed method is able to identify the ice polymorph, plane, and rotation of the ice structure that grows on both surfaces. The results are in good agreement with the nucleation trajectories from straightforward MD. We also use the RSeed method to extract the critical nucleus size on kao m surface and calculate the rate of nucleation by extending the classical nucleation theory (CNT) to heterogeneous case. The rate calculated using straightforward MD is within the error bars of the rate predicted by heterogeneous CNT. This technique enables us to study ice nucleation on a broad range of surfaces and thus, elucidate the correlations between surface properties and its ice nucleating efficiency. RSeed method is broadly applicable and can be used to study heterogeneous nucleation in a variety of systems.


## Summary. An optional shortened abstract.
summary: Rigid Seeding A computationally efficient method to study heterogeneous nucleation in molecular simulations

#
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

#url_pdf: ''
#url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_video: 'https://youtube.com'

## Featured image
## To use, add an image named `featured.jpg/png` to your page's folder.
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ''
#  preview_only: false
#
## Associated Projects (optional).
##   Associate this publication with one or more of your projects.
##   Simply enter your project's folder or file name without extension.
##   E.g. `internal-project` references `content/project/internal-project/index.md`.
##   Otherwise, set `projects: []`.
#projects:
#  - example
#
## Slides (optional).
##   Associate this publication with Markdown slides.
##   Simply enter your slide deck's filename without extension.
##   E.g. `slides: "example"` references `content/slides/example/index.md`.
##   Otherwise, set `slides: ""`.
#slides: example
---

