# How to Install and Run

## 1. Clone the Repository
```bash
git clone https://github.com/Toran625/CS_5640_Final_Project.git
cd CS_5640_Final_Project
```

## 2. Create and Activate a Virtual Environment
### Using venv
```bash
python -m venv venv
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate
```

### Using conda
```bash
conda create -n attention_env python=3.13
conda activate attention_env
```

## 3. Install Dependencies
```bash
pip install -r requirements.txt
```

If using GPU acceleration with CUDA, install the matching PyTorch build:
```bash
pip install torch torchvision --index-url https://download.pytorch.org/whl/cu121
```

## 4. Run the Project
### Option 1: Launch Jupyter Notebook
```bash
jupyter notebook AttentionPlacement_CNN.ipynb
```
### Option 2: Run In VSCode Environment
Open in VSCode using the Jupyter Notebook extension and RunAll