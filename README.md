# 🩺 Personal Health Assistant

This is a simple AI-powered web app that acts as a personal health assistant. It takes symptoms as input from the user and provides a possible diagnosis along with recovery advice.

## 💡 Project Summary

- Implemented using **OpenAI GPT-3.5 Turbo model** via the `boltiotai` API
- Built with **Flask** for the backend and **HTML/CSS (Bootstrap)** for the frontend
- The AI model processes the user's symptoms and gives medical advice in natural language

## 🚀 How it Works

### Input:
User enters symptoms like: headache, fever, sore throat

### Processing:
- The symptoms are passed to the GPT-3.5 model via API
- AI analyzes and generates a response with diagnosis and recovery suggestions

### Output:
The result is displayed on the same page with an option to copy the advice.

---

## 🛠️ Tech Stack

- **Language**: Python
- **Framework**: Flask
- **Frontend**: HTML, CSS (Bootstrap)
- **AI Model**: OpenAI GPT-3.5 Turbo (via `boltiotai`)
- **Hosted on**: Replit

---

## 📸 Screenshot

![Screenshot of the Personal Health Assistant ](https://github.com/user-attachments/assets/4c4f3c75-eebe-4971-93a5-89b9e4dd2d2d)


---

## 📁 Folder Structure

main.py # Flask application

templates/ # HTML files

static/ # CSS or assets if any

requirements.txt # Python dependencies

---

## 👩‍💻 Developed By

**Lavanya Panwar**  
Computer Science Student  
Project completed during internship at Bolt IoT  

---

## 🌐 How to Run Locally

1. Clone this repo
2. Install dependencies: pip install -r requirements.txt
3. Set your `OPENAI_API_KEY` as an environment variable
4. Run the app: python main.py
5. Open `http://localhost:8080` in browser

---

## 📝 License

This project is licensed for learning and demo purposes.
