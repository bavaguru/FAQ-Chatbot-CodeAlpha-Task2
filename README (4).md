# 🤖 FAQ Chatbot using NLP
**CodeAlpha Internship – Task 2**

This project is a simple yet efficient FAQ Chatbot built using Natural Language Processing (NLP) techniques. It processes user questions, calculates similarity with predefined questions, and responds with the most appropriate answer.

---

## 👩‍🎓 Internship Info

- 🎓 **Intern:** Bavadharani P  
- 🎓 **Program:** 3rd Year, B.Tech AI & DS  
- 💼 **Internship:** CodeAlpha – AI & ML Domain  
- 📌 **Task 2:** FAQ Chatbot using NLP  

---

## 🚀 Features
- Text preprocessing (lowercasing, stopword removal, punctuation filtering)
- Vectorization using TF-IDF
- Cosine similarity for matching questions
- Handles unrecognized queries with fallback message
- Supports multiple interactions

---

## 🛠️ Technologies Used
- Python
- NLTK
- Scikit-learn
- NumPy

---

## 📁 File Structure

```
📂 Task 2 - FAQ Chatbot
├── task2_faq_chatbot.ipynb   # Main Python notebook
└── README.md                 # Project documentation
```

---

## 🧪 How to Run

1. Open `task2_faq_chatbot.ipynb` in **Google Colab** or **Jupyter Notebook**.
2. Run the first cell to install and download required libraries:

    ```python
    import nltk
    nltk.download('punkt')
    nltk.download('stopwords')
    ```

3. Proceed to run all cells in order.
4. Type your question when prompted in the chatbot console.
5. To exit, type: `bye`, `exit`, or `quit`.

---

## 💬 Sample Questions to Ask
- What is your name?  
- How can I reset my password?  
- What services do you offer?  
- How can I contact support?  

---

## 🏁 Output Example
```
Chatbot is ready! Type 'bye' to exit.
You: How can I reset my password?
Chatbot: You can reset your password by clicking on 'Forgot Password' at the login page.
```

---

## 📌 Note
This chatbot is built on a fixed FAQ dataset and doesn't learn from user input. Ideal for customer support prototypes.

---

## 🏆 Acknowledgement
This project is submitted as part of **CodeAlpha AI & ML Internship** under **Task 2 – FAQ Chatbot**.