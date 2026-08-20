# KNN From Scratch

## 📌 Project Overview
User defined KNN 
This project is a simple implementation of the **K-Nearest Neighbors (KNN) Classification algorithm from scratch using Python**.

Instead of using a ready-made KNN classifier, the program manually calculates distances, sorts the data points, selects the nearest neighbors, and performs voting to determine the classification.

## 🎯 Objective

The main objective of this project is to understand how the KNN classification algorithm works internally.

## 🔄 How It Works

```text
Input Data Points
       ↓
Calculate Euclidean Distance
       ↓
Sort Points by Distance
       ↓
Select K Nearest Neighbors
       ↓
Voting
       ↓
Classification Result
```

## 🧠 KNN Implementation

The program contains four sample data points with X and Y coordinates and their corresponding labels:

* Point A → Red
* Point B → Red
* Point C → Blue
* Point D → Blue

A new point `(3,3)` is given to the classifier. The program calculates its distance from every existing point.

## 📐 Euclidean Distance

The program calculates the Euclidean distance between two points using:

```python
sqrt((X1 - X2)² + (Y1 - Y2)²)
```

This distance is used to find the closest points to the new point.

## 🔢 K Value

The project uses:

```python
K = 3
```

Therefore, the **3 nearest neighbors** are selected for classification.

## 🗳️ Voting

After selecting the nearest neighbors, the program counts the labels of those neighbors.

The label with the highest number of votes becomes the classification result.

## 🛠️ Technologies Used

* Python
* Math
* NumPy

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone <your-repository-link>
```

### 2. Open the project folder

```bash
cd KNN_From_Scratch
```

### 3. Run the program

```bash
python KNN_Classifier.py
```

## ⭐ Key Feature

The main feature of this project is that the **KNN algorithm is implemented manually**, including:

* Euclidean distance calculation
* Distance-based sorting
* K-nearest neighbor selection
* Majority voting

## 👩‍💻 Author

**Shreya Jagtap**

B.Sc. Data Science & Artificial Intelligence
