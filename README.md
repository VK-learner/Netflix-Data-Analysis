# 🎬 Netflix Data Analysis

![Netflix Banner](images/netflix.png)

An exploratory data analysis (EDA) project on Netflix movies dataset using Python.

---

## 📊 Dataset
| Field | Details |
|---|---|
| Source | TMDB Movie Database |
| File | `mymoviedb.csv` |
| Rows | 9,827 |
| Columns | 9 |

**Columns:** `Release_Date`, `Title`, `Overview`, `Popularity`, `Vote_Count`, `Vote_Average`, `Original_Language`, `Genre`, `Poster_Url`

---

## 🛠️ Tech Stack
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-4c72b0?style=flat)
![Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=flat&logo=googlecolab&logoColor=white)

---

## 📁 Project Structure
```
Netflix-Data-Analysis/
│
├── data/
│   └── mymoviedb.csv
│
├── notebooks/
│   └── movie data analysis netflix.ipynb
│
├── images/
│   └── netflix.png
│
└── README.md
```

---

## 🔍 Analysis Questions
- **Q1:** What is the most frequent genre in the dataset?
- **Q2:** What genres have the highest votes?
- **Q3:** Which movie has the highest popularity and what is its genre?
- **Q4:** Which movie has the lowest popularity and what is its genre?
- **Q5:** Which year had the most filmed movies?

---

## 💡 Key Findings
- 🎭 **Drama** is the most frequent genre, appearing 14%+ of the time across 19 genres
- 🕷️ **Spider-Man: No Way Home** (2021) has the highest popularity — Action, Adventure, Science Fiction
- 🎵 **The United States vs. Billie Holiday** (2021) has the lowest popularity — Music, Drama, History
- 📅 **2020** had the highest number of movies released in the dataset
- ⭐ **25.5%** of movies fall in the popular vote category, dominated by Drama

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/VK-learner/Netflix-Data-Analysis.git
```

2. Mount Google Drive in Colab:
```python
from google.colab import drive
drive.mount('/content/drive')

import os
os.chdir('/content/drive/MyDrive/Colab Notebooks/Netflix-Data-Analysis')
```

3. Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn
```

4. Open and run the notebook:
```
notebooks/movie data analysis netflix.ipynb
```

---

## 📈 Visualizations
- Genre distribution bar chart
- Vote average distribution chart
- Release year histogram

---

## 👤 Author
**VK-learner**
[![GitHub](https://img.shields.io/badge/GitHub-VK--learner-black?logo=github)](https://github.com/VK-learner)

---

## 📄 License
This project is open source and available under the [MIT License](LICENSE).
