# 🌿 GreenQuest — AI-Powered Nature Companion

**Less scrolling. More exploring.**

GreenQuest is an AI-powered outdoor activity web application built using HTML, CSS, and JavaScript. It encourages people to spend less time on screens and more time exploring the natural world through personalized outdoor quests.

The project uses an open-weight AI model with Hugging Face Transformers.js to generate nature activities based on the user's mood, available time, and interests.

## ✨ Features

* 🤖 **AI-Powered Quest Generator** — Generates personalized nature activities using an open-weight AI model.
* 🌳 **Nature Exploration** — Discover activities related to plants, trees, birds, wildlife, walking, and gardening.
* 🎯 **Personalized Activities** — Choose your mood, interests, and available time.
* 🏆 **Points System** — Earn points by completing quests.
* 💾 **Local Storage** — Saves your points in your browser.
* 📱 **Responsive Design** — Works on desktop, tablet, and mobile screens.
* 🌱 **Fallback Activities** — Displays a built-in activity when AI generation fails.
* 🔓 **Open-Weight AI** — Runs inference in the browser without requiring a paid AI API key.

## 🛠️ Technologies Used

| Technology                   | Purpose                                            |
| ---------------------------- | -------------------------------------------------- |
| HTML5                        | Website structure                                  |
| CSS3                         | Styling, layout, animations, and responsive design |
| JavaScript                   | Interactivity and application logic                |
| Hugging Face Transformers.js | Running AI models in the browser                   |
| Qwen2.5-0.5B-Instruct        | Open-weight language model                         |
| Browser Local Storage        | Saving user points                                 |

## 📂 Project Structure

```text
GreenQuest/
│
├── index.html     # Main website structure
├── style.css      # Styling and responsive layout
├── script.js      # AI integration and application logic
└── README.md      # Project documentation
```

## 🚀 Getting Started

### Prerequisites

* A modern web browser, such as Chrome or Firefox.
* Visual Studio Code (recommended).
* The Live Server extension for VS Code.
* An internet connection for the initial library and AI model downloads.

### Installation

**1. Clone the repository**

Replace `YOUR-USERNAME` with your GitHub username.

```bash
git clone https://github.com/YOUR-USERNAME/GreenQuest.git
```

**2. Open the project folder**

```bash
cd GreenQuest
```

**3. Open the project in Visual Studio Code**

```bash
code .
```

**4. Start the website**

Install the Live Server extension, right-click `index.html`, and select **Open with Live Server**.

**5. Generate your first quest**

* Select your mood.
* Choose your available time.
* Select an outdoor interest.
* Click **Generate My Quest**.
* Complete the activity to earn points.

The first AI model download may take some time depending on your internet speed and device.

## 🤖 How the AI Works

GreenQuest uses Hugging Face Transformers.js to load a text-generation model in the browser.

1. The user selects a mood, duration, and interest.
2. JavaScript builds a prompt from those preferences.
3. The model generates a nature quest.
4. The generated response is parsed and displayed on the website.
5. If AI generation fails, a built-in fallback activity is displayed.

The model is configured to run inference locally in the browser. However, the initial model download requires internet access, and fully offline operation requires the necessary model and library files to be cached or hosted locally.

## 🌍 Why Open-Source AI?

Open innovation makes GreenQuest more flexible and accessible.

* **Privacy:** User preferences can stay in the browser rather than being sent to a commercial AI API.
* **Cost efficiency:** No paid per-request AI API is required.
* **Flexibility:** Developers can experiment with compatible models and customize prompts.
* **Local inference:** AI generation can run on the user's device after the required files are downloaded.
* **Accessibility:** The project makes AI-powered outdoor activities available through a web browser.

*Note: Qwen2.5-0.5B-Instruct is an open-weight model. Review its license and the terms of any model distribution you use before deployment.*

## 🔮 Future Improvements

* 🌿 Plant identification using an image-capable model.
* 🐦 Bird identification from photographs or audio.
* 🗺️ Outdoor location discovery and nature trails.
* 📅 Daily and weekly nature challenges.
* 🏅 Achievement badges and leaderboards.
* 📶 Fully offline quest generation.
* 🌤️ Weather-aware activity recommendations.
* 📊 A dashboard to track outdoor activity progress.

## 🎯 Project Theme

**Touch Grass — Build something with open-source AI.**

GreenQuest aims to make technology a bridge to the real world, helping people discover nature, learn through exploration, and build healthier outdoor habits.

## 👨‍💻 Author

**Aarav Yadav**

B.Tech — Computer Science and Engineering (AI/ML)

## 📄 License

This project is intended for educational and personal development purposes. You may add an MIT License if you want to distribute your own project under those terms. Check third-party model and library licenses separately.

---

**🌿 Go outside. Explore more. Make every day a little greener.**

