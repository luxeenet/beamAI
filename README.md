

⚠️ Scroll down for an important disclaimer
Features
<details>

<summary>🤖 AI powered quiz generation based on user notes</summary>

🖼️, 🔗, 📝: Input images, URLs, and plain text

YouTube integration: Input URLs to videos with a transcript

Supported question formats include multiple choice, multi-select, and free-response (AI-powered grading)

</details> <details>

<summary>💬 Evaluate your understanding with AI-feedback</summary>

beamAI offers an Explain button, allowing users to understand why each option in a question is correct/incorrect

Free Response evaluates whether a user's response is correct, and it offers ways to improve their response, regardless of whether they got it correct or not.

Performance feedback at the end of a quiz means that beamAI can recommend reading material and concepts to work on based on the user's performance.

</details>

<details>

<summary>🕰️ beamAI includes quiz history</summary>

View list of past quizzes

Share the quiz file with friends

Retake the quiz (or even regenerate it!)

View past results

</details>

How to generate a quiz using beamAI
Install beamAI from the App Store.

You can also follow these installation instructions to install it from GitHub.

Complete the Onboarding process and input your free Gemini API key

If you aren't able to get the key from your iPhone, try opening the link on your laptop.

When you attempt to generate a quiz, you'll see a popup saying "Input your API key!" To fix this, open Settings (top right corner), scroll down, and click on Gemini under the model configurations. You'll see a textfield with a place to input your API key.

[!CAUTION] Be sure not to share your API key with anybody else!

Add attachments using the buttons marked for images and URLs, and add text-based attachments to the textfield.

Click the plane icon to start generating the quiz! Enjoy!

<details>

<summary>Prompting Instructions:</summary>

No need to use phrases such as "quiz me on [...]." beamAI has already instructed Gemini to generate you a quiz. Just simply add attachments relating to whatever you'd like to be quizzed on.

Free users have a 32K input limit on the Gemini 2.5 Pro model, so this means you should not exceed the limit by adding too much content. Switch to 2.5 Flash to have a significantly larger input limit.

</details>

[!TIP] Try to only generate quizzes on a singular topic (eg. Cats) rather than multiple topics (eg. Cats, Math, Java etc.)

How It Works
As mentioned previously, beamAI prompts Gemini with your input, and it returns a JSON with the quiz info, which beamAI parses and puts in a JSON. beamAI then parses the JSON, rendering the quiz UI.

Disclaimers
[!WARNING] While beamAI does not collect any data from its users, there's nothing stopping Google from collecting YOUR data, so be sure to read their privacy policies to be aware of what's going on. Read the Privacy Policy for more information about this.

[!CAUTION] When inputting your personal API key, be aware of the fact that on a free account, your prompts are linked to your identity and are used to train their models.

Installation
To get started with beamAI, follow these steps:

Bash

# Clone the repository
git clone https://github.com/Luxeenet/beamAI

# Navigate to the project directory
cd beamAI

# Open the project in Xcode
open beamAI.xcodeproj
Usage
To use beamAI, follow these steps:

Open the project in Xcode.

Select your target device or simulator.

Click the "Run" button or press Cmd + R to build and run the app.

FAQ
Why do I need to input an API key?

Unfortunately, as an indie developer, I can't afford to provide free AI access for everyone. However, Google, a very generous company, offers powerful AI tools for developers at no cost. All you need to do is input the key. If you need help adding the key, feel free to contact me or submit an issue!

Contributing
beamAI welcomes contributions from the community. Please read the contributing guidelines for more information.

License
This project is licensed under the Apache Version 2 License - see the LICENSE file for details.

Contact
For any inquiries, please contact the developer via the official Luxeenet channels.

[!WARNING] Emmanuel Kaonko, CEO of Luxeenet, is the sole developer of beamAI, and this is the official repository listed on the App Store. beamAI is not affiliated with any fraudulent users or organizations on GitHub falsely claiming involvement in this project.

Copyright © 2024-2026 Emmanuel Kaonko. All rights reserved.