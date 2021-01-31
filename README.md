
# Cloth-detection-system

### INTRODUCTION:
Object detection and location in digital images has become one of the most important applications for industries to ease user, save time and to achieve parallelism and one such is cloth detection system. This is not a new technique but improvement in cloth detection is still required in order to achieve the targeted objective more efficiently and accurately. The main aim to use  computer vision is to simulate the behavior and manner of human eyes directly by using a computer and later on develop a system that reduces human efforts. Computer vision is such kind of research field which tries to perceive and represents the 3D information for world objects. Its main purpose is reconstructing the visual aspects of 3D objects after analyzing the 2D information extracted. Real life 3D objects are represented by 2D images. The process of cloth detection analysis is to determine the number, location, size, position of the objects in the input image. Object detection is the basic concept for tracking and recognition of objects, which affects the efficiency and accuracy of object recognition such as the shoes ,dresses etc. in case of cloth recognition system
The goal of this project is to identify objects from a complex background image using various techniques. If, any particular algorithm predicts each and every pixel of an image to be its background, the IOU measure can effectively penalize for that, as the intersection between the predicted and ground-truth regions would be zero, it will produce an IOU count of zero. OpenCV library implemented in python2.7 along with the help of Numpy is used and the world of object detection is explored, a virtual Artificial Neural Network is created using Sci-kit tool. 
### CONCEPT:
Theory: Every object class has its own special features that help in classifying the object. cloth recognition is that sub-domain of computer vision which helps in identifying objects in an image or video sequence. With more efficient algorithms, objects can even be recognized even when they are partially obstructed from the direct view. Various approaches to this task have been implemented in the past years. Various terms related to object detection are: 
#### 1.	Edge matching:

     •	Uses edge detection techniques to find the edges
  
     •	  Effect of changes in lighting and color
  
     •	 Count the number of overlapping edges.
#### 2.	 Divide and Conquer search:

    •	All positions are to be considered as a set.
  
    •	The lower bound is determined at best position in the cell.  
    
    •	The cell is pruned if the bound is too large.
    
    •	The process stops when a cell becomes small enough.
    
#### 3.	Grayscale matching

     •	Edges give a lot of information being robust to illumination changes.
     
     •	Pixel distance is computed as a function of both pixel intensity and position. The same thing can compute with color too. 

### OBJECTIVE:

The cold-start problem is faced by most industries when trying to build a business from scratch. They have few or no users yet, but most industries when trying to build a business from scratch. They have few or no users yet, but still have to predict their interests to deliver a great customer experience. In fashion, it translates to being able to recommend clothes similar to the ones a customer looked at, liked o-r purchased. 
The visual aspects of clothes are the core information that influences customers behavior in fashion, often above price, brand and fabric, it makes sense to base the recommendation on the picture of a clothing item. However, clothes are often shown as part of outfits on models. In order to automatically extract visual features from a clothing items, it has to be isolated from the rest of the outfit on an image.

### FEASIBILITY STUDY:
#### 1.	Technical Feasibility:

The technology needed for the proposed system is available. We can work for the project on current equipment existing tools like python. We can develop this system still using this technology if needed to upgrade. In future, if we want to use new technology like android app of our system it is possible. Hence, the system that we are going to develop will successfully satisfy the needs of the system for technical feasibility.

#### 2.	Operational Feasibility:

The user interface will be user friendly and no training will be required to use the application. The solution proposed for our project is operationally workable and most likely convenient to solve the irrelevant document and fraud e-mail.

#### 3.	Economic Feasibility:

Since the system is developed as a part of project work, there is no manual cost to spend for the proposed system. Also, all the resources are already available, it gives an indication that the system is economically possible for development. The cost to conduct a full system investigation is negotiable because required information is collected from internet. We can run our system in our normal hardware like desktop, laptop mobiles and so on. Money to be developed so it will be economically feasible.

### SOFTWARE AND HARDWARE REQUIREMENT:

#### 1.	Software Requirements:

•	Anaconda (Python Distribution)

•	Python 3.5 or above

•	 Packages like numpy, opencv, pandas and scipy etc.

•	Pre-defined Dataset

•	Libraries

#### 2.	Hardware Requirements:

•	8GB RAM

•	i5 processor

### ABSTRACT :

Object detection is a well-known computer technology connected with computer vision and image processing that focuses on detecting objects or its instances of a certain class (such as humans, flowers, animals) in digital images and videos. There are various applications of object detection that have been well researched including face detection, character recognition, and vehicle calculator cloth detection. Object detection can be used for various purposes including retrieval and surveillance.  Various basic concepts used in object detection while making use of OpenCV library of python 2.7, improving the efficiency and accuracy of object detection are presented in the cloth detection system. The cloth recognition system can be used to recommend clothes to its customers and for better customer experience.


### METHODOLOGIES:

#### 1.	OpenCV:

Open Source Computer Vision is an open source computer vision and machine learning software library [. OpenCV was initially built to provide a common infrastructure for applications related to computer vision and to increase the use of machine perception in the commercial products. As it is a BSD-licensed product so it becomes easy for businesses to utilize and modify the existing code in OpenCV. Around 3000 algorithms are currently embedded inside OpenCV library, all these algorithms being efficiently optimized. It supports real-time vision applications. These algorithms are categorized under classic algorithms, state of art computer vision algorithms and machine learning algorithms. These algorithms are easily implemented in Java, MATLAB, Python, C, C++ etc. and are well supported by operating system like Window, Mac OS, Linux and Android. A full-featured CUDA and OpenCL interfaces are being actively developed for the betterment of technology. There are more than 500 different algorithms and even more such functions that compose or support those algorithms. OpenCV is written natively in C++ and has a templated interface that works seamlessly with STL containers. For OpenCV to work efficiently with python 2.7 we need to install NumPy package first.

#### 2.	NumPy:

NumPy is the fundamental package for scientific computing with Python. It can be treated as an extension of the Python programming language with support for multidimensional matrices and arrays. It is open source software with many contributors. 
It contains among other things:

•	A powerful N-dimensional array object.

•	Broadcasting functions.

•	Tools for integrating C/C++ and FORTRAN code.

•	Useful linear algebra, Fourier transform, and random number capabilities

•	Besides its obvious scientific uses, NumPy can also be used as an efficient multi-dimensional container of generic data.

#### 3.	Introduction to Python Programming Language:

The reason I’ll be using python for machine learning codes because Python is simple, elegant, consistent, and math-like. Python code has been described as readable pseudocode. It is easy to pick up due to its consistent syntax and the way it mirrors human language and/or their mathematical counterparts. Python has a huge set of libraries which can be easily used for machine learning (for e.g. NumPy, SciPy, Scikit Learn, Opencv, PyBrain etc). Python is one of the languages which can be used to write codes in Map-Reduce model while working in Hadoop Ecosystem.

#### 4.	 Introduction to Machine Learning:

Machine learning is a type of artificial intelligence (AI) that provides computers with the ability to learn without being explicitly programmed. Machine learning focuses on the development of Computer Programs that can change when exposed to new data. Machine learning involves computer to get trained using a given data set, and use this training to predict the properties of a given new data.

#### 5.	Logistic Regression (LR):

Logistic regression is a type of probabilistic statistical classification model for analyzing a
dataset in which there are one or more independent variables that determine an outcome.
In logistic regression, the dependent variable is binary or dichotomous, that means it only
contains data coded as 1 (TRUE, success, etc.) or 0 (FALSE, failure, etc.).



### Challenges:

The main purpose is to recognize a specific object in real time from a large number of objects. Most detection systems are poorly scalable with many recognizable objects. Computational cost rises as the number of objects increases. Comparing and querying images using color, texture, and shape are not enough because two objects might have same attributes. Designing a cloth detection system with abilities to work in the dynamic environment and behave like a human is difficult. Some main challenges to design cloth detection system are lighting, dynamic background, color of the object, the presence of shadow, the motion of the camera, the speed of the moving objects, and intermittent object motion weather conditions etc.

### Conclusion:

The possibilities of using computer vision to solve real world problems are immense. The basics of object detection along with various ways of achieving it and its scope has been discussed. Python has been preferred over MATLAB for integrating with OpenCV because when a Matlab program is run on a computer, it gets busy trying to interpret all that Matlab code as Matlab code is built on Java. OpenCV is basically a library of functions written in C\C++. Additionally, OpenCV is easier to use for someone with little programming background. So, it is better to start  cloth detection system using OpenCV-Python. Feature understanding and matching are the major steps in cloth detection system and should be performed well and with high accuracy. 

### APPLICATIONS AND FUTURE SCOPE:

Computer vision is still a developing discipline, it has not been matured to that level where it can be applied directly to real life problems.  We can consider object detection as a sub-branch of machine learning. Some common and widely used application of cloth detection sytem are:
#### 1.	Counting peoples:

Object detection can be also used for counting purpose, it is used for keeping a count of particular or all objects in an image or a frame. For e.g. from a group photograph it can count the number of persons and if implemented smartly you may also find out different people with different dresses.
#### 2.	Industries:

Object detection is also used in industrial processes for the identification of different products. Say WE want THE machine to only detect objects of a particular shape, you can achieve it very easily. For e.g. Hough circle detection transform [6] can be used for detecting circular objects.
#### 3.	Surveillance:

 Suspicious people can be recognized and tracked in videos for security purpose. Cloth detection is required so that the suspected person  can be tracked.

### References:

Latharani T.R., M.Z. Kurian, Chidananda Murthy M.V,“Various Object Recognition Techniques For Computer Vision”, Journal of Analysis and Computation, ISSN: 0973-2861.
Nidhi, “Image Processing and Object Detection”, Dept. of Computer Applications, NIT, Kurukshetra, Haryana, 1(9): 396-399, 2015.(2017, January 17). 
