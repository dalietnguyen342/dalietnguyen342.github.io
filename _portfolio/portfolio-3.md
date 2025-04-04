---
title: "Real-time Multi-Object Tracking in UAV Videos (KSE2024)"
collection: portfolio
excerpt: "Technologies: Apache Kafka, Apache Spark, Python, PyTorch, Docker, GPU Optimization"
---

System have been published and presented as a paper at KSE2025 Conference (RAMOTS: A Real-Time System for Aerial Multi-Object Tracking based on Deep Learning and Big Data Technology
). [GITHUB](https://github.com/NhiNguyen34/uav-detection)


## Overview

<img width="764" alt="image" src="https://github.com/user-attachments/assets/121b00dc-790c-4999-8656-6f2dd210f61b" />

Developed a real-time multi-object tracking system tailored for UAV (Unmanned Aerial Vehicle) videos, addressing unique challenges such as dynamic aerial scenes, low resolution, and fast-moving objects. The project seamlessly integrates scalable data engineering pipelines with advanced data analysis and deep learning models to deliver a robust, real-time solution.

## Technologies & Tools

-   **Data Engineering:** Apache Kafka, Apache Spark
-   **Programming & Scripting:** Python
-   **Deep Learning Frameworks:** YOLOv8, YOLOv10, ByteTrack
-   **Hardware:** Single GPU (maintaining 28 FPS for real-time processing)

## Data Engineering Pipeline

### Scalable Data Ingestion:

-   Utilized Apache Kafka to ingest high-volume UAV video streams, ensuring fault-tolerant, reliable, and real-time data delivery from multiple sources.

### Distributed Processing:

-   Employed Apache Spark to perform distributed and parallel processing of the streaming video data, enabling efficient ETL (Extract, Transform, Load) operations and rapid data transformation.

### ETL & Data Preparation:

-   Designed and implemented comprehensive ETL processes to standardize and pre-process video frames, ensuring that downstream analysis receives data in the correct format and adheres to strict data quality standards.

### System Integration:

-   Integrated the data pipeline with deep learning modules to create a unified framework that allows seamless transition from data ingestion to model inference.

## Data Analysis & Deep Learning Integration

### Object Detection & Tracking Models:

-   Integrated state-of-the-art deep learning models, including YOLOv8/YOLOv10 for accurate object detection and ByteTrack for robust multi-object tracking.

### Real-Time Analytical Solutions:

-   The system processes video streams in real time, achieving a processing speed of 28 FPS on a single GPU, which is critical for real-time situational awareness in UAV applications.

### Performance Metrics:

-   HOTA (Higher Order Tracking Accuracy): 48.14 on the Visdrone2019 benchmark
-   MOTA (Multi-Object Tracking Accuracy): 43.51 on the Visdrone2019 benchmark

### Actionable Insights:

-   The integration of deep learning and big data technologies enables the extraction of valuable insights from aerial video data, supporting further analytics and informed decision-making.

## Conclusion

This project demonstrates the power of combining scalable data engineering techniques with advanced data analysis and deep learning methods. By leveraging Apache Kafka and Apache Spark for efficient data processing, the system is able to ingest, transform, and analyze UAV video streams in real time. The integration with cutting-edge deep learning models not only meets the challenging requirements of multi-object tracking in aerial scenarios but also delivers high-performance tracking metrics, making it a practical solution for real-world applications.
