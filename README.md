# 📊 Matplotlib — Data Visualization with Python

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange?style=flat)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-013243?style=flat&logo=numpy)
![Google Colab](https://img.shields.io/badge/Google%20Colab-Notebook-F9AB00?style=flat&logo=googlecolab)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat)

> A hands-on Python notebook covering **Matplotlib from basics to advanced** — built using real-world cricket data (Sachin, Kohli, Sehwag) and student exam data for intuitive learning.

---

## 📌 Topics Covered

| # | Topic | What You Learn |
|---|-------|----------------|
| 1 | **Line Plots** | Basic plotting, axis labels, titles |
| 2 | **Multiple Lines** | Comparing datasets on one plot |
| 3 | **Format Strings** | Color, marker, linestyle shortcuts |
| 4 | **Styling** | `ggplot`, `seaborn`, XKCD comic mode |
| 5 | **Bar Charts** | Vertical, horizontal, side-by-side bars |
| 6 | **Pie Charts** | Explode, shadow, autopct, wedgeprops |
| 7 | **Stack Plots** | Area chart for cumulative data |
| 8 | **Histograms** | Distributions, bins, `axvline` |
| 9 | **Scatter Plots** | Color maps, annotations, multiple groups |
| 10 | **Subplots** | Grid layouts, `plt.subplots()`, looping |

---

## 🏏 Datasets Used

### Cricket Runs (1990–2010)
Used to demonstrate line plots, bar charts, and comparisons:
- **Sachin Tendulkar** — Yearly run data
- **Virat Kohli** — Career growth visualization
- **Virender Sehwag** — Peak performance analysis

### Student Exam Data
Used in scatter plots to show relationship between **study hours vs exam scores** — with Class A vs Class B comparison.

### YouTube Viewer Age Data
Used in histograms to show **age distribution** across 100 viewers.

### Daily Activity Data
Used in stack plots to track **weekly time spent** on studying, playing, watching TV, and sleeping.

---

## 🖼️ Chart Types Preview

```
Line Plot     →  plt.plot()
Bar Chart     →  plt.bar() / plt.barh()
Pie Chart     →  plt.pie()
Histogram     →  plt.hist()
Scatter Plot  →  plt.scatter()
Stack Plot    →  plt.stackplot()
Subplots      →  plt.subplot() / plt.subplots()
```

---

## ✨ Key Concepts Practiced

- `plt.xlabel()`, `plt.ylabel()`, `plt.title()` — Labeling charts
- `plt.legend()`, `plt.grid()`, `plt.tight_layout()` — Polishing plots
- Format strings like `'ro--'`, `'g^:'` — Quick styling
- `plt.style.use('ggplot')` — Theme switching
- `plt.xkcd()` — Comic-style plots for fun!
- `plt.text()` / `plt.annotate()` — Adding value labels
- `plt.axvline()` — Marking average/threshold lines
- `fig.savefig('plot.png')` — Saving plots as images
- `plt.colorbar()` — Color scale for scatter plots
- `np.arange()` — Positioning bars side-by-side

---

## 🛠️ Tech Stack

- **Python 3**
- **Matplotlib** — Core visualization library
- **NumPy** — Numerical data handling
- **Google Colab** — Development environment

---

## 🚀 How to Run

### Option 1 — Google Colab (Recommended)
Click the badge below to open directly in Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bhupendra-ds27/matplotlib-practice/blob/main/Matplotlib.ipynb)

### Option 2 — Run Locally
```bash
# Clone the repo
git clone https://github.com/bhupendra-ds27/matplotlib-practice.git
cd matplotlib-practice

# Install dependencies
pip install matplotlib numpy

# Open the notebook
jupyter notebook Matplotlib.ipynb
```

---

## 📁 Repository Structure

```
matplotlib-practice/
│
├── Matplotlib.ipynb      # Main notebook with all examples
└── README.md             # Project documentation
```

---

## 🎯 Who is this for?

- 🐣 **Beginners** starting with data visualization in Python
- 📚 **Students** learning Data Science or Machine Learning
- 💼 Anyone building their **Data Science portfolio**

---

## 👨‍💻 Author

**Bhupendra** — [@bhupendra-ds27](https://github.com/bhupendra-ds27)

---

⭐ **If this helped you, please star the repo!** It motivates me to keep learning and sharing.
