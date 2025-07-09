Mutational Outcomes of DNA Damage

A classification of Key Parameters for Mutational Outcomes of DNA Damage Using Machine Learning Approaches with Augmented Data has been implemented as part of predicting Mutational Outcomes of DNA Damage with the following:

•	Model Evaluation: Evaluating the classification performance of three machine learning models—Logistic Regression (LR), Decision Tree (DT), and Support Vector Machine (SVM) on synthetic genetic data generated using a Bootstrapped VAE.

•	Cross Validation: A 5-fold stratified cross-validation was carried out to assess how well each classifier performs across multiple data splits, ensuring robustness and consistency in evaluation.

•	Feature Importance: Identifying the most influential input features contributing to mutational outcome prediction with ranking using the XGBoost classifier.

•	Biological Insight: Highlights of analysis that reveal which genetic factors most significantly impact the classification outcome, thereby aiding biological interpretability.

•	Synthetic Data Generation: A Bootstrapped Variational Autoencoder (BT-VAE) to generate synthetic genetic data for toxicological classification, whereas the original dataset, containing features like Adduct, Size, Sequence, and Polymerase, was bootstrapped to 600 samples to increase diversity. A VAE model was trained on the bootstrapped data to learn its latent structure, and 1,000 synthetic samples were generated.

•	GAN Comparison: The quality of synthetic genetic data generated using a Generative Adversarial Network (GAN) and its output was compared to the original dataset.

•	Similarity Assessment: The similarity between real and synthetic data was assessed using KDE plots and KL Divergence, Maximum Mean Discrepancy (MMD), and Wasserstein Distance, confirming good alignment. Features such as Adduct, Size, Sequence, and Polymerase, along with various statistical and distribution-based metrics, were applied to evaluate the similarity between real and synthetic data. 

•	Quantitative Validation: A Quantitative evaluation using three statistical divergence metrics to compute descriptive statistics (mean, median, and standard deviation) for each feature in both datasets and also to validate structural consistency.
