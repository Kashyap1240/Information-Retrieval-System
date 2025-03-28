# Information Retrieval from Multiple PDFs 💁💬 with PaLM2

An intelligent system to retrieve information from multiple PDF documents using advanced LLM capabilities with PaLM2, LangChain, FAISS, and Streamlit.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech-Stack](#tech-stack)
- [Model Architecture](#model-architecture)
- [Demo Screenshots](#demo-screenshots)
- [Installation & Setup](#installation--setup)
- [Usage](#usage)
- [License](#license)

---

## Overview

This project is a multi-PDF information retrieval system that leverages **PaLM2** for advanced language understanding and **LangChain** to orchestrate complex language tasks. The system uses **FAISS** for efficient similarity search, enabling rapid retrieval of the most relevant information from a collection of PDFs. Built with **Streamlit**, it provides a user-friendly interface to interact with the model.

---

## Features

- **Multi-PDF Information Retrieval:** Seamlessly extract and search content across multiple PDF documents.
- **Advanced Query Processing:** Uses PaLM2 to understand and respond accurately to user queries.
- **Efficient Indexing:** Powered by FAISS for lightning-fast similarity searches.
- **Interactive User Interface:** Intuitive UI built with Streamlit for easy query submissions and responses.
- **Scalable & Modular:** Easily extendable architecture for future enhancements.

---

## Tech-Stack

- **Python**: The primary programming language.
- **LangChain**: For chaining language model functionalities.
- **Streamlit**: For building the web-based user interface.
- **PaLM2**: Advanced language model for processing natural language queries.
- **FAISS**: For efficient similarity search and indexing.

---

## Model Architecture

The diagram below illustrates the complete model workflow from input to output:

![Model Architecture](Model%20Architecture/Model%20Architecture.jpeg)

> **Note:** The above diagram is exported from draw.io. You can click [here](https://drive.google.com/file/d/1-76icfT-bY_BHirevmO_Ld_pbeu6xvcl/view?usp=sharing) to view the editable version if you have draw.io installed.

---

## Demo Screenshots

### Query Interface (Before Processing)
This screenshot shows the interface as you enter your query:

![Query Before Processing](Query%20Interface/Image%201.jpeg)

### Query Interface (After Processing)
This screenshot displays the model's response after processing your query:

![Query After Processing](Query%20Interface/Image%202.jpeg)

---

## Installation & Setup

### Steps to Set Up the Project

1. **Clone the Repository**

   ```sh
   git clone https://github.com/Kashyap1240/Information-Retrieval-System.git
   ```

2. **Create a Conda Environment**

   ```sh
   conda create -n llmapp python=3.8 -y
   conda activate llmapp
   ```

3. **Install the Requirements**

   ```sh
   pip install -r requirements.txt
   ```

4. **Set Up Environment Variables**

   Create a `.env` file in the root directory and add your Google API key as follows:

   ```
   GOOGLE_API_KEY= "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
   ```

5. **Run the Application**

   ```sh
   streamlit run app.py
   ```

6. **Access the Application**

   Open up: [http://localhost](http://localhost)

---

## Usage

1. **Enter your query** in the provided input box.
2. **Submit the query** and wait for the model to process and retrieve relevant information from the PDFs.
3. **View the response** displayed on the interface.

---

## License

This project is licensed under the MIT License.

---

Happy Coding! 🎉
```` ▋