# 🌍 Earth Detective

> **The real world becomes the dataset. AI becomes the game master. You become the investigator.**

Earth Detective is an interactive, AI-powered outdoor investigation game designed to encourage people to step away from their screens and explore the real world.

Instead of completing everything digitally, players receive missions, go outside, observe their surroundings, collect clues, and submit their observations to solve an environmental mystery.

---

## 🚀 Features

* 🕵️ **Interactive Investigation Missions**
* 🌿 Multiple themes:

  * Nature Detective
  * Water Mystery
  * Urban Detective
  * Sustainability Detective
* ⏱️ Adjustable investigation timer
* 🎯 Difficulty-based scoring
* 💡 AI-powered hints
* 🤖 Optional local AI integration using **Ollama**
* 📊 Investigation score and final report
* 💾 Progress saved using `localStorage`
* 🎨 Animated, responsive UI
* 📱 Works on desktop and mobile browsers
* ⚡ Offline-first fallback missions

---

## 🧠 How It Works

```text
Choose a Mission
       ↓
Receive an AI-generated / built-in mystery
       ↓
Go outside and investigate
       ↓
Observe real-world clues
       ↓
Submit your observations
       ↓
Earn points
       ↓
Solve the case
       ↓
Generate your investigation report
```

The key idea is simple:

> **Don't use AI to replace the real-world experience. Use AI to make the real-world experience more interesting.**

---

## 🤖 AI Integration

Earth Detective can optionally connect to a locally running open-weight AI model through **Ollama**.

```text
Earth Detective
      │
      │ JavaScript fetch()
      ▼
   Ollama API
      │
      ▼
Open-weight AI Model
```

The AI can help with:

* Generating investigation missions
* Providing hints
* Evaluating observations
* Creating investigation reports

The application also includes built-in missions, so the core game can work without AI.

---

## 🛠️ Technologies Used

* **HTML5**
* **CSS3**
* **Vanilla JavaScript**
* **LocalStorage API**
* **Fetch API**
* **Ollama** — optional local AI integration

No React, Vue, Angular, or other frontend frameworks are required.

---

## 📁 Project Structure

```text
Earth-Detective/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

---

## ▶️ Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/earth-detective.git
```

### 2. Open the project

```bash
cd earth-detective
```

### 3. Run the website

You can open `index.html` directly in your browser.

For a better local development experience, you can also use a local development server such as VS Code Live Server.

---

## 🤖 Optional: Run AI Locally

If you want to use the local AI features:

1. Install Ollama.
2. Download an available open-weight model.
3. Start Ollama.
4. Enter the Ollama API URL and model name in Earth Detective.

The application will fall back to built-in missions if the AI service is unavailable.

---

## 🌱 Why Earth Detective?

Most digital experiences encourage people to stay in front of a screen.

Earth Detective does the opposite.

The application gives the player a reason to:

* 🌳 Explore nature
* 💧 Observe water usage
* 🏙️ Study their surroundings
* ♻️ Identify sustainability problems
* 👀 Pay attention to details they normally ignore

The phone becomes a **tool for exploration instead of the destination**.

---

## 🎯 Project Goal

The goal of Earth Detective is to combine:

**AI + Gamification + Real-World Exploration**

into one experience that encourages people to interact with their physical environment.

---

## 🔮 Future Improvements

* 📷 AI-powered image investigation
* 🗺️ Location-based missions
* 🌦️ Weather-aware missions
* 🏆 Leaderboards
* 👥 Multiplayer investigations
* 🐦 Bird and plant identification
* 📍 Location-based environmental challenges
* 🧠 More advanced local AI models
* 📱 Progressive Web App (PWA) support

---

## 🔐 Privacy

Earth Detective is designed with a local-first approach.

When using local AI through Ollama, AI requests can remain on the user's own computer rather than being sent to a remote AI service.

---

## 📄 License

This project is open source and available for learning, experimentation, and further development.

---

## 👨‍💻 Author

**Vedant Shukla**

Built as an exploration of how AI can encourage people to spend more time interacting with the real world.

---

### ⭐ If you like the idea

Give the repository a ⭐ and try solving an Earth Detective mission yourself!

> **Touch less screen. Observe more world. 🌍**
