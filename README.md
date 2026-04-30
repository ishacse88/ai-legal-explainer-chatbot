# ⚖️ AI Legal Terms Explainer Chatbot

An AI-powered chatbot that simplifies complex legal language into easy-to-understand explanations.  
This project helps users understand legal documents without requiring a legal background.

---

## Features

- Accepts legal text input or PDF upload  
-  Extracts text from PDFs using PyPDF2  
-  Allows selection of explanation level (Beginner / Intermediate / Expert)  
-  Supports tone customization (Formal / Casual / Simple)  
-  Uses AI (Llama 3.1 via Groq API) for text simplification  
-  Fast and interactive UI using ipywidgets  
-  Deployable as a web app using Voilà  

---

##  Tech Stack

- **Language:** Python  
- **Libraries:** PyPDF2, ipywidgets  
- **AI Model:** Llama 3.1  
- **API:** Groq API  
- **Environment:** Jupyter Notebook  
- **Deployment:** Voilà  

---

##  How It Works

1. User enters legal text or uploads a PDF  
2. System extracts text (if PDF)  
3. User selects tone and explanation level  
4. Dynamic prompt is generated  
5. Prompt is sent to Groq API  
6. AI model simplifies the legal content  
7. Final explanation is displayed to the user  

---



