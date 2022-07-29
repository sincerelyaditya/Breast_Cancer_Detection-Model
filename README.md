# Product Wiki

All things related to product - processes, best practices, setup guides, and more!

## Guides & Processes

---

**BREAST CANCER DETECTION USING CLASSIFICATION ALGORITHMS**

**ADITYA SHRIVASTAVA**

**207103**

**CSE 2ND YEAR**

**NITW**

**Machine Learning Classification Algorithms Used**

- Logistic Regression
- Naive Bayes
- Decision Trees
- Random Forests
- K-Nearest Neighbors
- Support Vector Machines

**Dataset Used:**

Breast Cancer Detection - Wisconsin Breast Cancer Dataset

[UCI Machine Learning Repository: Breast Cancer Wisconsin (Diagnostic) Data Set](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)

**PROJECT DESCRIPTION**

Breast cancer is the most common cancer amongst women in the world. It accounts for 25% of all cancer cases, and affected over 2.1 Million people in 2015 alone. It starts when cells in the breast begin to grow out of control. These cells usually form tumors that can be seen via X-ray or felt as lumps in the breast area.

The key challenges against it’s detection is how to classify tumors into malignant (cancerous) or benign (non cancerous).

This data was donated by researchers of the University of Wisconsin and includes the measurements from digitized images of fine-needle aspirate of a breast mass.

The breast cancer data includes 569 examples of cancer biopsies, each with 32 features. One feature is an identification number, another is the cancer diagnosis and 30 are numeric-valued laboratory measurements. The diagnosis is coded as "M" to indicate malignant or "B" to indicate benign.

The other 30 numeric measurements comprise the mean, standard error and worst (i.e. largest) value for 10 different characteristics of the digitized cell nuclei, which are as follows:-

1. Radius
2. Texture
3. Perimeter
4. Area
5. Smoothness
6. Compactness
7. Concavity
8. Concave Points
9. Symmetry
10. Fractal dimension

I’m attaching google colab link to the project below

[https://colab.research.google.com/drive/11OCm5L1EFkG_OabpG_CMQtuQTxcOkmJf?usp=sharing](https://colab.research.google.com/drive/11OCm5L1EFkG_OabpG_CMQtuQTxcOkmJf?usp=sharing)

**CONCLUSION**

<img width="499" alt="Screenshot 2022-07-29 085527" src="https://user-images.githubusercontent.com/91006450/181676473-c5269423-fe06-4d7c-9518-f8154043ee19.png">


we can see that the validation accuracy is higher in 9 Nearest Neighbors. However, on comparing the models - Kernel SVC and 9 Nearest Neighbors we can see that the Training accuracy and Validation accuracy is stable in Kernel SVC model (less standard deviation). Hence, we use the model Kernel SVC for Breast Cancer Detection.

**Hence our recommended model - Kernel SVC provides a model accuracy of 98.25 percent and a validation accuracy of 97.38 percent.**
