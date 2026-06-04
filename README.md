## Abstract

Remote sensing semantic segmentation plays a vital role in land cover mapping, urban planning, environmental monitoring, and disaster management.
Traditional segmentation methods often rely on a single data source, limiting their ability to capture comprehensive scene information.
This project proposes a Vision Foundation Model Guided Multi-Modal Fusion framework that combines optical and Synthetic Aperture Radar (SAR) imagery to improve segmentation performance.
A pre-trained Vision Foundation Model extracts rich semantic features from remote sensing images, while a fusion module integrates complementary information from multiple modalities. 
The fused features are then processed by a semantic segmentation network to generate accurate pixel-level classifications. 
Experimental results demonstrate improved segmentation accuracy, robustness, and generalization compared to single-modal approaches.

## Introduction 
Remote sensing imagery provides valuable information for understanding Earth's surface.
Semantic segmentation aims to classify every pixel in an image into meaningful categories such as buildings, roads, vegetation, water bodies, and barren land.
However, optical images are often affected by weather conditions and illumination variations, while SAR images contain noise but offer structural information under all-weather conditions.

Vision Foundation Models have recently achieved remarkable success in extracting high-level semantic representations from visual data. 
By leveraging these models and integrating information from multiple sensing modalities, it is possible to enhance segmentation accuracy and robustness.
This project focuses on developing a Vision Foundation Model-guided multi-modal fusion framework for remote sensing semantic segmentation.
