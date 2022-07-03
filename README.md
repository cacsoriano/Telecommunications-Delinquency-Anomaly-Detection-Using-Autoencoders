# Telecommunications Delinquency: Anomaly Detection Using Autoencoders

Open the `Technical_Report.html` file to view the full report.

### Insights

1. Autoencoders can work better than other anomaly detection models depending on the use case. Autoencoders can predict outliers even if decision boundaries are not linear. In this case, in terms of telecommunications delinquency, we have a really good recall score for the model.

2. In terms of run time, the autoencoder is also faster than the second best model in terms of recall. Also for LOF, the larger the number of neighbors, the better it performs at the cost of run time.

3. Autoencoders also prefer high dimensional data since it compresses this in a latent space representation capturing only the most important parts. This can be problematic for other models since it would take longer run times.

4. Because it is a semi-supervised model, the methodology can work even though the dataset is highly imbalanced. No resampling techniques are needed in the pipeline.

5. Lastly, due to the simpler architecture of autoencoders, they can now be used with explainability libraries. Therefore, we can determine what makes delinquent behavior.

In partial fulfillment of the requirements for AIM MSDS 2022 Machine Learning 3 under Prof. Chris Monterola.
