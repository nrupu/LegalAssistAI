# 🧠 Legal Assist AI

An NLP-powered legal assistant that summarizes long legal texts using deep learning.

---

## 📂 Features
- 📑 **Text Summarization** using Transformer models (e.g., BART)
- 🧼 **Legal-specific Preprocessing** tailored for complex documents
- 📈 **Evaluation** using ROUGE metrics for summary quality
- 💻 **Simple CLI Tool** for quick and efficient summarization

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/NrupanMurali/LegalAssistAI.git
cd LegalAssistAI

# Install dependencies
pip install -r requirements.txt

# Run the summarization script
python src/model.py --input data/sample_docs/legal_doc.txt

## 📄 Example Output

**Input**:  
> "Whereas the parties have agreed to enter into an agreement..."

**Summary Output**:  
> "Parties agree to a contract for goods and services."

