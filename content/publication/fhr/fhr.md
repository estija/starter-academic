---
title: "Efficient Implementation of LMS Adaptive Filter-based FECG Extraction on an FPGA"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Bhavya Vasudeva
- Puneesh Deora
- Pyari Mohan Pradhan
- Sudeb Dasgupta

# Author notes (optional)
author_notes: ""

date: "2020-11-13"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-11-13"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: IET Healthcare Technology Letters
publication_short: 

abstract: In this Letter, the field programmable gate array (FPGA) implementation of a foetal heart rate (FHR) monitoring system is presented. The system comprises a preprocessing unit to remove various types of noise, followed by a foetal electrocardiogram (FECG) extraction unit and an FHR detection unit. To improve the precision and accuracy of the arithmetic operations, a floating-point unit is developed. A least mean squares algorithm-based adaptive filter (LMS-AF) is used for FECG extraction. Two different architectures, namely series and parallel, are proposed for the LMS-AF, with the series architecture targeting lower utilisation of hardware resources, and the parallel architecture enabling less convergence time and lower power consumption. The results show that it effectively detects the R peaks in the extracted FECG with a sensitivity of 95.74-100% and a specificity of 100%. The parallel architecture shows up to an 85.88% reduction in the convergence time for non-invasive FECG databases while the series architecture shows a 27.41% reduction in the number of flip flops used when compared with the existing FPGA implementations of various FECG extraction methods. It also shows an increase of 2-7.51% in accuracy when compared to previous works.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://digital-library.theiet.org/deliver/fulltext/htl/7/5/HTL.2020.0016.pdf;jsessionid=2cwha55ntv5lx.x-iet-live-01?itemId=/content/journals/10.1049/htl.2020.0016&mimeType=pdf&isFastTrackArticle='
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

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
slides: ""
---



