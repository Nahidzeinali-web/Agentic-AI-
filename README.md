# 🛒 Product Price Finder with LLMs

A simple Streamlit application that leverages large language models (LLMs) via [LangChain](https://www.langchain.com/) and [Groq API](https://console.groq.com/) to extract structured information (product name and tentative price) from free-form product descriptions.

## 🚀 Features

- Choose between multiple cutting-edge LLMs (`deepseek-r1-distill-llama-70b`, `qwen-qwq-32b`, and `llama-3.1-8b-instant`)
- Input raw product details and get:
  - 📦 Product Name  
  - 💵 Tentative Price in USD  
- Uses `Pydantic` for clean structured output
- Simple, fast, and interactive web UI with `Streamlit`

---

## 🧠 Tech Stack

- **LangChain**: Prompt templating and chaining with model
- **Groq**: Fast inference using various LLMs
- **Pydantic**: Data validation for structured output
- **Streamlit**: Interactive web app interface
- **dotenv**: Securely load API keys from `.env` file

---

## 📦 Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/product-price-finder.git
   cd product-price-finder
