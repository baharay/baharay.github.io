---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Computer and Communication Sciences, École Polytechnique Fédérale de Lausanne (EPFL), Switzerland, 2018 - July 2024
  * Thesis: Visual Saliency Prediction for Natural Images, Comics Panels, and Comics Pages
* Bachelor of Science in Computer Engineering, Middle East Technical University (METU), Ankara, Turkey, 2013 - 2018 (CGPA: 3.92, Ranked 3rd out of 130)
* Izmir Science High School, İzmir, Turkey, 2009 - 2013 (GPA: 93.15 / 100)

Work experience
======
* September 2019 - July 2024: Research Assistant @ EPFL, Image and Visual Representation Lab
  * Developed a data augmentation technique for saliency prediction using latent diffusion
  * Incorporated temporal data into image saliency prediction
  * Modeled object appearance and size dissimilarities for saliency prediction

* September 2019 - July 2024: Project Supervision @ EPFL
  * Supervised projects including eye tracking, face detection, and temporal saliency estimation

* January 2019 - July 2024: Teaching Assistant @ EPFL
  * Proposed and supervised projects for Computational Photography
  * Conducted sessions for Introduction to Computation, Object-Oriented Programming, and Linear Algebra

* June 2017 - September 2017: Internship @ CERN
  * Created Python bindings for the C++ Data Access Library algorithms

* September 2017 - July 2018: Algorithmic Trading Project @ METU
  * Developed a web-based framework for designing and testing trading algorithms

* June 2016 - August 2016: Internship @ Turkish Aerospace Industries (TAI)
  * Implemented an auto-generated user interface in Groovy

* September 2016 - June 2017: Interdisciplinary Design Studio @ METU
  * Developed a body posture recognition and correction system for Autodesk

Skills
======
* Theory: Computer Vision, Machine Learning, Generative AI, Transfer Learning, Deep Learning Model Architectures (CNN, RNN, GAN, VAE), Transformers, Diffusion Models, Image Processing, Image Manipulation, Feature Extraction, Linear Algebra, Probability and Statistics
* Programming Languages: Python, C, C++, LaTeX, Java, SQL
* Software Packages: PyTorch, OpenCV, scikit-learn, pandas, NumPy, SciPy, Jupyter, Seaborn
* Deployment/Version Control: Conda, Docker, git, Kubernetes, Amazon Web Services (AWS)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

