# Chatgpt-Analysis

## 📌 Problem Statement

Every day we ask ChatGPT questions about:

* Learning new topics
* Coding problems
* Career doubts
* Financial decisions
* Personal thoughts
But we never stop to think:
> **“What do my ChatGPT conversations say about me?”**
This project analyzes **5,168 real ChatGPT messages** to understand:
* What topics I focus on
* When I am most active
* My learning behavior
* My emotional tone
* My productivity pattern
This project turns raw AI chat history into **simple visual insights**.

## Libraries Used

| Library                 | Purpose                              |
| ----------------------- | ------------------------------------ |
| **json**                | Reading exported ChatGPT data        |
| **pandas**              | Organizing messages into a dataset   |
| **re (regex)**          | Cleaning and extracting useful words |
| **matplotlib**          | Creating graphs                      |
| **seaborn**             | Styling graphs                       |
| **numpy**               | Numerical operations                 |
| **collections.Counter** | Word frequency counting              |
| **TextBlob**            | Sentiment analysis                   |
| **WordCloud**           | Visual word map                      |

##  How the Data Was Collected

1. Open **ChatGPT**
2. Go to **Settings → Data Controls**
3. Click **Export Data**
4. Download the file
5. Extract **`conversations.json`**
6. Use this file in the project

The program reads all conversations and keeps **only user messages**.

##  Basic NLP Steps

This project uses simple Natural Language Processing:

* Removed common words (like *the, is, and, how*)
* Extracted meaningful words (4+ letters)
* Counted word frequency
* Classified messages into topics:

  * Data Science
  * Finance
  * Learning
  * Personal
* Analyzed sentiment (positive / neutral / negative)

##  Graphs Used & Why

| Graph                              | Why it was used                             |
| ---------------------------------- | ------------------------------------------- |
| **Top Keywords (Bar Chart)**       | Shows most repeated ideas                   |
| **Topic Distribution (Pie Chart)** | Shows where mental focus goes               |
| **Sentiment Chart**                | Shows emotional tone of messages            |
| **Peak Hours Graph**               | Identifies most active time of day          |
| **Focus by Hour (Line Graph)**     | Shows when deeper thinking happens          |
| **Weekly Usage Graph**             | Shows study/work pattern                    |
| **Focus vs Mood (Scatter Plot)**   | Shows link between emotion and productivity |
| **WordCloud**                      | Visual map of thinking topics               |

---

#  Results & Insights

### Top Keywords

Most frequent words:

**DATA, FILE, PRINT, PYTHON, MODEL, USERS, CREATE, PRICE**

➡ This shows strong focus on **coding, systems, and data-related tasks**.

### Topic Distribution

| Topic                         | Share         |
| ----------------------------- | ------------- |
| OTHER                         | 66.5%         |
| DATA SCIENCE                  | 26.4%         |
| Learning / Finance / Personal | Smaller share |

📌 Insight: ChatGPT is mainly used for **technical learning and problem solving**.

### Sentiment Analysis

* Majority messages are **Neutral**
* Some **Positive**
* Very few **Negative**

Overall sentiment: **+0.10 (slightly positive)**
➡ ChatGPT is used more for learning than emotional expression.

### Peak Activity Time

Highest usage happens around **5 AM**.

➡ Indicates early study or work habit.

###  Focus Score

Average focus score: **0.93 / 3**

➡ Mix of deep learning questions and general usage.
###  Weekly Pattern

More activity on **weekdays** than weekends.

➡ ChatGPT is used mainly for **study/work**, not entertainment.
###  Focus vs Mood

Focus stays active even during neutral mood.

➡ Learning continues regardless of emotional state.

### 🌩 WordCloud Insight

Large words include:

**DATA, FILE, PRINT, USERS, MODEL, PYTHON, RECOVERY**

➡ Confirms **technical and analytical thinking pattern**.

#  Conclusion

This project shows that ChatGPT conversation history can reveal:

* Learning interests
* Technical focus
* Productivity timing
* Emotional tone
* Work discipline

Using simple NLP and data visualization, we can turn AI chat data into **personal behavior insights**.

ChatGPT here works as a **learning and productivity tool**, not just a chatbot.

## 👨‍💻 Author

**Ansh Kambli**
Project built to understand personal learning and thinking patterns using AI conversation data.


If you want, next I’ll write a **LinkedIn post** that explains this project in a way recruiters love.
