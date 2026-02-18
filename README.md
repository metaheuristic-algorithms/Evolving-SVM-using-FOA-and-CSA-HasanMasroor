# Implementation and Enhancement of Evolving SVM using Fruit Fly Optimization and Clonal Selection Algorithm
This repository contains the final project for the Metaheuristic Optimization course. The project involves the implementation of a specialized classification model and explores potential enhancements by modifying its core optimization mechanism.

## 📌 Project Overview
The primary objective was to implement the research paper: "Evolving Support Vector Machines using Fruit Fly Optimization for Medical Data Classification ([ELSEVIER](https://www.sciencedirect.com/science/article/abs/pii/S0950705116000125))." The study focuses on optimizing two critical hyperparameters of the Support Vector Machine (SVM): $C$ and $\gamma$. To investigate performance improvements, the original model was modified by replacing the local search phase of the Fruit Fly Optimization Algorithm (FOA) with the Clonal Selection Algorithm (CSA), aiming for more robust convergence and higher classification accuracy.

## 🏛 Repository Structure
The project is organized into the following directories to facilitate easy review and reproducibility:

**📂 Article<br>**
Contains the original reference paper used as the foundation for the implementation and classroom presentations.

**📂 Datasets<br>**
Includes the medical datasets utilized for training and validating the classification models.

**📂 Implementation_FOA_SVM<br>**
The initial implementation of the research paper, featuring the standard Fruit Fly Optimization (FOA) for SVM parameter tuning.

**📂 Implementation_CSA_SVM<br>**
The enhanced version of the project. In this iteration, the local search phase of the FOA was replaced with the Clonal Selection Algorithm (CSA) to investigate its impact on model performance and optimization stability.

**📂 Presentation<br>**
Contains the slide decks and the full recorded presentation video covering the original paper’s methodology, the base implementation, and the subsequent enhancements. This section provides a detailed technical demonstration and a comprehensive walkthrough of the project's development phases, including initial research, implementation strategies, and a rigorous comparative analysis of the final results.

**📂Report<br>**
Includes the applied modifications and the revised version of the original research paper.

## 🛠 Contribution
This repository has been developed and maintained in fulfillment of the academic requirements for the Metaheuristic Optimization course. Its primary objective is to provide a transparent and reproducible framework for researchers and students interested in SVM hyperparameter tuning and evolutionary algorithms. Feedback and inquiries regarding the implementation are appreciated.
