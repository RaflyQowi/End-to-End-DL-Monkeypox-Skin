# Chicken Disease Classification Project

## Overview

Welcome to the Chicken Disease Classification Project! This repository is designed for learning MLOps using TensorFlow for deep learning, TensorBoard for tracking callbacks, and DVC for building pipelines. The project provides a hands-on experience to understand and implement MLOps concepts in a real-world scenario.

## Workflows

1. **Update Configuration Files**

   - `config.yaml`
   - `secrets.yaml` (Optional)
   - `params.yaml`

2. **Update Entity and Configuration Manager**

   - Update the entity
   - Update the configuration manager in `src/config`

3. **Update Components**

   - Update the components

4. **Update Pipeline**

   - Update the pipeline

5. **Update Main Script**

   - Update the `main.py`

6. **Update DVC Configuration**
   - Update the `dvc.yaml`

## How to Run?

### Step 1: Clone the Repository

```bash
git clone https://github.com/entbappy/Chicken-Disease-Classification--Project
```

### Step 2: Create a Conda Environment

```bash
conda create -n cnncls python=3.8 -y
conda activate cnncls
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

### DVC Commands

1. Initialize DVC

   ```bash
   dvc init
   ```

2. Reproduce DVC Pipeline

   ```bash
   dvc repro
   ```

3. View DVC DAG (Directed Acyclic Graph)
   ```bash
   dvc dag
   ```

**Note: This Project is for Learning MLOps**

This project is focused on learning MLOps practices using TensorFlow, TensorBoard, and DVC. It is not aimed at achieving the highest accuracy in a classification problem. Instead, it provides a practical hands-on experience for understanding and implementing MLOps concepts in a real-world scenario.

```

Feel free to modify it further based on your specific needs or preferences!
```
