# rentwiseAI
# 🚗 Car Rental Sentiment Analysis with Generative AI

A beginner-friendly AI project that performs **sentiment analysis** on customer reviews for a car rental service and generates AI-powered replies using a language model (GPT-2).

> 🔰 Built using Google Colab, Hugging Face Transformers, and Gradio.

---

## ✨ Features

- ✅ Detect whether a customer review is Positive or Negative.
- 🧠 Generate a smart AI response to each review using GPT-2.
- 📊 Support for analyzing **multiple reviews** from a CSV file.
- 🎨 Option to build an interactive web interface using **Gradio**.
- 📁 Save results as downloadable CSV.
- 📈 Visualize sentiment distribution using bar charts.

---

## 📁 Project Structure
car_rental_sentiment_project/
├── sentiment_analysis.py     # Sentiment detection code
├── text_generation.py        # AI-generated response logic
├── batch_analyzer.py         # Process multiple reviews from CSV
├── gradio_ui.py              # Web interface with Gradio
├── visualization.py          # Sentiment graph visualization
├── data/
│ └── reviews.csv             # Sample customer reviews
└── README.md                 # Project instructions

## 🚀 How to Run the Project (Google Colab)

1. Open [Google Colab]
2. Upload or create a new notebook and paste the code.
3. Install required libraries:

```python
!pip install transformers datasets torch gradio pandas matplotlib


