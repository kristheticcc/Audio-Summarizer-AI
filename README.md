# AudioSummarizerAI 📝

**AudioSummarizerAI** is an AI-powered tool that converts meeting audio into structured minutes. It transcribes speech using advanced LLMs and audio models, summarizes discussions, highlights key points, and generates actionable items — all in a **streamlined Colab workflow**.  

---

## 🚀 Features

- **Automatic Audio Transcription**: Uses HuggingFace and Open Source model for accurate speech-to-text conversion.  
- **Intelligent Summarization**: Generates meeting minutes including attendees, discussion points, takeaways, and action items.  
- **Streaming & GPU-Accelerated**: Designed to run on Google Colab with GPU support for faster processing.  
- **Secure API Management**: API keys are accessed through Colab secrets — no sensitive information is stored in the notebook.  

---

## 💻 How It Works

1. Audio file (e.g., `.mp3`) is loaded from Google Drive.  
2. Speech is transcribed into text using open-source and Frontier GPT models.  
3. Transcription is summarized into **markdown-formatted meeting minutes**, including:
   - Attendees, date, location  
   - Key discussion points  
   - Takeaways and action items with owners  
4. Outputs are displayed directly in the notebook for easy viewing.  

> **Note:** Since this notebook is hosted on Colab, viewers can only see the code and outputs. To run it themselves, they would need to copy the notebook to their own Colab account and provide API keys. Also, they need to make sure to set the correct path to their audio file.

---

## 🎯 Example Use Case

- City council meetings  
- Team stand-ups or project reviews  
- Board meetings or presentations  

**Input:** Audio recording of the meeting  
**Output:** Structured minutes in markdown format  

---


## ⭐ Acknowledgements

- HuggingFace Transformers, bitsandbytes, and accelerate for model pipelines  
- OpenAI / Frontier GPT models for transcription and summarization  
- Inspired by real-world AI applications in meeting automation

## 👨‍💻Author: Krish Makwana
