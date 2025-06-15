---
layout: page
title: Research
permalink: /research/
image: 
description: Presentation of the research areas and ongoing research projects of the AI Technology and Application Research Lab at the FPT University, Ho Chi Minh Campus
toc: true
toc_sticky: true
toc_label: "Table of Contents"
---

<!-- > Graphs illustrate intricate patterns in our perception of the world and ourselves; graph mining enhances this comprehension by highlighting overlooked details. -->

***

<h5>Table of Contents</h5>
* TOC
{:toc}

***
# Medical image segmentation
This research proposal aims to explore distributed learning in healthcare by comparing the performance and security of Federated Learning, Split Learning, and SplitFed Learning methods on 3D liver images using the LiTS dataset. The study will focus on applying these distributed learning techniques to segmentation models, particularly those based on U-Net architecture, and evaluate their effectiveness in terms of accuracy, privacy preservation, and communication efficiency. The expected outcomes include theoretical insights, methodological frameworks, and practical applications that could enhance patient data management and expand the use of distributed learning in medical image analysis beyond liver segmentation.

# Speech emotion recognition
This research proposal outlines a study aimed at enhancing Speech Emotion Recognition (SER) through the integration of multi-feature fusion and a Graph-LSTM architecture. The researchers plan to combine diverse acoustic and linguistic features to create a comprehensive representation of emotional expressions in speech, leveraging Graph Neural Networks to model complex relationships between emotional cues and Long Short-Term Memory networks to capture temporal dependencies. The expected outcomes include improved accuracy and robustness in SER, enhanced interpretability of the model, and a more comprehensive representation of emotional cues in speech.

# Handwritten mathematical expressions recognition
This research proposal outlines a study on Handwritten Mathematical Expressions (HME) Recognition, aiming to improve structural analysis for enhanced recognition accuracy. The project focuses on addressing challenges in understanding hierarchical and spatial relationships between mathematical symbols using deep learning techniques. Two main approaches are proposed: direct feature extraction from images and a two-step process involving symbol detection and spatial relationship analysis. The study aims to develop a robust structural analysis model that outperforms current baselines in recognizing complex and nested mathematical structures across various handwriting styles.

# Quantum machine learning
Quantum machine learning is an emerging field that combines quantum computing with machine learning to potentially solve complex problems more efficiently than classical methods. By harnessing quantum properties such as superposition, entanglement, and quantum tunneling, QML aims to enhance tasks like data analysis, optimization, and pattern recognition. The field explores algorithms that can leverage quantum advantages, categorized into areas like quantum-enhanced classical algorithms, feature selection, data classification, optimization, generative models, and dimensionality reduction.

# Vietnamese traffic sign recognition
This study presents an approach to Vietnamese traffic sign recognition designed for the IOT device, utilizing the YOLOv8 Nano model to achieve real-time performance. The researchers introduce a new dataset called VTSDB100, which includes 100 different classes of traffic signs captured in diverse locations within Ho Chi Minh City, Vietnam. The researchers conduct experiments using various object detection methods on the VTSDB100 dataset, including YOLOv8, YOLOv9, YOLOv10, YOLOX, RetinaNet, and Faster R-CNN. The paper also describes techniques for deploying deep learning models on resource-constrained devices, such as using TensorRT and quantization to optimize inference speed. Finally, the authors propose a workflow for a real-time traffic sign recognition system on the Jetson Nano 2GB, which includes object detection, tracking, and a class filter algorithm to minimize false predictions.

# Distributed and Adaptive Machine Learning
Distributed and Adaptive Machine Learning, including federated learning, split learning, active learning, and curriculum learning, aims to enhance efficiency, privacy, and adaptability in model training. Federated learning enables distributed model training across multiple clients, where local data remains private and only model updates are aggregated centrally to create a global model on the server. Split learning, another privacy-preserving technique, divides a neural network between a client and a server: the client processes the initial layers using local data and sends intermediate outputs to the server for further computation, reducing raw data exposure. Active learning optimizes learning efficiency in semi-supervised settings by initially training with minimal labeled data and then having the model iteratively select the most informative unlabeled data points for human annotation. Curriculum learning improves training by presenting data in a sequence from simpler to more complex examples, thereby accelerating convergence and enhancing model performance. 


# Spiking Neural Networks
Spiking Neural Networks (SNNs) are a type of artificial neural network inspired by the brain's biological neurons, processing information using discrete spikes or events rather than continuous values. Research on SNNs focuses on their energy efficiency, biological plausibility, and ability to handle temporal data, making them suitable for neuromorphic computing and tasks like pattern recognition, sensory processing, and real-time decision-making. Key topics include developing efficient training algorithms, optimizing hardware implementations, and exploring applications in robotics, IoT, and brain-machine interfaces.