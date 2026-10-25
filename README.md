# Netflix Data Profiling and Analytics Project 🎬📊

An end-to-end Data Science project solving 4 critical business use cases on the Kaggle Netflix dataset using **Pandas, Seaborn, and NLP (TF-IDF)**.

---

## 🛠️ Step-by-Step Data Science Workflow

1. **Data Ingestion & Profiling:** Inspected a dataset containing **8,807 entries** and 12 features. Identified structural metadata types (`int64` and `str`).
2. **Advanced Data Cleaning:** Handled extensive missing text values in `director`, `cast`, and `country` by strategically imputing them with `'Unknown'` to retain data integrity. Dropped rows with sparse null values in `date_added`, `rating`, and `duration`.
3. **Exploratory Data Analysis (EDA):** Leveraged data visualization to extract historical business insights.

---

## 💡 Solutions to Kaggle Interesting Task Ideas

### 📍 Task 1: Understanding Content Distribution by Country
* **Insight:** Modeled content counts geographically. The **United States** leads with over 2,800 titles, while **India** holds a strong 2nd position globally with nearly 1,000 titles.

### 📍 Task 2: Identifying Similar Content (Content-Based Recommendation)
* **Insight:** Implemented an NLP-driven solution using a **TF-IDF Vectorizer** to filter English stop-words and vectorized the plot summaries. Calculated a **Cosine Similarity** matrix to build a functioning Recommendation System. For example, inputting *'Transformers Prime'* successfully outputs its corresponding sequels and top anime matches.

### 📍 Task 3: Network Analysis of Directors and Actors
* **Insight:** Conducted a Co-occurrence Network Analysis to unpack collaborations. **Rajiv Chilaka** emerged as the top director, frequently collaborating with voice artists like *Julie Tejwani* and *Jigna Bhardwaj* (17 times each).

### 📍 Task 4: Content Trend Focus (Movies vs TV Shows)
* **Insight:** Built a time-series line graph filtering modern data (2010-2021). The data proves a massive structural shift: while movie uploads peaked in 2018 (~800), Netflix has aggressively focused on **TV Shows in recent years**, with show releases officially overtaking movies by 2021.

---

## 🧠 Technologies Used
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Seaborn, Matplotlib
* **Machine Learning & NLP:** Scikit-Learn (TfidfVectorizer, cosine_similarity)

