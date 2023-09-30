## Machine-Learning-project

# Structure of the repository
This repository contains:
- Excel files with training and test data
- Pyhton script to compile and manage data, and train the Machine Learning models adopted and to produce effective data visualization of the results
- Log file to track the most relevant model results

# Idea of the project
The idea that almost entirely drove the project was to evaluate the performance of the anomaly detection model through a practical, business-oriented approach. As a matter of fact, a labeled test set obtained by fractioning the original dataset would contain roughly 100 to 200 samples. Since the number of anomalies is, in general, much smaller than the number of normal data, even one misclassified anomaly would change drastically the performance of the model. For this reason, two important decisions were taken:

# Models and techniques
Multiple anomaly detection techniques based on completely different approaches were implemented. The best models were put together to form a single, more powerful model by means of model averaging. This allowed to exploit the advantages of each specific architecture (providing diversification) and to average out the errors of each model;
The predictions of the anomaly detection model on additional unlabeled data were used to regulate the risk-propensity of a toy portfolio (i.e. the fraction of equites, bonds and commodities forming the portfolio). The custom portfolio outperformed three different benchmarks (low, medium and high risk), revealing the goodness of the model.
