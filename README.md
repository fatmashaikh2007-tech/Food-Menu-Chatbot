# 🍔 Swiggy Food Menu Chatbot

An AI-powered food menu chatbot built using Python, Pandas, Google Colab, and the Groq API.

The chatbot uses a Swiggy restaurant/menu dataset as its knowledge source and allows users to ask questions about restaurants, dishes, prices, ratings, food categories, and locations.

---

## 📌 Project Overview

The Swiggy Food Menu Chatbot is designed to make it easier for users to search and understand restaurant and food menu information through a conversational interface.

Instead of manually searching through a large dataset, users can ask questions in natural language.

For example:

- Which restaurants serve biryani?
- What is the price of a particular dish?
- Which restaurants are available in Chennai?
- What is the rating of a restaurant?
- Show me vegetarian food.
- What dishes are available at a particular restaurant?

The chatbot searches the dataset and provides an answer using the Groq AI API.

If the requested information is not available in the dataset, the chatbot responds:

> Content not found in the dataset.

---

## 🎯 Objectives

- Build a simple AI-powered chatbot.
- Use a real-world restaurant dataset.
- Learn data cleaning and preprocessing.
- Search structured data using Python.
- Integrate an external AI API.
- Generate natural-language responses.
- Prevent the chatbot from inventing information.
- Gain practical experience in Generative AI.

---

## 🛠️ Technologies Used

- Python
- Pandas
- Google Colab
- Groq API
- Llama 3.1
- CSV Dataset
- GitHub

---

## 📊 Dataset

The project uses a Swiggy restaurant and menu dataset.

The dataset contains information such as:

- Restaurant Name
- Dish Name
- City
- State
- Location
- Category
- Price
- Rating
- Rating Count

The dataset is loaded into Python using Pandas.

---

## ⚙️ How It Works

The chatbot follows these steps:

```text
User Question
      ↓
Question Processing
      ↓
Search Swiggy Dataset
      ↓
Find Relevant Records
      ↓
Create Dataset Context
      ↓
Send Context + Question to Groq
      ↓
Generate Answer
      ↓
Display Response
