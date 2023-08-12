## Industry-Standard Project: Diamond-Price-Predictor 

## Project Flow:
**Environment Setup-->setup.py-->ML_Pipeline-Modular_Coding_Methodology-->Flask(WebApp)-->Docker Image-->Container Registry(Azure)-->CI/CD Pipeline(GitHub Actions)-->Deployed on Microsoft Azure WebApp**


### Problem Statement

Diamonds are highly valued gemstones, each possessing unique qualities that influence their worth. The pricing of diamonds is a complex process, influenced by various attributes such as carat weight, cut quality, color, clarity, dimensions, and more.
To streamline this process and provide consumers, diamond merchants with more transparency, my aim to develop a robust machine learning model that can predict the price of a diamond based on its features.

### Project Title and Objectives:

Welcome to the **Diamond Price Predictor** is an **industry-standard project** aims to build a machine learning model that predicts the price of a diamond based on various features such as carat, cut quality, color, clarity and more. This project follows a **modular coding approach** to ensure maintainability and extensibility. This means that the code is organized into independent modules that can be easily reused and modified.

### Technologies and Frameworks:
**Python,** **Pandas,** **Numpy,** **Seaborn,**  **Scikit-learn,** **Flask**
### Tools:
Visual Studio Code (VS Code): A popular and feature-rich code editor that provides a great development environment.
Git and GitHub: Version control and collaboration tools for code management and sharing.
Conda: A package and environment manager used to create isolated environments for the project.
Docker: Used to create containerized applications for consistent deployment.
Microsoft Azure: Cloud platform used for hosting the deployed web application.

By leveraging these technologies, frameworks and tools effectively, we ensure efficient development, seamless deployment, and an interactive user experience. The combination of Python, machine learning libraries, web frameworks, and cloud services contributes to the creation of a comprehensive and functional solution for predicting diamond prices.

### Project Flow

* #### Environment Setup:
Created a Conda environment.
* #### setup.py file:
The **setup.py** file is a critical component when it comes to packaging and distributing Python projects. It's used by tools like **setuptools** and **pip** to build, package, and install your project, making it available for distribution and installation across different environments..

* #### ML Pipeline and Modular Coding Methodology:
**Implemented a modular ML pipeline including data ingestion, data transformation, model training, and evaluation with each component clearly defined and encapsulated.**

**Data Ingestion**
**Data Preprocessing**
**Exploratory Data Analysis(EDA): analyzed and visualized the data to understand the data.**
**Model Training, Selection and Evaluation:** Experimentation with various algorithms-Linear Regression, Ridge, Lasso, ElasticNet and hyperparameters to find the best-performing model.Evaluated the model's performance using appropriate metrics. Best Model: Linear Regression, R2 Score: 0.9362906819996044

* #### Flask Web Application
The prediction model is integrated into a user-friendly web application using Flask, a micro web framework for Python. Users can input diamond features through a web interface, and the application will use the trained model to predict the diamond's price.

* #### CI/CD Pipeline(GitHub Actions):
Implemented a CI/CD pipeline to automate the deployment process.Ensured efficient updates and maintenance of the application.
A Continuous Integration and Continuous Deployment (CI/CD) pipeline is set up using GitHub Actions. This pipeline automates the process of building, testing, and deploying the application whenever changes are pushed to the repository. It ensures that the codebase is always in a deployable state.

* #### Deployment (Microsoft Azure):
Created a **Docker image** of the application.
Pushed the Docker image to a **container registry.**
Deployed on **Microsoft Azure WebApp** users can access the web app's interactive interface to input diamond features and receive predicted prices.



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

