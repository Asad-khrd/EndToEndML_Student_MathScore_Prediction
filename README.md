# End-to-End Machine Learning Project 🚀

Welcome to the End-to-End Machine Learning project repository! This project is developed to predict students' math scores based on various input features using machine learning algorithms. The model achieved an impressive accuracy of **88.05%** on the test data, with the Ridge Regressor model outperforming other algorithms.

## Overview 📋

This project utilizes a variety of machine learning algorithms, including:

- **XGBoost** 🌳
- **Random Forest** 🌲
- **Decision Tree** 🌿
- **Lasso** 🧱
- **Ridge** 🏡
- **Adaboost** 🚀
- **K Nearest Neighbors** 👫

The **Ridge Regressor** model emerged as the top performer, achieving an accuracy of **88.05%** on the test dataset. The model predicts students' math scores based on input details such as parental education, race, test preparation status, and other relevant features.

## Features 🛠️

- Implementation of various machine learning algorithms.
- Exception handling to ensure robustness.
- Logging for tracking and debugging.
- Deployment of the model on **AWS EC2** with **Flask** as the backend.
- Interactive web interface for predicting students' math scores.

## Project Structure 📁

The project is organized into the following directories:

- `data`: Contains the dataset used for training and testing.
- `models`: Includes scripts for training and evaluating machine learning models.
- `flask_app`: Contains files for deploying the model on **AWS EC2** with **Flask**.
- `notebooks`: Jupyter notebooks for data exploration, preprocessing, and model evaluation.
- `utils`: Utility functions used throughout the project.

## Getting Started 🚀

To get started with this project, follow these steps:

1. **Clone** the repository: `git clone <repository-url>`
2. **Install** the required dependencies: `pip install -r requirements.txt`
3. **Explore** the notebooks in the `notebooks` directory for data analysis and model evaluation.
4. **Train and evaluate** machine learning models using scripts in the `models` directory.
5. **Deploy** the model on **AWS EC2** using the **Flask** application in the `flask_app` directory.

## Contributing 👥

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. **Fork** the repository.
2. **Create** a new branch: `git checkout -b feature-name`
3. **Make** your changes and **commit** them: `git commit -m 'Add new feature'`
4. **Push** to the branch: `git push origin feature-name`
5. **Submit** a pull request.

## License 📝

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.
