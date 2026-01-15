@Library('Jenkins-shared-library') _

mlModelPipeline(
    appName: 'saaymo/property-recommendation-engine-k-means-cosine-similarity',
    hfRepo: 'saaymo/Property-Recommendation-Engine-K-MEANS-Cosine-Similarity',
    modelFiles: [
        [name: 'k_means_model.pkl', targetDir: 'model/models'],
        [name: 'preprocessor.pkl', targetDir: 'model/models'],
        [name: 'property_feature_matrix.npy', targetDir: 'model/data']
    ]
)
