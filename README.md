# AI_Rag_model
This Ai agent which will take the pdf from end user and answer the question based on end users requirement  on the pdf that user uploaded 

Here’s a step-by-step guide you can run on your machine:

---

### 1. Clone the repository

```bash
git clone https://github.com/Ansari-5/AI_Rag_model.git
cd AI_Rag_model
```

---

### 2. Create a virtual environment

Using **Python venv**:

```bash
python3 -m venv venv
```

Or if you prefer **conda**:

```bash
conda create -n Chatbot  python=3.10 -y
conda activate Chatbot
```

---

### 3. Activate the virtual environment

* **Linux / macOS**:

  ```bash
  source venv/bin/activate
  ```
* **Windows (PowerShell)**:

  ```powershell
  venv\Scripts\activate
  ```

---

### 4. Install dependencies

Check if the repo has a `requirements.txt` file (I don’t have repo contents yet). If it does:

```bash
pip install -r requirements.txt
```

If instead it has `pyproject.toml` or `environment.yml`, you’d use:

```bash
pip install .
```

or

```bash
conda env create -f environment.yml
```

---

### 5. Verify installation

```bash
python -m pip list
```

You should see all installed packages.


