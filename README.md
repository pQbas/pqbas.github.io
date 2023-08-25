# Machine Learning Engeenier Portfolio

**Technical Skills: Python, Pytorch, TF, NLPs, AWS**

**Personal Skills: Adaptability, Active Listening, Collaborative Problem Solving, Open-mindedness, Willingness to Share, Task Delegation**

## 1. Profile Description
I have experience with programming languages python, matlab, C++ in applications related to Robotics, Artificial Vision and IoT. My interests are focused in artificial intelligence, robotics and academic research.

---
## 2. Education
- B.S., Electronic Eng. | Universidad Privada Antenor Orrego (_July 2023_)

---
## 3. Experience
**Research assistant @ Multidisciplinary Research Laboratory (_September 2021 - July 2023_)**
- Identify requirements of the current robotics project and propose strategies which involve DL/ML methods.
- Perform data labeling over data recollected via online or during field visits.
- Implement DL/ML models using Python, PyTorch, TensorFlow.
- Train and test DL/ML models employing platforms such as Google-Colab, Gradient.
- Writing and present reports at each stage of the project.


**Leader Student (_March 2022 - July 2022_) @ Universidad Privada Antenor Orrego, Trujillo, Peru** 
- Attentively understanding student concerns, queries, and feedback during tutoring sessions.
- Regularly seeking feedback to continuously improve teaching methods and approaches.
- Organizing open discussion sessions where students could freely share their insights and knowledge.


**Freelancer (_March 2023 - July 2023_) @ Project: SignatureMatching** 
- Development of a DL strategy to identify the similarity of two signatures.
- Deployment on AWS platform using SageMaker and Lambda functions services.


----
## 4. Projects

<!-- #### Development and implementation of a robotic system to carry out an efficient and continuous quality control on seedlings grown in Industrial Nurseries in La Libertad - Peru (_Match 2019 - June 2021_) -->

### IIoT system for monitoring and analysis of the transplanting process of the artichoke seedling

[Publication](https://doi.org/10.1109/ANDESCON56260.2022.9989611)

This project involved enhancing a computer vision system and its IIoT platform to assist a cartesian robot in transplanting artichoke seedlings and ensuring quality control. Key enhancements included:

- Improving portability and security by encapsulating the IIoT application, which processes images and detects seedlings, within an Ubuntu 18.04 Desktop virtual machine.
- Extending a software module's functionality to communicate between local and external servers.
- Deploying the IIoT application on an external web server via the FRED service for better transplanting process oversight regardless of the monitor's location.
- Acquiring transplanting data through a database connection, and analyzing average transplantation times over two days.

**Technologies Used:** Ubuntu 18.04 Desktop virtual machine, IIoT platform, FRED service, computer vision system, database connection.



<!-- #### Robotic system for efficient and continuous quality control of the growth of industrial nursery seedlings in the La Libertad region of Peru (_March 2021 - August 2023_) -->
### Detection and Classification of ventura-blueberries in five levels of ripeness from images taken during pre-harvest stage using Deep Learning techniques

[Publication](https://doi.org/10.1109/ANDESCON56260.2022.9989578)

In this project is introduced a method to detect and classify blueberries' ripeness levels in an agro-industrial farm, leveraging the Mask R-CNN and a custom convolutional neural network (CNN). Key steps include:

- Creation of a dataset for training and validation.
- Manual generation of masks for blueberries in images to label them based on five ripeness stages.
- Implementation of two deep learning models for blueberry detection and ripeness classification.
- Attainment of a 90.74% accuracy rate in the blueberry classification task with the proposed models.

**Technologies Used:** Mask R-CNN, convolutional neural network (CNN), Python, OpeCV

<!-- #### Development and implementation of a Multifunctional Automated Machine for the Sowing of Seeds of Different Sizes in multi-cell trays and Pealing of Seedlings according to the quality of Growth in Nurseries of the La Libertad Region-Peru (_March 2023 - December 2023_) -->

### Deep Learning-based Segmentation and Classification System for Artichoke Seedling Grading

This project presents an innovative solution for automated grading of artichoke seedlings, a pivotal step in the transplantation workflow.

- Acquisition of seedling images from vertical and horizontal viewpoints using depth cameras.
- Segmentation of these images to extract morphological attributes: width, height, and leaf area.
- Deployment of two deep learning models, Mask R-CNN and YOLOv8, for the tasks of detection and instance segmentation.
- Development of a Multi-Layer Perceptron (MLP) which classified seedlings into good or not good categories with an accuracy of 85.19% after being trained with specific parameters.

**Technologies Used:** Depth cameras, Mask R-CNN, YOLOv8, Multi-Layer Perceptron (MLP).


### Machine Learning Models Review 
[Repository](https://github.com/pQbas/Machine-Learning-Models-Review.git)

This repository is dedicated to the implementation of state-of-the-art Deep Learning models using the robust PyTorch framework. The emphasis is on both Image Classification and Semantic Segmentation tasks. The models are implemented from scratch and are tested on widely recognized datasets for consistency and performance benchmarking.

**Technologies Used:** supervised learning, image classification, semantic segmentation


### SignatureMatching 
<!-- [Repository](https://github.com/pQbas/SignatureMatcher.git) -->

In this repository, we embark on the journey of capturing the essence of visual signs using a convolutional encoder. The primary objective is to extract significant features that can discern between signs and determine if they are identical, i.e. the similarity between two images with signatures. The unique approach taken here lies in leveraging a semi-supervised learning methodology, bridging the gap between labeled and unlabeled data, ultimately aiming for a more generalized and robust feature representation.

**Technologies Used:** semi-supervised learning, convolutional encoder, similarity

---

## 6. Publications

- P. Cubas, J. Alva, S. Prado. “IIoT system for monitoring and analysis of the transplanting process of the artichoke seedling”. 2022 IEEE ANDESCON. https://doi.org/10.1109/ANDESCON56260.2022.9989611

- P. Cubas, E. Fiestas, S. Prado. “Detection and Classification of ventura-blueberries in five levels of ripeness from images taken during pre-harvest stage using Deep Learning techniques”. 2022 IEEE ANDESCON. https://doi.org/10.1109/ANDESCON56260.2022.9989578