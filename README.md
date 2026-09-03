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

## 📁 Project Structure

```text
├── .github/workflows/   # GitHub Actions workflows
├── src/                 # Source code
├── tests/               # Automated tests
├── outputs/             # Generated outputs and model artifacts
├── aml-lab-01/          # Machine learning lab
├── aml-lab-02/          # ML pipeline and model registry
├── terraform_lab3/      # Terraform configuration
├── requirements.txt     # Project dependencies
└── requirements-dev.txt # Development dependencies
