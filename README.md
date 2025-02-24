# RAG 101 - AI-Driven Research Paper Evaluation

## 📌 Project Overview
The manual evaluation of research papers for conference submission is **labor-intensive, time-consuming, and demands significant expertise**. This project, **RAG 101**, leverages AI to **streamline conference selection and research paper evaluation** using the **Pathway Framework**. The system integrates **advanced language models, comparative analysis techniques, and streaming data frameworks** to **automate** and **optimize** these tasks.

## 🚀 Features
- **Automated Publishability Assessment:** Determines whether a research paper is **publishable** or **non-publishable**.
- **Conference Recommendation System:** Suggests the best **conference category** for publishable papers.
- **Semantic Search & FAISS Indexing:** Efficient paper retrieval for comparison.
- **Machine Learning Models:** Utilizes **K-Nearest Neighbors (KNN), FAISS, and LangChain** for evaluation.

## 🛠 Tech Stack
- **Programming Language:** Python
- **Libraries & Frameworks:**  
  - `LangChain`: AI-powered research paper analysis  
  - `FAISS`: Efficient similarity search  
  - `Semantic Search`: Enhanced document retrieval  
  - `K-Nearest Neighbors (KNN)`: Classification for research categories  
- **Data Processing:** 150 research papers, with 15 labeled examples for training.

## 📂 Project Structure
RAG-101/ │── data/ # Research paper dataset │── models/ # AI models for classification │── scripts/ # Training & evaluation scripts │── src/ # Core implementation │── notebooks/ # Jupyter notebooks for experimentation │── requirements.txt # Dependencies │── README.md # Project documentation

bash
Copy
Edit

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/yourusername/rag-101.git

pip install -r requirements.txt
3️⃣ Run the Application


# Load Model
model = LangChainFramework(model_name="research-paper-evaluator")

# Evaluate a research paper
paper_text = "This paper introduces a novel method for..."
response = model.evaluate(paper_text)
print(response)  # Output: "Publishable" or "Non-Publishable"
🎯 Future Improvements
Expand dataset for more accurate classification.
Fine-tune models for better generalization.
Real-time API integration for conference platforms.
📜 License
This project is licensed under the MIT License.

🤝 Contributing
Contributions are welcome! Open an issue or submit a pull request.

📬 Contact
For inquiries, reach out at devansh05awasthi@gmail.com or open an issue in the repo.
