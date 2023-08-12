## Industry-Standard Project: Diamond-Price-Predictor 

## Project Flow:
**Environment Setup-->setup.py-->ML Pipeline-Modular Coding Methodology-->Flask(WebApp)-->Docker Image-->Container Registry(Azure)-->CI/CD Pipeline(GitHub Actions)-->Deployed on Microsoft Azure WebApp**

## Introduction & Objectives:

This Diamond Price Predictor project is an industry-standard project that aims to develop a machine learning model for predicting the price of diamonds based on various features such as carat, cut quality, color, clarity and more. The project follows best practices in terms of code organization, **modular coding approach** to ensure maintainability and extensibility. This means that the code is organized into independent modules that can be easily reused and modified. Pipeline setup, containerization, and deployment to a cloud platform.

### Problem Statement

Diamonds are highly valued gemstones, each possessing unique qualities that influence their worth. The pricing of diamonds is a complex process, influenced by various attributes such as carat weight, cut quality, color, clarity, dimensions, and more.
To streamline this process and provide consumers, diamond merchants with more transparency, my aim to develop a robust machine learning model that can predict the price of a diamond based on its features.


### Technologies and Frameworks:
**Python,** **Pandas,** **Numpy,** **Seaborn,**  **Scikit-learn,** **Flask**

### Tools:
#### Visual Studio Code (VS Code): A popular and feature-rich code editor that provides a great development environment.
#### Git and GitHub: Version control and collaboration tools for code management and sharing.
#### AnaConda: A package and environment manager used to create isolated environments for the project.
#### Docker: Used to create containerized applications for consistent deployment.
#### Microsoft Azure: Cloud platform used for hosting the deployed web application.

By leveraging these technologies, frameworks and tools effectively, we ensure efficient development, seamless deployment, and an interactive user experience. The combination of Python, machine learning libraries, web frameworks, and cloud services contributes to the creation of a comprehensive and functional solution for predicting diamond prices.

## Project Flow

* ## Environment Setup:
**Before starting the development process, the project environment is set up. This includes creating a virtual environment with the necessary dependencies and tools.** 

* #### setup.py file:
The **setup.py** file is a critical component to packaging and distributing Python projects. It's used by tools like **setuptools** and **pip** to build, package, and install your project, making it available for distribution and installation across different environments.

* ## ML Pipeline and Modular Coding Methodology:
**Implemented a modular ML pipeline including data ingestion, data transformation, model training, and evaluation with each component clearly defined and encapsulated.**

* #### Data Ingestion**

* #### Data Preprocessing

* #### Exploratory Data Analysis(EDA): analyzed and visualized the data to understand the data.

* #### Model Training, Selection and Evaluation:
 **Experimentation with various algorithms-Linear Regression, Ridge, Lasso, ElasticNet and hyperparameters to find the best-performing model.Evaluated the model's performance using appropriate metrics. Best Model: Linear Regression, R2 Score: 0.9362906819996044**

* ## Flask Web Application
The prediction model is integrated into a user-friendly web application using Flask, a micro web framework for Python. Users can input diamond features through a web interface, and the application will use the trained model to predict the diamond's price.

* ##  Docker Image Creation
The application is containerized using Docker, allowing for consistent deployment across different environments. A Dockerfile defines the application's environment and dependencies. This encapsulation ensures that the application runs consistently regardless of the host system.

* ## Container Registry (Azure)
The Docker image is pushed to a container registry in Azure, such as Azure Container Registry. This registry serves as a centralized repository for storing and managing Docker images, making it easy to distribute and deploy the application.

* ## CI/CD Pipeline(GitHub Actions):
Implemented a CI/CD pipeline to automate the deployment process.Ensured efficient updates and maintenance of the application.
A Continuous Integration and Continuous Deployment (CI/CD) pipeline is set up using GitHub Actions. This pipeline automates the process of building, testing, and deploying the application whenever changes are pushed to the repository. It ensures that the codebase is always in a deployable state.

* ## Deployment (Microsoft Azure):
The final step involves deploying the web application to **Microsoft Azure WebApp**. Azure WebApp is a Platform-as-a-Service (PaaS) offering that simplifies application deployment and scaling. The Docker container containing the application is deployed to the WebApp instance.

### 1.Create new Environment
```
conda create -p env python==3.8
```

### 2.Activate your environment
- For bash terminal
```
source activate env/
```
- For CMD prompt
```
conda activate env/
```

### 3.Install your requriments file

```
pip install -r requirements.txt
```

