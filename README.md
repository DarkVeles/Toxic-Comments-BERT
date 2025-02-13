# Toxic Comment Classification with BERT

This project fine-tunes BERT for toxic comment classification in Russian.  
The task was to detect toxic user-generated content in an online store's product descriptions.  
A model was trained on a labeled dataset to distinguish between **toxic** and **non-toxic** comments.  

## 🔥 Key Features
- Fine-tuned **RuBERT** for text classification  
- GPU-accelerated training on **RTX 4080**  
- Achieved **F1-score: 0.85** (exceeding the required 0.75)  
- Custom preprocessing pipeline for better performance  
- Optimized training workflow to handle **kernel crashes and library conflicts**  

## 🛠 Tech Stack
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)  
- **Machine Learning:** PyTorch, Hugging Face Transformers  
- **NLP:** RuBERT (DeepPavlov), Tokenizers  
- **GPU Acceleration:** CUDA, NVIDIA RTX 4080  

## 🚀 Challenges & Solutions
During the project, I faced multiple **technical issues**, including:  
✅ Frequent kernel crashes during visualization (solved by modular library imports)  
✅ Library conflicts when using Seaborn & Matplotlib together with PyTorch  
✅ Environment setup challenges for GPU acceleration  

After optimizing the pipeline, I successfully trained and deployed the model.

## 📊 Results
- **F1-score (Test Set):** `0.85`
- **F1-score (Train Set):** `0.80`
- **Training time:** ~50 minutes on a single epoch  
- **Inference time:** ~18 minutes on training, ~5 minutes on test set  

## 📌 Future Improvements
- Increase the number of training epochs for better generalization  
- Experiment with data balancing techniques to improve performance on rare classes  
- Further optimize GPU utilization for faster training  

## 📫 Contact
- Telegram: [@Alvin_S](https://t.me/Alvin_S)  

---

💡 *This project was an exciting challenge, combining NLP, deep learning, and real-world GPU optimization.* 🚀
