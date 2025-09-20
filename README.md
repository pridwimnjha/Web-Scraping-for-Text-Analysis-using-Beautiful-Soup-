# NLP with BeautifulSoup and OCR using Tesseract

## 📌 Overview

This repository demonstrates two essential techniques for data extraction using Python:

1. **Web Scraping with BeautifulSoup**

   * Extracts product details (title, price, rating) from Amazon search results.
   * Uses custom headers to mimic browser behavior and bypass anti-scraping measures.

2. **Optical Character Recognition (OCR) with Tesseract**

   * Extracts text from images using the **Tesseract OCR engine** via `pytesseract`.
   * Uses **Pillow** for preprocessing images.

---

## 🛠️ Technologies & Libraries Used

* **Python 3.x**
* **Requests** – HTTP requests for scraping
* **BeautifulSoup (bs4)** – HTML parsing
* **time** – polite scraping delays
* **pytesseract** – OCR wrapper
* **Pillow** – Image handling
* **Tesseract OCR** – external OCR engine

---

## 📂 Contents

* `NLP_Beautiful Soup.ipynb` – Jupyter notebook with scraping + OCR examples.
* **Web Scraping Section** – Extract laptop listings from Amazon.
* **OCR Section** – Extract text from images.

---

## ⚙️ Installation & Setup

### 1. Clone Repository

```bash
git clone https://github.com/your-username/NLP_BeautifulSoup_OCR.git
cd NLP_BeautifulSoup_OCR
```

### 2. Install Dependencies

```bash
pip install requests beautifulsoup4 pillow pytesseract
```

### 3. Install Tesseract OCR

* **Linux (Ubuntu/Debian):**

```bash
sudo apt-get install tesseract-ocr
```

* **Windows:** [Download installer](https://github.com/UB-Mannheim/tesseract/wiki)
* **Mac (Homebrew):**

```bash
brew install tesseract
```

---

## 🚀 Usage

### Run Notebook

```bash
jupyter notebook NLP_Beautiful\ Soup.ipynb
```

### Example Output

#### 🔍 Web Scraping (Amazon Laptop Listings)

<img width="769" height="378" alt="image" src="https://github.com/user-attachments/assets/a8a22005-357a-4aeb-a489-280fc5da0a1d" />

#### 🖼️ OCR (Image to Text)

Input Image →
<img width="362" height="266" alt="image" src="https://github.com/user-attachments/assets/d604c065-1c81-4473-903a-8fd23214ce82" />


Extracted Text:

```
MAKE TEXT
STAND OUT FROM
, BACKGROUNDS 
```

<img width="220" height="140" alt="image" src="https://github.com/user-attachments/assets/84ea44e4-c7c2-4000-bc5a-6e703dc71a04" />


## 📊 Observations & Learnings

* **Web Scraping** needs handling of anti-bot measures and changing HTML structures.
* **OCR** accuracy improves with clear, high-resolution images.
* Together, these tools enable powerful **automation in data collection & text recognition**.

