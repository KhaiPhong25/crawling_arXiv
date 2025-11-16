# **Milestone 1**

This repository implements **Milestone 1**, focusing on automated downloading, and organizing metadata, paper and reference information from arXiv papers.  

---

## Requirements

### **Python Version**
```

Python 3.9+

```

To install all required dependencies, simply run:

```bash
pip install -r requirements.txt
```

System packages (Linux or Google colab):

```bash
apt install unzip
```

If using Conda:

```bash
conda install -c conda-forge orjson tqdm
pip install arxiv filetype requests
```

---

## Configuration parameters

Modify inside the notebooks:

### **1. arXiv ID Range**

```python
START_ID = 2211.13747
END_ID   = 2212.11475
```

### **2. Scraping Rate**

Scraping rate for metadata: 100%
Scraping rate for paper: 99.37%
Scraping rate for reference: 99.6%

### **3. Parallelism**
```python
NUM_THREADS = 1
```

---

## How to Run

### **1. Open Jupyter Notebook**
When scraping metadata and paper
```bash
jupyter notebook module_1.ipynb
```
When scraping reference
```bash
jupyter notebook module_2.ipynb
```