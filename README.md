# MLOps on Image Classifications (Monkey Pox classification problem)

Welcome to the MLOps on Image Classifications Project! This repository is designed for learning MLOps using TensorFlow for deep learning, TensorBoard for tracking callbacks, and DVC for building pipelines. The project provides a hands-on experience to understand and implement MLOps concepts in a real-world scenario.

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
https://github.com/RaflyQowi/End-to-End-DL-Monkeypox-Skin.git
```

### Step 2: Create a Python Virtual Environment

```bash
python -m venv venv
source venv/bin/activate    # On Windows, use `.\cnncls\Scripts\activate`
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

```

Feel free to adjust it further according to your preferences!
```
