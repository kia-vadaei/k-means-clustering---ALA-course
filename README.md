# K-Means Clustering for Handwritten Digits (MNIST)

This repository contains Python code for performing k-means clustering on the MNIST dataset, a collection of handwritten digit images. The code includes functions for initializing centroids, assigning data points to clusters, and updating centroids.

## Usage

1. Adjust the `k` variable in the code to set the desired number of clusters.
2. Run the k-means algorithm using the MNIST dataset.
3. Visualize and save the centroids as images.

```python
# Example usage
k = 5

# Run k-means clustering
centroids, labels = kmeans(datas, k)

# Visualize and save centroids
for i in range(k):
    # ... (code for saving centroids as images)
```

## Files and Directories

- kmeans.py: Contains the k-means clustering functions.
- kianoosh/: Directory for saving centroid images.
  
## Dependencies

- numpy
- PIL (Pillow)

## Author
[Kianoosh Vadaei](https://github.com/kia-vadaei)

## Output Example

<img src="https://media.licdn.com/dms/image/D4E22AQGZ14NMyEJ1kA/feedshare-shrink_800/0/1700181378744?e=1703116800&v=beta&t=TWSw08w84C3g0HlLLEpgZCJ9AtLaEByCYFyaPC9hwE8" alt="Alt Text" width="400"/>


