# ML Pipeline & Model Deployment

A machine learning project demonstrating an automated CI/ML workflow using GitHub Actions.

## 🚀 Continuous Integration & Machine Learning

The project includes an automated CI-ML pipeline that:

- runs automatically on push, pull request, or manually,
- installs project dependencies from `requirements*.txt` files,
- performs code quality checks using **flake8** and **Black**,
- runs automated tests with **pytest**,
- trains a machine learning model using **Logistic Regression**,
- publishes the trained model as an artifact with environment-specific names (`model-dev`, `model-prod`),
- uses repository **Variables** and **Secrets** for configuration.

## 🛠️ Technologies

- Python
- GitHub Actions
- pytest
- flake8
- Black
- Scikit-learn
- Logistic Regression
- Terraform
