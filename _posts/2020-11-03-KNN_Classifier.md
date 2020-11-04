---
layout: post
title: K_Nearest_neighbors_from_scratch
bigimg: /img/KNN.png
---

KNN is a non-parametric algorithm. Non-parametric means there is no assumption for underlying data distribution. In other words, the model structure determined from the dataset. In KNN classifier algorithm works on the core deciding factor which is a — k nearest neighbors. Let’s explain this by using Fig:1-We have an entire dataset with 2 class labels which are class A (red)& class B(green). When we have a new data point(Yellow question mark)to classify then we will compare with the entire dataset and we will check that this new datapoint belongs to red class A or green class B. As we know it all depends on k. Let’s check how it behaves with the different values of k. We see when k=3 then majority vote is green class as 2 data points belong to green class & 1 data point belongs to the red class. So the returned predicted output is Class A(Green class). But when we take k=7 then the majority vote is Red class as 4 data points belong to the red class & 3 data points belong to the green class. So the returned predicted output is Class B(Red class).
[**to learn more click here**](https://anitashar2006.medium.com/k-nearest-neighbors-knn-classifier-from-scratch-80113a558d93)
