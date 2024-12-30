# **Project Repository: Text Summarizer and Image Captioner**

This repository is for the **Text Summarizer** and **Image Captioner** projects, two independent yet complementary projects leveraging natural language processing and computer vision techniques. We use two LLMs, one with GPT-like structure, and one using BLIP.

## 🔍 **Overview**

### **1. Text Summarizer**
The **Text Summarizer** project focuses on generating concise and accurate summaries from long-form text. It can be used to simplify document analysis, news aggregation, and content generation.

**Features:**
- Summarization for articles, research papers, and general text.
- Supports abstractive and extractive summarization techniques.
- Adjustable summary length based on user input.

### **2. Image Captioner**
The **Image Captioner** project automates the generation of natural language descriptions for images, bridging the gap between visual and textual data.

**Features:**
- Generates human-like captions for uploaded images.
- Fine-tuned with pre-trained transformer and vision models.
- Supports custom dataset training.

## **Setup and Usage**

1. Copy the repository URL, and open it through **Google Colab**, to run it as a notebook.
2. Run `WebScraping.ipynb` first to create the **2024** and **2023 - earlier years datasets**.

### **Text Summarizer**
- Run the code in `Text_Summarizer`, ensuring the datasets are present in the notebook.

### **Picture Captioner**
- Run the code in `Picture_Captioner`.
- Use the **2023 earlier years dataset** in Colab.
- Take an image from the **2024 dataset** and place it in the `testImage = Image.open()` line.

