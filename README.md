# Health AI – Intelligent Healthcare Assistant  

## 📌 Project Overview  
Health AI is an intelligent healthcare assistant that leverages **IBM's Granite generative AI models** to provide **smart, easy-to-understand medical support**. It helps patients and learners with **disease prediction, treatment guidance, and patient-friendly chat**.  

The goal is to bridge the gap between **raw medical data** and **accessible, personalized healthcare assistance** — making health information more reliable and understandable.  

---

## 👨‍💻 Team Members  
1. name_1
2. "
3. "
4. "

---

## 🚀 Features  
### 🔹 Patient Chat  
- **Key Point:** AI-powered medical chat.  
- **Functionality:** Patients can ask health-related questions and get reliable, simplified responses.  

### 🔹 Disease Prediction  
- **Key Point:** Early health assessment.  
- **Functionality:** Predicts possible conditions based on user inputs and symptoms.  

### 🔹 Treatment Plan Guidance  
- **Key Point:** Suggests possible treatments.  
- **Functionality:** Generates treatment suggestions and lifestyle advice (non-diagnostic).  

### 🔹 User-Friendly Gradio Interface  
- **Key Point:** Accessible web interface.  
- **Functionality:** Clean Gradio interface with tabs for **Chat, Prediction, and Plans**.  

---

## 🏗️ Architecture  
1. **Frontend (Gradio):**  
   - Simple web interface for chat and predictions.  

2. **Backend (Google Colab):**  
   - Python handles medical queries, integrates Granite model, and displays results.  

3. **AI Model (IBM Granite via Hugging Face):**  
   - Uses `ibm-granite/granite-3.2-2b-instruct` for healthcare Q&A and predictions.  

4. **Deployment (Public Gradio Link):**  
   - Hosted via Google Colab with a temporary live link.  

---

## ⚙️ Setup Instructions  

### Prerequisites  
- Google account (for Colab access)  
- Internet connection  
- Hugging Face account  
- Basic knowledge of Python & Gradio  

### Installation  
1. Open **Google Colab** and create a new notebook.  
2. Install dependencies:  
   ```bash
   !pip install transformers torch gradio -q
   ```
   ### Installation
1. Open **Google Colab** and create a new notebook.  
2. Install dependencies:
   
```bash
  !pip install transformers torch gradio -q
```

```bash
  HealthAI/
│── health_ai.ipynb      # Main Colab notebook
│── requirements.txt     # (Optional) dependencies
```

```bash
gradio
transformers
torch
 ```
## ▶️ Running the Application

1. Open **`health_ai.ipynb`** in **Google Colab**.  
2. Run the **first cell** (installs required libraries).  
3. Run the **subsequent cells** (loads model + builds interface).  
4. The **final cell** generates a public Gradio link (e.g., `https://12345.gradio.live`).  
5. Open the link → Ask a health query → Choose **Chat**, **Prediction**, or **Treatment Plan**.  

---

## 📡 API Documentation

Health AI interacts with the **Hugging Face API**.

### Input Examples:
- `"What are the symptoms of diabetes?"`  
- `"Suggest a treatment plan for mild fever."`  
- `"Predict possible disease from cough, cold, and headache."`  

### Output:
- AI-generated **health explanation**, **prediction**, or **treatment guidance**.  

---

## 🔐 Authentication

- **Current Version**: No authentication required (public access).  
- **Future Plans**:  
  - Hugging Face API tokens for secure access.  
  - User accounts for health history & progress tracking.  

---

## 🧪 Testing

- **Unit Testing**: Verified responses for common symptoms.  
- **UI Testing**: Checked usability of Gradio interface.  
- **Model Testing**: Adjusted prompts for more accurate outputs.  

---

## ⚠️ Known Issues

- Predictions are **not diagnostic** (informational purposes only).  
- Responses may vary in **accuracy**.  
- Public Colab links **expire after inactivity**.  
- Performance may lag without a **GPU**.  

---

## 🔮 Future Enhancements

- Add **medical datasets** for fine-tuning.  
- **Multi-language** support for diverse users.  
- Integrate **voice-based input & output**.  
- Provide **PDF health reports**.  
- Deploy on **Hugging Face Spaces** for 24/7 access.  

---
