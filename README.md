# Music Genre Classification System

Given multiple audio files, the task is to categorize each audio file in a certain category like audio belongs to Disco, hip-hop, etc. The music genre classification can be built using different approaches in which the top 4 approaches that are mostly used are listed below.

1. Multiclass support vector machine
2. K-Nearest Neighbors
3. K-means clustering algorithm
4. Convolutional neural network

I have used K-Nearest Neighbors algorithm because various researches prove it is one of the best algorithms to give good performance and till time along with optimized models organizations uses this algorithm in recommendation systems as support.

I used MFCC to extract features from audio files. After that, I built a KNN classifier from scratch that finds K number of nearest neighbour based on features and maximum neighbour belonging to particular class gives as an output. Using this method, I achieved an accuracy of 86.67%
