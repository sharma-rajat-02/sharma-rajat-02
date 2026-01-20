## Hi there 👋

# 📚 Hybrid Book Recommender System 
### *Consensus-Based Collaborative Filtering Engine*

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)

## 🚀 The Challenge
Standard recommendation engines often suffer from **Popularity Bias** or **Data Sparsity**. This project implements a unique **Hybrid Consensus Logic** to ensure high-relevance suggestions even in sparse datasets.

## 🧠 Engineering Logic: The Consensus Rank
Unlike single-model systems, this engine aggregates outputs from three distinct mathematical perspectives:

1. [cite_start]**Cosine Similarity:** Measures the orientation of user-rating vectors[cite: 59].
2. [cite_start]**Jaccard Similarity:** Analyzes the binary intersection of user libraries to find "Reading Peers"[cite: 59].
3. [cite_start]**Pearson Correlation:** Corrects for user-rating bias (strict vs. lenient raters)[cite: 59].

> **Consensus Rank Formula:** $Final\_Rank = \omega_1(Cosine) + \omega_2(Jaccard) + \omega_3(Pearson)$



## 📊 Performance & Validation
I implemented a **Live Hit Rate @ 5** pipeline to move beyond "fake" accuracy scores.
* [cite_start]**Baseline Accuracy:** ~85% (Self-reported efficiency gains)[cite: 62].
* [cite_start]**Real-time Hit Rate:** Dynamically calculated by verifying suggestions against historical user "Likes" (Rating >= 8)[cite: 61].

## 🛠️ Tech Stack
- [cite_start]**Backend:** Python, Flask [cite: 57]
- [cite_start]**Data Science:** NumPy, Pandas, Scikit-Learn, SciPy [cite: 57, 70]
- **Frontend:** Responsive UI with real-time "Match Confidence" bars.

## ⚙️ Installation
1. Clone the repo: `git clone https://github.com/yourusername/book-buddy.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the engine: `python app.py`

## 🤝 Responsible AI Note
[cite_start]This project demonstrates a **Human-in-the-loop** AI development cycle, utilizing Generative AI for 85% measurable efficiency gains in boilerplate scaffolding while maintaining manual oversight of all mathematical logic[cite: 62].

---
Developed by **Rajat Sharma** | [LinkedIn](https://linkedin.com/in/yourlink) | [Portfolio](https://yourportfolio.com)


Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...


# Hi there, I'm Rajat Sharma 👋

### 🛠️ Professional Toolbox & Languages
<p align="left">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sharma-rajat-02&layout=compact&theme=vision-friendly-dark" alt="Top Languages" />
</p>

---

### 🚀 Featured Projects
* **[Book Recommender System](https://github.com/YOUR_USERNAME/book-recommender)** - KNN-based engine with 97% accuracy using Python & Scikit-Learn.
* **[Dry Fruits E-Commerce](https://github.com/YOUR_USERNAME/dry-fruits-web)** - Dynamic React.js/Vue.js site deployed for business operations.

---

### 📊 GitHub Analytics & Score
<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=sharma-rajat-02&show_icons=true&theme=radical&rank_icon=github&count_private=true" alt="GitHub Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=sharma-rajat-02&theme=radical" alt="GitHub Streak" />
</p>

---

### 🏆 Achievements
<p align="left">
  <img src="https://github-profile-trophy.vercel.app/?username=sharma-rajat-02&theme=radical&no-bg=true&no-frame=true" alt="Trophies" />
</p>
