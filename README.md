# 📧 Cold Mail Generator

A cold email generator built using **groq**, **langchain**, and **streamlit**. It allows users to input the URL of a company's careers page. The tool then extracts job listings from that page and generates personalized cold emails. These emails include relevant portfolio links sourced from a vector database, tailored to the specific job descriptions.

---

## Example Scenario

Imagine a company (**Company A**) needs a **Principal Software Engineer** and is investing heavily in their hiring, onboarding, and training processes. Another organization (**Company B**) provides dedicated software development engineers. A business development executive from Company B reaches out to Company A via a cold email.

---

## Architecture Diagram

![image](https://github.com/user-attachments/assets/fa0d1c6c-e17e-47ca-bfc7-63c020f58fbe)

---

## Setup

1. **Obtain an API Key**  
   Get an API key from [groq console](https://console.groq.com/keys).  
   In `app/.env`, update the value of `GROQ_API_KEY` with your newly created key.

2. **Install Dependencies**  
   ```bash
   pip install -r requirements.txt
