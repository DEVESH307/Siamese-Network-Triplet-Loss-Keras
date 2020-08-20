# Siamese-Network-Triplet-Loss-Keras
## Welcome!
Welcome to **Siamese Network with Triplet Loss in Keras**. 
A **Siamese neural network** (sometimes called a **twin neural network**) is an artificial neural network that uses the same weights while working in tandem on two different input vectors to compute comparable output vectors. Often one of the output vectors is precomputed, thus forming a baseline against which the other output vector is compared. This is similar to comparing fingerprints but can be described more technically as a distance function for locality-sensitive hashing.
It is possible to make a kind of structure that is functional similar to a siamese network, but implements a slightly different function. This is typically used for comparing similar instances in different type sets.
Uses of similarity measures where a twin network might be used are such things as recognizing handwritten checks, automatic detection of faces in camera images, and matching queries with indexed documents. The perhaps most well-known application of twin networks are [face recognition](https://en.wikipedia.org/wiki/Facial_recognition_system), where known images of people are precomputed and compared to an image from a turnstile or similar. It is not obvious at first, but there are two slightly different problems. One is recognizing a person among a large number of other persons, that is the facial recognition problem. [DeepFace](https://en.wikipedia.org/wiki/DeepFace) is an example of such a system. In its most extreme form this is recognizing a single person at a train station or airport. The other is face verification, that is to verify whether the photo in a pass is the same as the person claiming he or she is the same person. The twin network might be the same, but the implementation can be quite different.

## Project Objectives
In this Project, we are going to focus on three learning objectives:
1. Implement a Siamese Network.
2. Implement a Triplet Loss Function.
3. Train a Siamese Network with Triplet Loss.

By the end of this Project, We will be able to implement a Triplet Loss function, create a Siamese Network, and train the network with the Triplet Loss function.

## Project Structure
The hands on project on **Siamese Network with Triplet Loss** in Keras is divided into following tasks:
### Task 1: Understanding the Approach
- Importing the Libraries and Helper Functions.
- Understanding the approach with an example.
- Siamese Network.

### Task 2: Importing the Data
- Importing the MNIST Dataset.
- Reshaping and Normalizing the Examples.

### Task 3: Plotting Examples
- Creating a function to plot triplets.

### Task 4: Batch of Triplets
- Creating a function to generate triplet examples.
- Testing the function.

### Task 5: Embedding Model
- Creating an Embedding Model, this is a simple Neural Network.
- Taking a look at generated Embedding for an image.

### Task 6: Siamese Network
- Using the Embedding Model to create a Siamese Network.

### Task 7: Triplet Loss
- Implementing the Triplet Loss function.
- Implementing the custom loss function.

### Task 8: Model Training
- Creating a small test set.
- Compiling the Siamese Network with Triplet Loss.
- Training the Siamese Network.