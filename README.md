# BERT_FineTuning_IMDB_NLP_Task4.ipynb


## 📌 Objective
The objective of this project is to fine-tune a pre-trained BERT model for text classification using the IMDB Movie Reviews dataset.

## 📊 Dataset
- IMDB Movie Reviews Dataset
- Binary Sentiment Classification (Positive / Negative)

## ⚙️ Tools & Technologies
- Python
- Hugging Face Transformers
- PyTorch
- Google Colab

## 🔄 Pipeline
Raw Data → Preprocessing → Tokenization → Model Training → Evaluation → Comparison

## 🧹 Data Preprocessing
- Converted text to lowercase
- Removed extra spaces
- Cleaned raw text data

## 🔤 Tokenization
- Used `bert-base-uncased` tokenizer
- Applied padding and truncation

## 🤖 Model
- Pre-trained BERT model
- Used `AutoModelForSequenceClassification`

## 🚀 Training
- Optimizer: AdamW
- Learning Rate: 2e-5
- Epochs: 1
- Reduced dataset for faster training

## 📈 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## 📊 Results
- Accuracy: ~87%
- Model performed well on sentiment classification

## 🧪 Experiments
- Freezing BERT layers reduced performance
- Fine-tuning improved accuracy

## ⚠️ Note
Due to computational limitations, a subset of the dataset was used for training.

## 📌 Conclusion
BERT demonstrated strong performance in understanding contextual text and performing sentiment classification effectively.

---

## 👩‍💻 Author
Kavitha Shrawan
