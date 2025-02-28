# 📄 Interactive Summarization of Scientific Papers  

## 📌 Project Overview  
This project focuses on **interactive summarization of scientific papers** using **NLP and graph-based algorithms**. It specifically targets biomedical literature, leveraging **BioBERT** for domain-specific abstractive summarization and **graph-based ranking algorithms** (PageRank & TextRank) to enhance coherence.  

## 🔥 Features  
- **BioBERT-based abstractive summarization** for biomedical texts.  
- **Graph-based sentence ranking** using PageRank and TextRank.  
- **Evaluation using ROUGE and Cosine Similarity** for accuracy.  
- **Optimized for PubMed dataset**, handling complex biomedical terminology.  
- **Fine-tuned model for improved summary quality** over extractive baselines.  

## 🛠️ Installation & Setup  
### Prerequisites  
- Python 3.8+  
- GPU (recommended for fine-tuning)  
- Required libraries: `transformers`, `torch`, `pandas`, `numpy`, `networkx`, `nltk`, `matplotlib`  

### Installation Steps  
1. **Clone the Repository**  
   ```bash
   git clone https://github.com/your-username/interactive-summarization.git  
   cd interactive-summarization  
   ```  
2. **Create a Virtual Environment**  
   ```bash
   python -m venv venv  
   source venv/bin/activate  # On Windows use: venv\Scripts\activate  
   ```  
3. **Install Dependencies**  
   ```bash
   pip install -r requirements.txt  
   ```  
4. **Run the Notebook**  
   ```bash
   jupyter notebook  
   ```  
5. **Open `Interactive_Summarization_of_Scientific_papers.ipynb` and execute the cells.**  

## 📖 Usage  
1. **Input a scientific paper (PubMed abstract format).**  
2. **Preprocess text** (cleaning, tokenization using BioBERT’s WordPiece tokenizer).  
3. **Generate an abstractive summary** using fine-tuned BioBERT.  
4. **Rank sentences** using PageRank or TextRank.  
5. **Evaluate summary quality** using ROUGE scores and Cosine Similarity.  

## 📚 Technologies Used  
- **BioBERT (Biomedical BERT) for text summarization**  
- **Graph-based ranking** (PageRank & TextRank)  
- **Hugging Face Transformers** for model fine-tuning  
- **PyTorch for deep learning training**  
- **NetworkX for sentence graph construction**  

## 🚀 Performance Metrics  
- **ROUGE-1, ROUGE-2, ROUGE-L** for lexical similarity.  
- **Cosine Similarity** for semantic accuracy.  
- **Fine-tuned BioBERT improved summary coherence** over extractive baselines.  

## 👩‍💻 Contributors  
- **Shwejan Shsahank Keerthi** 
