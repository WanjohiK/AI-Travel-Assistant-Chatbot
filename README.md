# 🧭 AI Travel Assistant

An interactive **AI-powered travel planning assistant** built using **OpenAI GPT‑4o** and **Gradio**.  
This app helps users plan trips, select destinations, and explore travel options like airlines, cities, and dates — all through a smart conversational interface.

---

## 🚀 Features

- 🌍 **Destination Discovery:** Choose from a list of popular countries and cities.
- ✈️ **Airline Suggestions:** Recommends airlines based on your travel route.
- 🗓️ **Smart Date Planning:** Uses contextual reasoning to propose travel schedules.
- 🤖 **AI Chat Interface:** Powered by GPT‑4o for dynamic, natural conversations.
- 🧱 **Gradio UI:** Easy-to-use web interface for quick interaction.

---

## 🛠️ Installation & Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/ai-travel-assistant.git
   cd ai-travel-assistant
   ```

2. **Create and activate a virtual environment:**

   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Set up your OpenAI API key:**

   Create a `.env` file in the project root and add your key:

   ```bash
   OPENAI_API_KEY=your_api_key_here
   ```

---

## ▶️ Usage

Run the notebook or start the app directly with Gradio:

```bash
python app.py
```
Or open the Jupyter notebook:
```bash
jupyter notebook "AI Travel Assistant.ipynb"
```

Once launched, a **Gradio interface** will open in your browser where you can:
- Select a country and city
- Choose preferred airlines
- Interact with the AI to generate personalized travel ideas

---

## 📦 Technologies Used

- **Python 3.10+**
- **OpenAI GPT‑4o**
- **Gradio**
- **dotenv**
- **JSON / datetime** utilities

---

## 🌱 Future Improvements

- Integration with live flight APIs (Skyscanner, Amadeus)
- Budget-aware itinerary suggestions
- Hotel and event recommendations
- Support for multiple languages

---

## 📄 License

This project is open-source and available under the **MIT License**.

---

**Author:** Kelvin Nyawira  
✨ *Made with GPT‑4o & Gradio*
