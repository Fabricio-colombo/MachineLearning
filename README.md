# Python AI Project: Artificial Intelligence and Predictions

Welcome to the Python AI Project: Artificial Intelligence and Predictions. In this project, we have developed a model to determine the credit score of a bank's customers. The goal is to create a system capable of analyzing customer information and automatically classifying the credit score as Poor, Fair, or Good.

## Project Structure
- **clientes.csv:** File containing historical customer data used for training the model.
- **ia.ipynb:** Jupyter Notebook with the main code of the project.
- **inicial.ipynb:** Jupyter Notebook with initial codes and experiments.
- **novos_clientes.csv:** File containing data of new customers for whom we will make predictions.

The Artificial Intelligence project aims to develop a credit prediction model for a bank. Using historical customer data from the "clientes.csv" file, we performed data preparation and model training with the help of Pandas and Scikit-Learn libraries. We implemented algorithms such as RandomForestClassifier and KNeighborsClassifier, achieving an accuracy of approximately 82.51% and 73.24%, respectively. The preprocessing involved the encoding of categorical variables and the separation of data into training and testing sets. Additionally, we made predictions for new customers in the "novos_clientes.csv" file. Analyzing the importance of features, we highlighted that "total_debt" and "credit_mix" are significant factors in the model's decision-making process. This project represents a practical application of A.I. in the financial sector, providing a valuable tool for automated credit assessment.
