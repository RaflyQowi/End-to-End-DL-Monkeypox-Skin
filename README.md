# MLOps on Image Classifications (Monkeypox Classification)

Welcome to the MLOps on Image Classifications Project! This repository serves as a hands-on guide for implementing MLOps using TensorFlow for deep learning, TensorBoard for tracking callbacks, and DVC for building pipelines. Gain practical experience in MLOps concepts within a real-world scenario.

## Project Overview

Provide a brief overview of the project, highlighting its goals and significance.

## Project Setup

### 1. Update Configuration Files

Before diving into the project, make sure to customize essential configuration files:

- `config.yaml`: Modify global settings.
- `params.yaml`: Adjust parameters for model training and evaluation.

### 2. Update Entity and Configuration Manager

Update the entity and configuration manager located in `src/config` to align them with your project requirements.

### 3. Update Components

Review and customize various components as needed for your specific use case.

### 4. Update Pipeline

Tailor the pipeline to suit your dataset, model architecture, and training objectives.

### 5. Update Main Script

Customize the `main.py` script to incorporate any additional functionalities or specific requirements.

### 6. Update DVC Configuration

Adjust the `dvc.yaml` file to capture changes effectively during the project lifecycle.

## How to Run?

Follow these steps to set up and run the application:

### Step 1: Clone the Repository

```bash
git clone https://github.com/RaflyQowi/End-to-End-DL-Monkeypox-Skin.git
```

### Step 2: Set Up Python Virtual Environment

```bash
python -m venv venv
source venv/bin/activate    # On Windows, use `.\venv\Scripts\activate`
```

### Step 3: Install Requirements

```bash
pip install -r requirements.txt
```

### Step 4: Run the Application

```bash
python app.py
```

### Step 5: Access Local Host

Open your local host and port in a web browser.

## DVC Commands

Leverage DVC for versioning and managing your data science projects:

1. **Initialize DVC**

   ```bash
   dvc init
   ```

2. **Reproduce DVC Pipeline**

   ```bash
   dvc repro
   ```

3. **View DVC DAG (Directed Acyclic Graph)**

   ```bash
   dvc dag
   ```

## Troubleshooting

Include a troubleshooting section to address common issues users may encounter during setup or execution.

Feel free to customize and adapt the instructions to suit your needs!

```
This version includes a "Project Overview" section, which can briefly describe the project's goals and significance. Additionally, I've added a "Troubleshooting" section to help users address common issues. Adjust as needed!
```
