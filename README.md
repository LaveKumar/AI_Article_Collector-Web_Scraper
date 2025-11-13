# 📰 AI Article Collector – Web Scraper 🤖

This project is a **Python automation script** that scrapes and saves the latest Artificial Intelligence (AI) articles from **The Guardian** using their official API and **BeautifulSoup**.  

The goal is simple — to streamline access to **AI-focused content** for research, insights, and daily learning.  

---

## 🚀 Project Highlights

Here’s what this project accomplishes 👇  

1️⃣ **Dynamic Folder Creation** – Automatically creates timestamped folders to neatly organize articles by date and time.  
2️⃣ **API Integration** – Connects with *The Guardian’s open API* to fetch the latest AI-related articles automatically.  
3️⃣ **Data Extraction** – Uses **BeautifulSoup** to parse HTML content and extract article titles and body text efficiently.  
4️⃣ **Automated Saving** – Saves each article as a `.txt` file inside structured directories for quick access and reference.  
5️⃣ **Error Handling & Reliability** – Handles request failures gracefully to ensure consistent and reliable scraping.

---

## 🧠 Tech Stack

- **Python** 🐍  
- **Requests** – for API and web requests  
- **BeautifulSoup (bs4)** – for parsing HTML content  
- **OS & Datetime** – for file handling and folder organization  

---

## 📂 Folder Structure

AI_Article_Collector-Web_Scraper-
│
├── Saved_Articles/
│ ├── 12_45_13_11_2025/
│ │ ├── article_0.txt
│ │ ├── article_1.txt
│ │ └── ...
│
├── main.py
├── requirements.txt
└── README.md


Each folder inside `Saved_Articles/` is automatically generated with the current timestamp, ensuring every scraping session is stored separately.

---

## ⚙️ How to Run

1️⃣ Clone this repository:

  git clone https://github.com/LaveKumar/AI_Article_Collector-Web_Scraper.git

2️⃣ Navigate into the project directory:

  cd AI_Article_Collector-Web_Scraper


3️⃣ Install dependencies:

  pip install -r requirements.txt


4️⃣ Run the script:

  python3 app.py


5️⃣ Check your Saved_Articles/ folder — your freshly scraped AI articles will be there!

