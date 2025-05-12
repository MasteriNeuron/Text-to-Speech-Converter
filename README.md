📢 Text to Speech Converter 🎙️
Welcome to the Text to Speech Converter project! This web application transforms your text into natural-sounding speech with various English accents. Built with Flask, HTML, Tailwind CSS, and JavaScript, it offers a sleek and responsive user interface. 🌐✨
🚀 Features

Multiple Accents: Choose from a variety of English accents to customize your speech output. 🗣️
Fast Conversion: Convert text to speech in seconds with a seamless experience. ⚡
Responsive Design: Access the app on any device, from desktops to mobiles. 📱💻
User-Friendly Interface: Modern UI with intuitive controls and audio playback. 🎨
Powered by iNeuron.ai: Leverages advanced text-to-speech technology. 🧠

🛠️ Technologies Used

Backend: Flask (Python) 🐍
Frontend: HTML, Tailwind CSS, JavaScript 🌐
Libraries: jQuery, Font Awesome (for icons) 📚
Deployment: Runs locally with Flask server 🌍

📋 Prerequisites
Before you start, ensure you have the following installed:

Python 3.8+ 🐍
pip (Python package manager) 📦
Git (for cloning the repository) 🗂️

⚙️ Installation
Follow these steps to set up the project locally:

Clone the Repository 📥
git clone https://github.com/your-username/text-to-speech-converter.git
cd text-to-speech-converter


Create a Virtual Environment 🧪
conda create -p env python==3.11 -y

Actuvate the Virtual Environment 🧪
conda activate env/


Install Dependencies 📦
pip install -r requirements.txt


Set Up the Flask Application 🚀Ensure the app.py file and the templates folder (containing index.html) are in the project directory.

Run the Application 🌟
python app.py

The app will be available at http://127.0.0.1:5000.


🎮 Usage

Open your browser and navigate to http://127.0.0.1:5000. 🌐
Select an English accent from the dropdown menu. 🗣️
Enter the text you want to convert in the textarea. ✍️
Click the Convert to Speech button. ▶️
Listen to the generated audio in the results section. 🎧

📂 Project Structure
text-to-speech-converter/
├── templates/
│   └── index.html       # Frontend template with HTML, Tailwind CSS, JS
├── app.py
|-- text_to_speech       # Flask backend for handling requests
├── requirements.txt     # Python dependencies
├── README.md            # Project documentation
└── text_to_speech/      # Custom modules for TTS functionality

🐞 Troubleshooting

Flask Server Not Starting: Ensure all dependencies are installed and the virtual environment is activated. 🛠️
Audio Not Playing: Check if the browser supports WAV audio and verify the backend response. 🔊
CORS Issues: The app uses Flask-CORS to handle cross-origin requests; ensure the backend URL is correct. 🌐

🌟 Contributing
We welcome contributions! To contribute:

Fork the repository. 🍴
Create a new branch (git checkout -b feature/your-feature). 🌿
Commit your changes (git commit -m "Add your feature"). 📝
Push to the branch (git push origin feature/your-feature). 🚀
Open a Pull Request. 🙌

📧 Contact
For support or inquiries, reach out to:

Email: support@pwskills.com 📧
Phone: +1-800-123-4567 📞
Website: pwskills.com 🌐

📜 License
This project is licensed under the MIT License. See the LICENSE file for details. 📄

Built with ❤️ by the PWSkills team. Happy converting! 🎉
