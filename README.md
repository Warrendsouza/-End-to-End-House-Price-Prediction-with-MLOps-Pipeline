# End-to-End-House-Price-Prediction-with-MLOps-Pipeline

**Project Description:**

This project demonstrates the complete lifecycle of building and deploying a house price prediction model, emphasizing robust MLOps practices. It moves beyond simple model training to incorporate continuous integration, continuous deployment (CI/CD), experiment tracking, and API-based inference. The goal is to create a scalable, reproducible, and deployable machine learning system.

**Key Features:**

* **Data-Driven Approach:** Focused on thorough data understanding and iterative refinement, ensuring the model's accuracy reflects the underlying data patterns.
* **MLOps Pipeline:** Implements a CI/CD pipeline for automated model training and deployment, streamlining the development process.
* **API-Based Inference:** Exposes the trained model via an API, enabling seamless integration with other applications.
* **Experiment Tracking:** Uses MLflow to track experiments, compare model performance, and manage model versions.
* **Workflow Orchestration:** Leverages ZenML to define and manage the machine learning pipeline, enhancing reproducibility and collaboration.
* **Code Quality:** Adheres to best practices for code readability and maintainability, ensuring a robust and scalable codebase.

**Tools and Technologies:**

* **ZenML:** MLOps framework for pipeline orchestration and management.
* **MLflow:** Experiment tracking and model registry.
* **Python:** Main programming language.
* **Scikit-learn:** Machine learning library for model training.
* **FastAPI:** For creating the inference API.
* **Git:** Version control.
* **Docker:** Containerization for deployment.

**Methodologies:**

* **Iterative Development:** Emphasizing continuous improvement through data analysis and model refinement.
* **Factory Design Pattern:** Used for code modularity and maintainability.
* **CI/CD:** Automated testing and deployment for efficient model updates.

**Quantifiable Metrics and Progress Tracking:**

To demonstrate the project's success and progress, consider tracking the following metrics:

* **Model Performance:**
    * **Mean Absolute Error (MAE):** Measure the average magnitude of errors in predictions.
    * **Root Mean Squared Error (RMSE):** Measure the standard deviation of the prediction errors.
    * **R-squared (R²):** Measure the proportion of the variance in the dependent variable that is predictable from the independent variable(s).
* **Pipeline Efficiency:**
    * **Deployment Time:** Measure the time taken to deploy a new model version.
    * **Training Time:** Measure the time taken to train the model.
    * **Inference Latency:** Measure the time taken to receive a prediction from the API.
* **Experiment Tracking:**
    * **Number of Experiments:** Track the number of experiments conducted to optimize the model.
    * **Model Versioning:** Track the number of model versions created and deployed.
* **Code Quality:**
    * **Code Coverage:** Measure the percentage of code covered by tests.
    * **Static Analysis:** Track code quality metrics using tools like pylint or flake8.
* **API Performance:**
    * **Requests Per Second (RPS):** Measure the number of requests the API can handle per second.
    * **API uptime:** measure the percentage of time that the API is online.

**Progress Tracking:**

* Use Git commit messages to document changes and progress.
* Maintain a `README.md` file to track project milestones and updates.
* Use MLflow to log metrics and parameters for each experiment.
* Create a simple dashboard to show the metrics of the API.

**How to Use This Repository:**

1.  Clone the repository.
2.  Follow the instructions in the `README.md` file to set up the environment.
3.  Run the ZenML pipeline to train and deploy the model.
4.  Use the provided API endpoint to make predictions.
5.  Experiment with different model parameters and data preprocessing techniques to improve performance.


