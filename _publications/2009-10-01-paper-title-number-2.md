---
title: "Modeling Object Dissimilarity for Deep Saliency Prediction"
collection: publications
permalink: /publication/2023-07-10-dissimsal
excerpt: 'This paper introduces a novel saliency prediction model that learns to output saliency maps in sequential time intervals by exploiting human temporal attention patterns.'
date: 2022-11-10
venue: 'Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition'
slidesurl: 'http://academicpages.github.io/files/slides1.pdf'  # Replace with actual URL if available
paperurl: 'http://academicpages.github.io/files/paper1.pdf'    # Replace with actual URL if available
citation: 'Bahar Aydemir, Deblina Bhattacharjee, Tong Zhang, Seungryong Kim, Mathieu Salzmann, Sabine Süsstrunk. (2022). &quot;TModeling Object Dissimilarity for Deep Saliency Prediction.&quot; <i>Transactions on Machine Learning Research (TMLR)</i>.'
---

Saliency prediction has made great strides over the past two decades, with current techniques modeling low-level information, such as color, intensity and size contrasts, and high-level ones, such as attention and gaze direction for entire objects. Despite this, these methods fail to account for the dissimilarity between objects, which affects human visual attention. In this paper, we introduce a detection-guided saliency prediction network that explicitly models the differences between multiple objects, such as their appearance and size dissimilarities. Our approach allows us to fuse our object dissimilarities with features extracted by any deep saliency prediction network. As evidenced by our experiments, this consistently boosts the accuracy of the baseline networks, enabling us to outperform the state-of-the-art models on three saliency benchmarks, namely SALICON, MIT300 and CAT2000.