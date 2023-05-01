# Support Vector Machin (svm)

Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.


The goal of the SVM algorithm is to create the best line or decision boundary that can segregate n-dimensional space into classes so that we can easily put the new data point in the correct category in the future. This best decision boundary is called a hyperplane.

SVM chooses the extreme points/vectors that help in creating the hyperplane. These extreme cases are called as support vectors, and hence algorithm is termed as Support Vector Machine. Consider the below diagram in which there are two different categories that are classified using a decision boundary or hyperplane:

![image](https://user-images.githubusercontent.com/51235527/235447501-c9bc36cf-eea9-4cd9-99f9-45f45f7fe744.png)

SVM algorithm can be used for Face detection, image classification, text categorization, etc.

# Types of SVM

## Linear SVM: 
Linear SVM is used for linearly separable data, which means if a dataset can be classified into two classes by using a single straight line, then such data is termed as linearly separable data, and classifier is used called as Linear SVM classifier.

## Non-linear SVM:
Non-Linear SVM is used for non-linearly separated data, which means if a dataset cannot be classified by using a straight line, then such data is termed as non-linear data and classifier used is called as Non-linear SVM classifier.

# Hyperplane and Support Vectors in the SVM algorithm:

## Hyperplane: 
There can be multiple lines/decision boundaries to segregate the classes in n-dimensional space, but we need to find out the best decision boundary that helps to classify the data points. This best boundary is known as the hyperplane of SVM.

The dimensions of the hyperplane depend on the features present in the dataset, which means if there are 2 features (as shown in image), then hyperplane will be a straight line. And if there are 3 features, then hyperplane will be a 2-dimension plane.

We always create a hyperplane that has a maximum margin, which means the maximum distance between the data points.

## Support Vectors:
The data points or vectors that are the closest to the hyperplane and which affect the position of the hyperplane are termed as Support Vector. Since these vectors support the hyperplane, hence called a Support vector.

# How does SVM works?
 
## Linear SVM:
The working of the SVM algorithm can be understood by using an example. Suppose we have a dataset that has two tags (green and blue), and the dataset has two features x1 and x2. We want a classifier that can classify the pair(x1, x2) of coordinates in either green or blue.

![image](https://user-images.githubusercontent.com/51235527/235448112-5bd8105e-6fe1-4c22-8a23-809e8b358b91.png)

So as it is 2-d space so by just using a straight line, we can easily separate these two classes. But there can be multiple lines that can separate these classes.

![image](https://user-images.githubusercontent.com/51235527/235448145-844d11d3-7be0-4e40-ac4e-d9ef0550e960.png)

Hence, the SVM algorithm helps to find the best line or decision boundary; this best boundary or region is called as a hyperplane. SVM algorithm finds the closest point of the lines from both the classes. These points are called support vectors. The distance between the vectors and the hyperplane is called as margin. And the goal of SVM is to maximize this margin. The hyperplane with maximum margin is called the optimal hyperplane.


![image](https://user-images.githubusercontent.com/51235527/235448224-42162cf2-de3f-477e-97e2-fbe8bf93e19a.png)


## Non-Linear SVM:

If data is linearly arranged, then we can separate it by using a straight line, but for non-linear data, we cannot draw a single straight line.

![image](https://user-images.githubusercontent.com/51235527/235448445-f70c8d28-8d50-4bf5-aa9b-754c6bd87837.png)


So to separate these data points, we need to add one more dimension. For linear data, we have used two dimensions x and y, so for non-linear data, we will add a third dimension z. It can be calculated as:

## z=x2 +y2

By adding the third dimension, the sample space will become as:

![image](https://user-images.githubusercontent.com/51235527/235448478-12276d4a-3833-41f9-a3ca-aa4663e56508.png)


So now, SVM will divide the datasets into classes in the following way.

![image](https://user-images.githubusercontent.com/51235527/235448508-dc730daa-3c63-4fe4-b108-5aaeb703dadc.png)

Since we are in 3-d Space, hence it is looking like a plane parallel to the x-axis. If we convert it in 2d space with z=1, then it will become as:

![image](https://user-images.githubusercontent.com/51235527/235448539-a7ce0fc6-7598-4c35-8155-4d71d64d3d72.png)

Hence we get a circumference of radius 1 in case of non-linear data.















