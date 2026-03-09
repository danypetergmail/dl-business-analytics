# Deep Learning for Business Analytics
### From Basics to Large Language Models

**Authors: Dr. M. Ramasubramaniam & Mr. Daniel Peter**

A practical, hands-on book for students and business analytics professionals.  
Each chapter is a self-contained Jupyter notebook built for Google Colab.

---

## How to Use This Book

### Option A — Google Colab (recommended, no setup)
Click any **Open in Colab** badge below. The notebook opens directly in your browser.  
A GPU is not required — all exercises run on CPU. A GPU (available free on Colab) will speed up training in Chapters 4–6.

### Option B — Run locally
```bash
git clone https://github.com/danypetergmail/dl-business-analytics.git
cd dl-business-analytics
pip install -r requirements.txt
jupyter notebook
```

---

## Chapters

| # | Chapter | Open in Colab |
|---|---------|---------------|
| 0 | Introduction & Setup | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/danypetergmail/dl-business-analytics/blob/main/notebooks/ch00_intro.ipynb) |
| 1 | Foundations of Deep Learning | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/danypetergmail/dl-business-analytics/blob/main/notebooks/ch01_foundations.ipynb) |
| 2 | Essential Tools and Math | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/danypetergmail/dl-business-analytics/blob/main/notebooks/ch02_tools_math.ipynb) |
| 3 | Optimization and Training | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/danypetergmail/dl-business-analytics/blob/main/notebooks/ch03_optimization.ipynb) |
| 4 | Feedforward Neural Networks | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/danypetergmail/dl-business-analytics/blob/main/notebooks/ch04_ffn.ipynb) |
| 5 | Convolutional Neural Networks | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/danypetergmail/dl-business-analytics/blob/main/notebooks/ch05_cnn.ipynb) |
| 6 | Recurrent Networks and LSTMs | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/danypetergmail/dl-business-analytics/blob/main/notebooks/ch06_rnn_lstm.ipynb) |
| 7 | Large Language Models | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/danypetergmail/dl-business-analytics/blob/main/notebooks/ch07_llm.ipynb) |

---

## Prerequisites

- Basic Python (variables, loops, functions)
- Some familiarity with NumPy or pandas
- A free Google account (for Colab) or a local Python 3.9+ environment
- A free [Kaggle account](https://www.kaggle.com) for dataset downloads (Chapters 2–6)
- A free API key from OpenAI, Google Gemini, or Anthropic (Chapter 7 only)

---

## Repository Structure
```
dl-business-analytics/
├── notebooks/          # All chapter notebooks (.ipynb)
├── data/               # Local data files (gitignored — see each notebook for download instructions)
├── assets/             # Images and diagrams used in notebooks
├── requirements.txt    # All Python dependencies
└── README.md
```

---

## Datasets

All datasets used in this book are publicly available and free. Each notebook contains the exact download instructions for its dataset. Sources include Kaggle, the UCI ML Repository, torchvision built-ins, Hugging Face Hub, and other open data repositories.

---

## License

This book and all notebooks are released under the [MIT License](LICENSE).  
You are free to use, adapt, and share with attribution.
