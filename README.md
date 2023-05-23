# K-Nearest-Neighbors
Applying K Nearest Neighbors Machine Learning model on open-source Breast Cancer Detection Classification Master Dataset

*	Used for both classification and regression
*	Distance based model

K-nearest neighbors (KNN) is a non-parametric machine learning algorithm used for both classification and regression tasks. It is a simple yet powerful algorithm that makes predictions based on the similarity of input data to its neighboring data points.

Theory: The KNN algorithm works based on the principle that similar data points tend to share the same class or have similar output values. The algorithm stores the entire training dataset in memory and uses it during the prediction phase. When a new data point is provided, the algorithm calculates the distance between that point and all other data points in the training set. The distance metric used is typically Euclidean distance, although other distance metrics can be employed.

![image](https://github.com/Sai-Likhith/K-Nearest-Neighbors/assets/102646751/a6f085f4-d8a4-4bcd-95b6-5c0299eb4fbd)


KNN algorithm:
1.	Determine the number of neighbors (K) to consider, usually specified by the user.
2.	Calculate the distance between the new data point and all other data points in the training set.
3.	Select the K data points with the shortest distances (i.e., the K nearest neighbors).
4.	For classification tasks, assign the class label that is most frequent among the K nearest neighbors to the new data point. For regression tasks, compute the average or weighted average of the output values of the K nearest neighbors.
5.	Output the predicted class label or regression value for the new data point.
# Advantages of KNN:
*	Simplicity: KNN is easy to understand and implement. It does not require any assumptions about the underlying data distribution or model structure.
*	Versatility: KNN can be applied to both classification and regression problems. It can handle both numerical and categorical data.
*	Adaptability: KNN is a lazy learner, meaning it does not perform a training phase. This makes it suitable for dynamic or changing environments, as the model can be updated with new data points easily.
*	Non-linearity: KNN can capture complex, non-linear relationships between the input features and the target variable.
# Limitations of KNN:
*	Computational Complexity: As the algorithm compares the new data point with all training data points, the computational cost can be high, especially for large datasets.
*	Sensitivity to Feature Scaling: KNN calculates distances based on feature values. If the features have different scales, features with larger values can dominate the distance calculation, leading to biased results. It is essential to normalize or standardize the features before applying KNN.
*	Determining the Optimal K: Choosing the optimal number of neighbors (K) is subjective and depends on the dataset and problem at hand. A small K may result in overfitting, while a large K may introduce more noise and dilute the local patterns.
# Applications of KNN:
*	Recommender Systems: KNN can be used to build recommendation engines by finding similar users or items based on their features or preferences.
*	Image Recognition: KNN can be applied to image classification tasks by comparing the pixel values or feature vectors of images to identify similar objects or patterns.
*	Anomaly Detection: KNN can detect outliers or anomalies in data by identifying data points that are significantly different from their neighbors.
*	Text Classification: KNN can classify text documents based on their word frequencies or vector representations by measuring the similarity between documents.
*	Healthcare: KNN can assist in medical diagnosis by finding similar patient cases or medical images for comparison and decision support.*
