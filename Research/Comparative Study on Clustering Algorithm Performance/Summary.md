## [Comparative Study On Clustering Algorithm Performance]

### ㆍ Summary
Provide guidelines for algorithm selection, comparing the performance of different clustering algorithms according to properties of data set
<br/>
<br/>
### ㆍ Used Algorithms/Methods/Datasets
▸ Algorithm : K-Means, DBSCAN, Gaussian Mixture Model, Agglomerative Hierachical Clustering
<br/>
▸ Performance metrics : Silhouette Coefficient, Calinski-Harabasz Index, Davies-Bouldin Index, execution time
<br/>
▸ Dataset : iris, wine, credit card (from Kaggle)
<br/>
<br/>
### ㆍ Experiments
▸ The performance was analyzed using the original dataset and a reduced dataset using the UMAP(Uniform Manifold Approximation and Projection) and PCA(Principle Components Analysis)
<br/>
<br/>
### ㆍ Conclusion
▸ To get a highly efficient model, reducing the dimension of the data by using PCA and UMAP before applying clustering algorithms is recommended.
<br/>
▸ The K-Means method, combined with data reduction techniques, can achieve good results without significantly affecting the cluster propensity of the dataset.
<br/>
▸ It is recommended to apply the DBSCAN algorithm to a dataset with a complex structure or a dataset with a highly cluster tendency.
<br/>
<br/>
### ㆍ Reference
[1] K. Bindra, A. Mishra, “A Detailed Study of Clustering Algorithms,” 6th International Conference on Reliability, Infocom Technologies and Optimization, pp. 370-376, Sep. 20-22, 2017
<br/>
[2] Rodriguez MZ, Comin CH, Casanova D, Bruno OM, Amancio DR, Costa LdF, et al, “Clustering algorithms: A comparative approach,”, PLOS, January 15, 2019
<br/>
[3] S. H. Shah, M. J. Iqbal, M. Bakhsh and A. Iqbal, “Analysis of Different Clustering Algorithms for Accurate Knowledge Extraction from Popular DataSets,” Information Sciences Letters, No. 1, pp. 21- 31, 2020
<br/>
[4] N. Shahriar, S. M. A. Al Faisal, Md. M. Pinjor, Md. A. S. Zobayer Rafi, A. R. Sarkar, “Comparative Performance Analysis of K-Means and DBSCAN Clustering algorithms on various platforms,” 22nd International Conference on Computer andInformation Technology, pp. 18-20 Dec. 2019
