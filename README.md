# 🗣️ Marwari Text-to-Speech System using NLP

> **Capstone Project · BSc (Hons.) Data Analytics & AI · IIS (Deemed to be a University), Jaipur · 2024–25**

---

## 📌 Problem Statement

In rural Rajasthan, many women cannot access health information because it is available only in Hindi — a language they may not read or fully understand. Language and literacy barriers prevent them from making informed health decisions.

**This project solves that problem** by translating Hindi health queries into Marwari text and audio, so that even non-literate rural women can listen to health information in their own language.

---

## ✅ Solution

### 🛠️ Technology Used

| Tool / Library | Purpose |
|---|---|
| Python | Core programming language for all logic |
| Streamlit | Web application interface — input, output, audio playback |
| Scikit-learn | Logistic Regression model + CountVectorizer for translation |
| gTTS (Google Text-to-Speech) | Converts Marwari text output into audio (MP3) |
| Pandas | Dataset handling, CSV storage, translation history |
| Pickle | Saves and loads the trained translation model |
| PyCharm | IDE used for development and testing |
| Google Colab | Model training environment |

### 🔄 What the Solution Does — Step by Step

1. User enters a Hindi health sentence in the web app
2. The trained Logistic Regression model translates it to Marwari
3. gTTS converts the Marwari text into an audio file (MP3)
4. The app plays the audio back so the user can listen to the translation
5. Every translation is saved to `translation_history.csv` with a timestamp for history tracking

### 💡 Impact

- Rural women who cannot read Hindi or Marwari text can **listen** to health information in their own dialect
- Covers 3 key health topics: **Hygiene Practices, Menstrual Health, Disease Prevention**
- Makes health awareness culturally and linguistically relevant for underserved communities
- Demonstrates how machine learning + text-to-speech can be combined for social good

---

## 📊 Dataset

| Detail | Value |
|---|---|
| Total sentences | 100 Hindi health sentences |
| Topics covered | Hygiene, Menstrual Health, Disease Prevention |
| Hindi source | Health awareness materials, government posters, local clinics |
| Marwari translations | Verified by native speakers and community health workers |
| Format | Excel → CSV (`Hindi_Marwari.csv`) |

**No publicly available Hindi-Marwari health dataset existed** — this dataset was manually collected and verified for this project.

---

## 🖥️ System Interface

The web app — named **SwasthyaBot** — was built using Streamlit:

- Input box for Hindi sentences
- "Translate + Play Audio" button
- Marwari translation displayed as text
- Audio playback control to listen to the Marwari translation
- Translation history table showing all past interactions

> *Screenshots of the interface are available in the `docs/` folder.*

---

## 📁 Repository Contents

| File / Folder | Description |
|---|---|
| `README.md` | Project overview and documentation |
| `docs/` | Project report and capstone presentation (PPT) |
| `dataset/` | Hindi-Marwari health sentences CSV used for model training |
| `screenshots and Images/` | Web app interface screenshots and UI images |
| `requirements.txt` | Python libraries required to run the project |

> **Note:** Source code is maintained privately.
> For a live demo or code walkthrough, connect via [LinkedIn](https://www.linkedin.com/in/teena-sharma-professional).

---

## 🔮 Future Scope

- Add **voice input** so users can speak Hindi questions instead of typing
- Convert into a **mobile app** for easier access on smartphones
- Expand the dataset with more health sentences to improve translation accuracy
- Add support for additional regional languages beyond Marwari

---

## 🎓 About This Project

**Teena Sharma**
BSc (Hons.) Data Analytics & AI — IIS (Deemed to be a University), Jaipur
Submitted to: Dr. Amita Sharma & Dr. Astha Pareek, Department of CS&IT

[LinkedIn](https://www.linkedin.com/in/teena-sharma-professional) · [GitHub](https://github.com/TEENA2004)
