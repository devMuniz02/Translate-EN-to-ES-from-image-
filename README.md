# Translate EN to ES from image

## 📌 Overview
This project extracts text from images using **EasyOCR** and translates the extracted text from **English to Spanish** using a **Hugging Face NLP model** (`Helsinki-NLP/opus-mt-en-es`). The results are displayed in a **side-by-side format**, with:
- **Left:** The original image.
- **Center:** The extracted English text.
- **Right:** The translated Spanish text.

## 🛠 Requirements
Make sure you have the following installed:
- Python 3.7+
- Required Python libraries:
  ```sh
  pip install easyocr transformers opencv-python matplotlib numpy
  ```

## 📜 Files in Repository
- `Translator.ipynb`: Jupyter Notebook containing the complete implementation of the OCR and translation tool.
- `Text.png`: Sample image used for text extraction and translation.
- `README.md`: Documentation for the project.
- `LICENSE`: License file for the project.

## 🚀 How It Works
1. **Extract text from an image** using `EasyOCR`.
2. **Translate the extracted text** from **English to Spanish** using a pre-trained NLP model.
3. **Display a figure** with three sections:
   - **Original image**
   - **Extracted text in English**
   - **Translated text in Spanish**

## 📌 Example Output
If the image (`Text.png`) contains:
```
Hello, how are you?
This is a test image for OCR.
```
The console output will be:
```
Extracted Text (English):
Hello, how are you?
This is a test image for OCR.

Translated Text (Spanish):
Hola, ¿como estás?
Esta es una imagen de prueba para OCR.
```
And the **displayed figure** will show:
- **Left:** Original image.
- **Center:** Extracted text in English.
- **Right:** Translated text in Spanish.

---

### Check Out My Other Projects
Explore more of my AI and ML work [here](https://github.com/devMuniz02/AI-ML-Code-and-projects/).

### License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

