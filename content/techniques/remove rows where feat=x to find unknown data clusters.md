- when using [[UMAP dimension reduction]], you may find weird clusters of data
- if you remove rows where they have a specific value for a feature, then re-run the dimension reduction, the cluster may disappear
	- this can tell you which feat was causing the clusters
- **To be sure that dropping those rows remove the feature, try 100 seeds and verify that the cluster is gone**