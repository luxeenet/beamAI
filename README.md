
# 🚀 beamAI

<p align="center">
  <img src="https://img.shields.io/badge/Developer-Emmanuel%20Kaonko-blue?style=for-the-badge" alt="Developer">
  <img src="https://img.shields.io/badge/CEO-Luxeenet-orange?style=for-the-badge" alt="Company">
  <img src="https://img.shields.io/badge/Platform-iOS-lightgrey?style=for-the-badge&logo=apple" alt="Platform">
  <img src="https://img.shields.io/badge/License-Apache%202.0-green?style=for-the-badge" alt="License">
</p>

---

> [!IMPORTANT]  
> **⚠️ Scroll down for an important disclaimer regarding data and official sources.**

## ✨ Features

Explore the powerful capabilities of **beamAI**, designed to transform your learning experience using state-of-the-art AI.

<details>
<summary><b>🤖 AI-Powered Quiz Generation</b></summary>
<br>

- **Multi-Source Input:** Seamlessly process 🖼️ images, 🔗 URLs, and 📝 plain text.
- **YouTube Integration:** Simply paste a video link to generate quizzes directly from transcripts.
- **Diverse Formats:** Supports Multiple Choice, Multi-select, and AI-graded Free Response.
</details>

<details>
<summary><b>💬 Intelligent AI Feedback</b></summary>
<br>

- **Explain Button:** beamAI breaks down why specific options are correct or incorrect.
- **Deep Evaluation:** Free Response questions are analyzed by AI to offer constructive improvement tips.
- **Smart Recommendations:** beamAI tracks performance to suggest specific reading materials and focus concepts.
</details>

<details>
<summary><b>🕰️ Smart Quiz Management</b></summary>
<br>

- **History Tracking:** Access a comprehensive list of all past quizzes.
- **Collaboration:** Share quiz files directly with friends and classmates.
- **Persistence:** Retake or instantly regenerate quizzes to master a topic.
</details>

---

## 🛠️ How to Get Started

### 1. Installation
* **App Store:** Download [beamAI](https://apps.apple.com/us/app/beamAI/id6602897476) for the best mobile experience.
* **Source:** Follow the [Installation Guide](#-installation) below to build from GitHub.

### 2. Configuration
* Complete the onboarding and provide your free [Gemini API Key](https://aistudio.google.com/app/apikey).
* **Troubleshooting:** If the popup "Input your API key!" appears, navigate to **Settings** (top right) → **Gemini** → Input your key.

> [!CAUTION]
> Never share your API key. It is personal to your Google account.

### 3. Generate & Learn
* Attach your study material (images, links, or text).
* Tap the **Plane Icon** ✈️ to generate your quiz.

<details>
<summary><b>💡 Prompting Pro-Tips</b></summary>

- **Keep it Simple:** No need to type "Quiz me on..."; beamAI handles the instruction logic automatically.
- **Model Choice:** Free users have a 32K limit on Gemini 2.5 Pro. Use **2.5 Flash** for significantly larger content processing.
</details>

> [!TIP]
> For higher accuracy, focus each quiz on a **singular topic** (e.g., "Photosynthesis") rather than mixing unrelated subjects.

---

## ⚙️ How It Works

1.  **Input:** User provides text, images, or URLs.
2.  **Processing:** **beamAI** structures a prompt for the Gemini 2.5 models.
3.  **Parsing:** The AI returns a structured JSON object.
4.  **Rendering:** **beamAI** parses the JSON to dynamically build the quiz user interface.

---

## 🛡️ Disclaimers & Safety

> [!WARNING]
> While **beamAI** itself does not collect user data, Google may collect data based on their terms. Review the [Privacy Policy](https://github.com/Luxeenet/beamAI/blob/master/Privacy.md) and Google's AI policies.

> [!CAUTION]
> Using a free API key means your prompts may be used by Google to train their models. Use a paid tier or be mindful of sensitive information.

---

## 📥 Installation

Build the latest version of **beamAI** directly from the source:

```bash
# Clone the official Luxeenet repository
git clone [https://github.com/Luxeenet/beamAI](https://github.com/Luxeenet/beamAI)

# Enter the project folder
cd beamAI

# Open in Xcode
open beamAI.xcodeproj