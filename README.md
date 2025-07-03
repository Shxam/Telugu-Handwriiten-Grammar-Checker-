# 🧠 Telugu OCR and Grammar Checker 🇮🇳

This project is a complete **Telugu text extraction and grammar checking tool** implemented in a Jupyter Notebook: `telugu_grammar_checker.ipynb`.

It performs the following:
- 🖼️ Reads an image containing Telugu text.
- 🎯 Preprocesses the image for clarity.
- 🔎 Extracts text using **EasyOCR**.
- 🧠 Performs **rule-based grammar analysis** on the extracted Telugu text.

---

## 📂 File Structure

```bash
├── telugu_grammar_checker.ipynb   # Main notebook with all logic
├── README.md                      # Project documentation
Thanks! Here's your updated `README.md` specifically for the file named **`telugu_grammar_checker.ipynb`**:

---

````markdown
# 🧠 Telugu OCR and Grammar Checker 🇮🇳

This project is a complete **Telugu text extraction and grammar checking tool** implemented in a Jupyter Notebook: `telugu_grammar_checker.ipynb`.

It performs the following:
- 🖼️ Reads an image containing Telugu text.
- 🎯 Preprocesses the image for clarity.
- 🔎 Extracts text using **EasyOCR**.
- 🧠 Performs **rule-based grammar analysis** on the extracted Telugu text.

---

## 📂 File Structure

```bash
├── telugu_grammar_checker.ipynb   # Main notebook with all logic
├── README.md                      # Project documentation
````

---

## 🔧 Dependencies

Install all required packages using pip:

```bash
pip install easyocr opencv-python matplotlib numpy
```

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/telugu-ocr-grammar-checker.git
cd telugu-ocr-grammar-checker
```

2. Open the notebook:

```bash
jupyter notebook telugu_grammar_checker.ipynb
```

3. Modify the image path inside the notebook:

```python
image_path = 'C:/Users/SHAM/OneDrive/Documents/xx.jpg'
```

4. Run all cells to:

   * Preprocess image
   * Extract Telugu text using OCR
   * Check grammar using custom rule-based logic

---

## 🔤 Telugu Grammar Checker Features

The `TeluguGrammarChecker` class performs:

* ✅ **Sentence Splitting**
* ✅ **Sentence Structure Validation** (e.g., verb should be at the end)
* ✅ **Subject-Verb Agreement** (e.g., "నేను" must match with "తున్నాను")
* ✅ **Tense Consistency Detection**
* ✅ **Case Marker Misuse Detection**
* ✅ **Particle Position Validation**

---

## ✅ Sample Output

```bash
Grammar Errors Found:

Sentence 1
Word: అతనికి
Error Type: case_marker
Suggestion: Multiple case markers detected

Sentence 2
Error Type: structure
Suggestion: Sentence should end with a verb
```

---

## 📌 Future Enhancements

* [ ] Add spell checking with Indic NLP
* [ ] Support complex/compound sentences
* [ ] Export grammar report to CSV or PDF
* [ ] Web UI using Streamlit or Flask

---

## 📜 License

MIT License – free to use and modify.

---

## 👤 Author

**Pamarthi Sai Narasimham**

---

## 🙏 Acknowledgements

* [EasyOCR](https://github.com/JaidedAI/EasyOCR)
* [OpenCV](https://opencv.org/)
* Native Telugu grammar knowledge base

---

```

---

Let me know if you'd like this in `.md` file format or want a version with badge-style headers (for GitHub Pages/portfolio display).
```
