# 🧮 Apple-Inspired AI Calculator

## 📝 Overview
The Apple-Inspired AI Calculator is an innovative project that utilizes OpenCV and Google’s Gemini AI to solve mathematical problems of any complexity. The user can draw the math problem on the screen, and the AI model will interpret the visual input to provide a detailed solution. This project is similar to the Apple iPad calculator but leverages advanced AI technology for enhanced functionality and accuracy.

## ✨ Features
- ✍️ **Draw Math Problems** — Use your finger to write any mathematical expression directly on the screen.
- 🖱️ **Navigate Freely** — Move the pointer across the screen by lifting **two fingers**.
- 🗑️ **Reset the Canvas** — Clear your current drawing by lifting your **thumb**.
- 📤 **Submit to AI** — Send the drawing to the AI model by lifting your **little finger**.
- 📊 **Comprehensive Solutions** — Receive accurate, step-by-step explanations powered by Google's Gemini AI.

## 📋 Requirements
Ensure the following dependencies are installed:

- 🐍 Python 3.x  
- 👁️ OpenCV `4.8.0.74`  
- ➗ NumPy `1.23.5`  
- 🖼️ Pillow `9.3.0`  
- 🤖 Google Generative AI `0.1.0`  
- 🛠️ CVZone `1.5.6`  
- 🌐 Django `4.2`  

## 🚀 Installation

1. **Get the Gemini API Key**
   - Sign up and obtain your key from [Google AI Studio](https://aistudio.google.com).

2. **Install Dependencies**
   - Use pip to install all required packages:
     ```bash
     pip install -r requirements.txt
     ```

3. **Set Up the API Key**
   - Add your Gemini API key in the `videoapp/view.py` file where specified.

4. **Run the Application**
   - Start the Django server:
     ```bash
     python manage.py runserver
     ```

5. **Open in Browser**
   - Visit [http://127.0.0.1:8000](http://127.0.0.1:8000) to start using the calculator.

## 🎨 Drawing Rules

Interact with the AI Calculator using these hand gestures:

| Gesture              | Action                                |
|----------------------|----------------------------------------|
| ☝️ One finger up     | Draw math problems                     |
| ✌️ Two fingers up    | Move the pointer on screen             |
| 👍 Thumb up          | Clear the canvas                       |
| 🤏 Little finger up  | Submit the drawing to the AI model     |

Once submitted, the AI processes the drawing and returns a detailed solution.

## 🎥 Demo

🎬 **Watch the AI Calculator in Action**  
Check out our demo video that received 60k+ reactions:  
👉 [Watch on LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:7221422183175139328/)

## 🤝 Contributing

Contributions are welcome!  
Feel free to fork the repository, submit issues, or open pull requests. Your feedback helps improve the project for everyone.

## 📜 License

This project is licensed under the **MIT License**.  
See the [LICENSE](./LICENSE) file for details.

