---
title: "TempSAL - Uncovering Temporal Information for Deep Saliency Prediction"
collection: publications
permalink: /publication/2023-07-10-tempsal
excerpt: 'This paper introduces a novel saliency prediction model that learns to output saliency maps in sequential time intervals by exploiting human temporal attention patterns.'
date: 2023-07-10
venue: 'Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition'
slidesurl: 'http://academicpages.github.io/files/slides1.pdf'  # Replace with actual URL if available
paperurl: 'http://academicpages.github.io/files/paper1.pdf'    # Replace with actual URL if available
citation: 'Bahar Aydemir, Ludo Hoffstetter, Tong Zhang, Mathieu Salzmann, Sabine Süsstrunk. (2023). &quot;TempSAL - Uncovering Temporal Information for Deep Saliency Prediction.&quot; <i>Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition</i>. 6461-6470.'
---

Deep saliency prediction algorithms complement the object recognition features; they typically rely on additional information such as scene context, semantic relationships, gaze direction, and object dissimilarity. However, none of these models consider the temporal nature of gaze shifts during image observation. We introduce a novel saliency prediction model that learns to output saliency maps in sequential time intervals by exploiting human temporal attention patterns. Our approach locally modulates the saliency predictions by combining the learned temporal maps. Our experiments show that our method outperforms the state-of-the-art models, including a multi-duration saliency model, on the SALICON benchmark and CodeCharts1k dataset. Our code is publicly available on GitHub.
