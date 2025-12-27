# English to Hindi Translation using MarianMT

This project demonstrates English to Hindi translation using a **pre-trained MarianMT Transformer model** from HuggingFace.  
It also includes evaluation using **BLEU score** and an interactive **Gradio UI** for real-time translation.

---

## Project Overview

The workflow of this project includes:

1. **Installing required packages**: `transformers`, `sentencepiece`, `nltk`, `gradio`
2. **Loading the pre-trained MarianMT model and tokenizer**
3. **Extracting the IIT Bombay English-Hindi corpus** from a zip file
4. **Loading and preprocessing English and Hindi sentences**
5. **Generating translations** for sample sentences
6. **Evaluating translations** using BLEU score
7. **Creating a Gradio web interface** for interactive translation

---

## Dataset

This project uses the **IIT Bombay English-Hindi Parallel Corpus**.  
- The corpus contains aligned English-Hindi sentence pairs.  
- Dataset is **not included** in this repository due to size restrictions.  
- Download it from: [IIT Bombay English-Hindi Corpus](https://www.cfilt.iitb.ac.in/iitb_parallel/)

**Expected folder structure after extraction:**

parallel_dataset/
└── parallel-n/
├── IITB.en-hi.en
└── IITB.en-hi.hi


---

## Installation

1. Clone this repository:

```bash
git clone https://github.com/Swathi-S2004/English-Hindi-Translation
cd English-Hindi-Translation

2. Install required packages:

pip install -r requirements.txt

Alternatively, if running in Google Colab, the notebook installs the packages automatically.

## Usage

1. Place the downloaded dataset zip file (parallel.zip) in the same folder as the notebook.

2. Open the notebook English_Hindi_Translation.ipynb in Colab or VS Code.

3. Run all cells sequentially.

4. Interact with the Gradio interface to input English sentences and get Hindi translations in real-time.

---

## Evaluation

1.The BLEU score is calculated for a small subset of sentences to evaluate translation quality.

2. BLEU measures how close the model translations are to the reference human translations.

---

## Demo Example

English Input: I love learning artificial intelligence
Predicted Hindi Output: मुझे कृत्रिम बुद्धि सीखना अच्छा लगता है

---

## Author

Swathi Selvaraj
