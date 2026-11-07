# 🍔 Swiggy Food Menu Chatbot

An AI-powered food menu chatbot built using **Python, Pandas, Google Colab, and the Groq API**.

The chatbot uses a Swiggy restaurant and menu dataset as its knowledge source. It allows users to ask questions in natural language about restaurants, dishes, prices, ratings, food categories, and locations.

## 📌 Project Overview

The Swiggy Food Menu Chatbot makes it easier to explore restaurant and food menu information through a conversational interface.

Instead of manually searching through a large dataset, users can ask questions such as:

- Which restaurants serve biryani?
- What is the price of a particular dish?
- Which restaurants are available in Chennai?
- What is the rating of a restaurant?
- Show me vegetarian food.
- What dishes are available at a particular restaurant?

The chatbot searches the dataset, retrieves relevant information, and uses the Groq AI API to generate a natural-language response.

If the requested information is not available in the dataset, the chatbot provides a fallback response rather than intentionally making up menu details.

## 🎯 Project Objectives

- Build a simple AI-powered chatbot.
- Work with a real-world restaurant and menu dataset.
- Perform data handling and preprocessing using Pandas.
- Search structured data using Python.
- Integrate an external AI API.
- Generate conversational responses using an LLM.
- Explore practical applications of Generative AI.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Data Handling:** Pandas
- **Development Environment:** Google Colab
- **AI API:** Groq API
- **Language Model:** Llama 3.1
- **Dataset Format:** CSV
- **Version Control:** GitHub

## 📊 Dataset

The project uses a Swiggy restaurant and menu dataset containing information such as:

- Restaurant Name
- Dish Name
- City
- State
- Location
- Category
- Price
- Rating
- Rating Count

The dataset is loaded and processed using Pandas to retrieve relevant restaurant and menu information.

## ⚙️ How It Works

The chatbot follows this workflow:

1. **User Input:** The user asks a question in natural language.
2. **Question Processing:** The question is processed to identify the required information.
3. **Dataset Search:** The chatbot searches the Swiggy dataset.
4. **Record Retrieval:** Relevant restaurant or menu records are selected.
5. **Context Preparation:** The retrieved information is prepared as context.
6. **LLM Integration:** The context and user question are sent to the Groq API.
7. **Response Generation:** The language model generates a conversational response.
8. **Output:** The chatbot displays the response to the user.

## 🖥️ Project Screenshots

### Chatbot Interaction

This screenshot shows the chatbot responding to a user's food menu query.

Screenshot%202026-08-14%20144220.png

### Dataset Preview

This screenshot shows the Swiggy dataset loaded for processing.

Screenshot%202026-08-14%20144257.png

## 🚀 How to Run the Project

1. Clone or download this repository.
2. Open `Food_Menu_Chatbot.ipynb` in Google Colab.
3. Make sure the dataset CSV file is available in the expected location.
4. Configure your Groq API key securely, following the notebook's API-key setup.
5. Run the notebook cells in sequence.
6. Interact with the chatbot using natural-language questions.


## 📂 Repository Structure

```text
Food-Menu-Chatbot/
│
├── Food_Menu_Chatbot.ipynb
├── swiggy_all_menus_india.csv
├── Screenshot 2026-08-14 144220.png
├── Screenshot 2026-08-14 144239.png
├── Screenshot 2026-08-14 144257.png
└── README.md
```

## 📚 Key Learnings

Through this project, I gained practical exposure to:

- Working with structured datasets using Pandas.
- Searching and retrieving relevant information from data.
- Integrating an LLM through an external API.
- Generating natural-language responses.
- Building a simple conversational AI application.
- Understanding how Generative AI can be applied to real-world use cases.

## 🔮 Future Improvements

- Improve natural-language query handling.
- Add more advanced filtering and search capabilities.
- Explore Retrieval-Augmented Generation (RAG).
- Develop a user-friendly web interface.
- Explore additional conversational AI features.

## 👩‍💻 Author

**Fatma Sameer Shaikh**

B.E. Computer Science and Engineering (AI & ML)  
St. Joseph's Institute of Technology

GitHub Profile: https://github.com/fatmashaikh2007-tech

---

*Built as a hands-on project during the "Next-Gen AI Engineering: LLMs, RAG & AI Agent" workshop at St. Joseph's Institute of Technology.*
