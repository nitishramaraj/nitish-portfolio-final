---
title: "Patient Medical Report Analyser A Multi-Stage Workflow"


# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Nitish Ramaraj
- Girish Murugan
- Tejas Anil
- Dr. Vetriselvi T
- Dr. Jagadeesan S

# Author notes (optional)
author_notes:
- "First Author"

date: "2024-10-17T00:00:00Z"
# doi: "10.21105/joss.02664"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-10-17T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Taylor and Francis Journal*
publication_short: In *T&F*

abstract: "This work presents an advanced automated system designed to streamline the processing of medical prescriptions. The system 
follows a multi-stage workflow aimed at enhancing efficiency in handling and interpreting prescription data. The process begins when a user 
uploads a prescription image, which is then subjected to a series of sophisticated image processing techniques, including grayscale conversion, 
noise reduction, and morphological operations. These steps are crucial for improving the readability of the text within the image, ensuring that 
the subsequent stages operate on high-quality data. Once the image is processed, an Optical Character Recognition (OCR) module is employed 
to extract text from the image. The OCR process involves text region detection, segmentation of lines and characters, and the application of 
algorithms to recognize and transcribe the text accurately. Following OCR, the extracted text is further refined using language modeling 
techniques, which involve spell checking, error correction, and the recognition of key entities such as medication names and dosages. To 
provide meaningful insights, a large language model (LLM) is used to generate a concise and coherent summary of the prescription. This 
summary distills the essential information from the prescription, making it easier for healthcare professionals and patients to understand and 
manage the prescribed treatments. The final summary is then returned to the user, completing a seamless, end-to-end process that automates 
the traditionally manual and error-prone task of interpreting medical prescriptions. This system has significant potential for integration into 
healthcare management systems, offering a scalable solution for improving prescription processing and patient care. "

# Summary. An optional shortened abstract.
summary: 

tags: [Medical Prescription Processing, Optical Character Recognition (OCR), Image Processing, Large Language Models (LLM), Text Extraction, Language Modeling, Healthcare Automation]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: ''
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - nas-paper

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
