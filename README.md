# Expense Management System

### This project is ideal for developers looking to combine Python’s versatility with modern web development tools to create fast, scalable, and user-friendly applications.

This project is a Python-based web application that combines the simplicity of Streamlit for the frontend with the high performance of FastAPI for the backend server. It demonstrates a modern architecture for building scalable and interactive web applications, suitable for data-driven use cases and API-driven workflows.


## Features

**Frontend (Streamlit)**:
  - Provides an intuitive, interactive user interface for visualizing data and interacting with the application.
  - Enables rapid prototyping and deployment of custom dashboards and user workflows.

**Backend (FastAPI)**:
   - High-performance RESTful API server for handling business logic and data processing.**
   - Built-in support for OpenAPI documentation and asynchronous operations.

**Python Ecosystem**:
   - Leverages Python's rich ecosystem for data manipulation, analysis, and visualization.
   - Easy integration with external APIs, databases, and machine learning models.

**Use Cases**
   - Interactive dashboards for data visualization.
   - RESTful APIs for serving or processing data.
   - Rapid development of proof-of-concept applications.



## Project Structure

- **frontend/**: Contains the Streamlit application code.
- **backend/**: Contains the FastAPI backend server code.
- **tests/**: Contains the test cases for both frontend and backend.
- **requirements.txt**: Lists the required Python packages.
- **README.md**: Provides an overview and instructions for the project.


## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/expense-management-system.git
   cd expense-management-system
   ```
1. **Install dependencies:**:   
   ```commandline
    pip install -r requirements.txt
   ```
1. **Run the FastAPI server:**:   
   ```commandline
    uvicorn server.server:app --reload
   ```
1. **Run the Streamlit app:**:   
   ```commandline
    streamlit run frontend/app.py
   ```
