---
title: "Data Augmentation via Latent Diffusion for Saliency Prediction"
collection: publications
permalink /publication/2024-10-10-augsal
excerpt: 'We propose a novel data augmentation method for deep saliency prediction that edits natural images while preserving the complexity and variability of real-world scenes.'
date: 2024-11-10
venue: 'Proceedings of the European Conference on Computer Vision'
slidesurl: 'http://academicpages.github.io/files/slides1.pdf'  # Replace with actual URL if available
paperurl: 'http://academicpages.github.io/files/paper1.pdf'    # Replace with actual URL if available
citation: 'Bahar Aydemir, Deblina Bhattacharjee, Tong Zhang, Mathieu Salzmann, Sabine Süsstrunk. (2024). &quot;Data Augmentation via Latent Diffusion for Saliency Prediction.&quot; <i> European Conference on Computer Vision (ECCV)</i>.'
---

Saliency prediction models are constrained by the limited diversity and quantity of labeled data. Standard data augmentation techniques such as rotating and cropping alter scene composition, affecting saliency. We propose a novel data augmentation method for deep saliency prediction that edits natural images while preserving the complexity and variability of real-world scenes. Since saliency depends on high-level and low-level features, our approach involves learning both by incorporating photometric and semantic attributes such as color, contrast, brightness, and class. To that end, we introduce a saliency-guided cross-attention mechanism that enables targeted edits on the photometric properties, thereby enhancing saliency within specific image regions. Experimental results show that our data augmentation method consistently improves the performance of various saliency models. Moreover, leveraging the augmentation features for saliency prediction yields superior performance on publicly available saliency benchmarks. Our predictions align closely with human visual attention patterns in the edited images, as validated by a user study.
