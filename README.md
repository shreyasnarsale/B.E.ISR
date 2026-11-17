# Information Storage and Retrieval (ISR) – Lab Practice III (414446)

## Savitribai Phule Pune University, Pune

**Final Year – Information Technology (2019 Course)**

**Subject:** 414446 – Lab Practice III: Information Storage and Retrieval (ISR)

---

## 📖 About

This repository contains practical assignments for **Information Storage and Retrieval (ISR) – Lab Practice III (414446)** prescribed by Savitribai Phule Pune University (SPPU), Pune, for Final Year Information Technology students under the 2019 Course Curriculum.

The practicals focus on Information Retrieval, Document Processing, Clustering, Search Techniques, Performance Evaluation, Image Feature Extraction, Web Crawling, Weather Information Retrieval, and Recommender Systems using Python.

## 🎯 Objectives

- Understand the fundamentals of Information Storage and Retrieval.
- Implement document processing and conflation algorithms.
- Perform document clustering using the Single-pass Algorithm.
- Understand and implement inverted file indexing.
- Evaluate Information Retrieval systems using Precision, Recall, F-measure, and E-measure.
- Perform feature extraction and histogram visualization for 2D color images.
- Develop web crawlers to extract information from e-commerce websites.
- Retrieve live weather information using Python.
- Understand and implement recommender systems.

## 🛠️ Technologies & Tools

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| NumPy | Numerical Computation |
| Pandas | Data Manipulation |
| Matplotlib | Data Visualization |
| NLTK | Natural Language Processing |
| Scikit-learn | Machine Learning |
| OpenCV | Image Processing |
| BeautifulSoup | Web Scraping |
| Requests | HTTP Requests |
| Jupyter Notebook | Development Environment |

## 📚 Practical Assignments

### Group A – CO1, CO2, CO3

#### Experiment 1: Implementation of Conflation Algorithm

**Aim:** Implement the Conflation Algorithm to generate a document representative of a given text file.

**Implementation:**
- Read and process a text document.
- Perform text preprocessing.
- Apply conflation techniques to identify related word forms.
- Generate a representative document containing important terms.

**Expected Output:**
- Processed text document.
- Conflated words.
- Document representative.

#### Experiment 2: Single-pass Algorithm for Document Clustering

**Aim:** Implement the Single-pass Algorithm for clustering files by considering 4 to 5 text documents.

**Implementation:**
- Load 4 to 5 text files.
- Preprocess the documents.
- Extract document features.
- Calculate similarity between documents.
- Apply the Single-pass Clustering Algorithm.
- Group similar documents into clusters.

**Expected Output:**
- Document similarity results.
- Generated document clusters.

#### Experiment 3: Document Retrieval using Inverted Files

**Aim:** Implement a program for retrieving documents using inverted files.

**Implementation:**
- Read a collection of documents.
- Tokenize and preprocess the documents.
- Generate an inverted index.
- Store terms and their corresponding document references.
- Search for user-provided query terms.
- Retrieve relevant documents.

**Expected Output:**
- Inverted index.
- Search query results.
- Retrieved documents.

---

### Group B – CO3, CO5

#### Experiment 4: Calculation of Precision and Recall

**Aim:** Implement a program to calculate Precision and Recall for a sample Information Retrieval system.

**Given:**
- Answer Set (A)
- Query (q1)
- Relevant Documents to Query (Rq1)

**Implementation:**
- Identify retrieved documents.
- Identify relevant documents.
- Calculate True Positives, False Positives, and False Negatives.
- Calculate Precision and Recall.

**Formulas:**

Precision:

\[
Precision = \frac{TP}{TP+FP}
\]

Recall:

\[
Recall = \frac{TP}{TP+FN}
\]

**Expected Output:**
- Precision value.
- Recall value.

#### Experiment 5: Calculation of F-measure and E-measure

**Aim:** Write a program to calculate the Harmonic Mean (F-measure) and E-measure using the previous Precision and Recall example.

**Implementation:**
- Use the Precision and Recall values obtained in Experiment 4.
- Calculate the harmonic mean.
- Calculate the E-measure.
- Display the evaluation results.

**Formulas:**

F-measure:

\[
F = \frac{2PR}{P+R}
\]

E-measure:

\[
E = 1-F
\]

Where:
- P = Precision
- R = Recall
- F = F-measure

**Expected Output:**
- F-measure value.
- E-measure value.

#### Experiment 6: Feature Extraction in 2D Color Images

**Aim:** Implement a program for feature extraction in 2D color images using features such as color and texture.

**Implementation:**
- Load an input color image.
- Preprocess the image.
- Extract color features.
- Extract texture features.
- Calculate feature values.
- Plot histograms for the extracted features.

**Expected Output:**
- Input image.
- Extracted image features.
- Color and texture histograms.

---

### Group C – CO4, CO5

#### Experiment 7: Web Crawler for E-commerce Websites

**Aim:** Build a Python-based web crawler to retrieve product information and links from an e-commerce website.

**Implementation:**
- Identify the target e-commerce website.
- Send HTTP requests to the website.
- Parse HTML content using BeautifulSoup.
- Extract product information.
- Retrieve product names, prices, and links.
- Display or store the extracted information.

**Expected Output:**
- Product information.
- Product prices.
- Product URLs and links.

*Note: Follow the website's terms of service, robots.txt, and applicable crawling restrictions.*

#### Experiment 8: Live Weather Report using Python

**Aim:** Write a Python program to retrieve the live weather report of a given city.

**Weather Parameters:**
- Temperature
- Wind Speed
- Weather Description
- Weather Condition

**Implementation:**
- Accept a city name from the user.
- Connect to a weather API.
- Retrieve current weather information.
- Process the API response.
- Display the weather report.

**Expected Output:**
- City name.
- Current temperature.
- Wind speed.
- Weather description and condition.

#### Experiment 9: Case Study on Recommender Systems

**Aim:** Study and implement a case study based on a Recommender System.

**Suggested Domains:**
- Product Recommendation System.
- Doctor Recommendation System.
- Product Price Recommendation System.
- Music Recommendation System.

**Implementation:**
- Understand the concept of Recommender Systems.
- Collect or use a suitable dataset.
- Analyze user preferences and item characteristics.
- Study recommendation techniques.
- Generate recommendations based on the selected domain.
- Evaluate the recommendation results.

**Expected Output:**
- Recommender System case study.
- Recommendation results.
- Analysis of the selected recommendation technique.

---

## 📂 Repository Structure

```text
Information-Storage-and-Retrieval/
│
├── Group-A/
│   ├── Experiment-01-Conflation-Algorithm/
│   ├── Experiment-02-Single-Pass-Clustering/
│   └── Experiment-03-Inverted-File-Retrieval/
│
├── Group-B/
│   ├── Experiment-04-Precision-and-Recall/
│   ├── Experiment-05-F-Measure-and-E-Measure/
│   └── Experiment-06-Image-Feature-Extraction/
│
├── Group-C/
│   ├── Experiment-07-Web-Crawler/
│   ├── Experiment-08-Live-Weather-Report/
│   └── Experiment-09-Recommender-System/
│
└── README.md
```

*Note: Each experiment folder can contain Python source code (.py), Jupyter Notebook (.ipynb), datasets, sample input files, and output screenshots.*

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/shreyasnarsale/Information-Storage-and-Retrieval.git
```

### 2. Navigate to the Project Directory

```bash
cd Information-Storage-and-Retrieval
```

### 3. Install Required Libraries

```bash
pip install numpy pandas matplotlib
pip install nltk scikit-learn
pip install opencv-python
pip install requests beautifulsoup4
pip install jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the required experiment notebook and execute the cells sequentially.

## 📊 Course Outcomes (CO Mapping)

| Group | Course Outcomes | Experiments |
|---|---|---|
| Group A | CO1, CO2, CO3 | Experiments 1, 2, 3 |
| Group B | CO3, CO5 | Experiments 4, 5, 6 |
| Group C | CO4, CO5 | Experiments 7, 8, 9 |

## 🎓 Course Information

| Details | Information |
|---|---|
| University | Savitribai Phule Pune University, Pune |
| Course | Final Year Information Technology |
| Curriculum | 2019 Course |
| Subject Code | 414446 |
| Subject Name | Lab Practice III – Information Storage and Retrieval (ISR) |
| Assignment Groups | Group A, Group B, Group C |
| Total Experiments | 9 |

## 📚 References

- [NLTK Documentation](https://www.nltk.org/)
- [Scikit-learn Documentation](https://scikit-learn.org/)
- [OpenCV Documentation](https://docs.opencv.org/)
- [BeautifulSoup Documentation](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [Python Official Documentation](https://docs.python.org/3/)
- [Matplotlib Documentation](https://matplotlib.org/)
- [Requests Documentation](https://requests.readthedocs.io/)

## 👨‍💻 Author

**Shreyas Narsale**

- GitHub: [@shreyasnarsale](https://github.com/shreyasnarsale)

---

