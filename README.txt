🔐 SecurePass Pro — Intelligent Password Strength Checker (Jupyter Edition)

SecurePass Pro is a modern GUI-based password strength analyzer built entirely in Python using CustomTkinter — right inside a Jupyter Notebook.
It helps users instantly test and improve password strength, provides entropy calculations, detects common passwords, and offers smart suggestions — all in a visually interactive interface.

────────────────────────────────────────────
🌟 Key Features
────────────────────────────────────────────
✅ Real-time Strength Indicator
Instantly updates as you type — showing strength as Weak, Moderate, or Strong.

✅ Entropy / Score Meter
Displays entropy bits that reflect password randomness and complexity.

✅ Common Password Detection
Contains 50+ common and predictable passwords (like 123456, password, hello@123) and warns users if their password is too common.
A “View Common Passwords” button lets users see the full list of weak examples.

✅ Password Generator 🔐
Generates strong, random passwords avoiding common patterns.

✅ Password Visibility Toggle 👁️
Allows you to show or hide your entered password safely.

✅ Dark / Light Theme 🌙☀️
Switch themes dynamically with adaptive colors for perfect visibility.

✅ Offline Mode
Runs entirely offline — no internet or external API required.

────────────────────────────────────────────
🧠 How It Works
────────────────────────────────────────────
• The app uses entropy-based analysis, character variety, and length to score passwords.
• Detects common passwords or variations (e.g. “hello@123”).
• Gives human-friendly suggestions for improvement.
• Includes a random secure password generator.
• GUI automatically updates with every keystroke.

────────────────────────────────────────────
🧩 Project Structure
────────────────────────────────────────────
SecurePassPro/
│
├── securepass.ipynb        # Main Jupyter Notebook (app interface)
├── README.txt              # Project documentation (this file)
├── dark_mode.png           # Optional screenshot
├── light_mode.png          # Optional screenshot
└── requirements.txt        # Optional dependencies file

────────────────────────────────────────────
⚙️ Setup & Installation
────────────────────────────────────────────
Step 1️⃣ — Install Required Packages
In a new Jupyter Notebook cell, run:
!pip install customtkinter

Step 2️⃣ — Open the Notebook
Open securepass.ipynb in Jupyter Notebook or VS Code (with Jupyter support).

Step 3️⃣ — Run the App
Run the cell that contains the SecurePass Pro code.
The GUI window will appear — you can:
• Type or paste a password to check its strength
• Generate random passwords 🔐
• Toggle visibility 👁️
• Switch dark/light themes 🌗
• View common passwords ⚠️

────────────────────────────────────────────
🧩 Example Password Tests
────────────────────────────────────────────
Password      | Strength | Comment
--------------|-----------|----------------------------------
123456        | 🔴 Weak   | Extremely common
Hello@123     | 🔴 Weak   | Common pattern
Pa$$w0rd!     | 🟡 Moderate | Variation of “password”
G7!rM2z#pL9q  | 🟢 Strong | Excellent entropy

────────────────────────────────────────────
🧰 Technologies Used
────────────────────────────────────────────
• Python 3.11.9
• CustomTkinter (modern GUI framework)
• Regex (pattern matching)
• Math (entropy calculation)
• String (password generation)

────────────────────────────────────────────
💡 Future Enhancements
────────────────────────────────────────────
• ✅ Larger common password database (10K+ entries)
• ✅ Fuzzy detection for passwords containing common words
• ⏳ Integration with HaveIBeenPwned API for breach checks
• ⏳ Export strong passwords to a text file
• ⏳ More UI customization and animations

────────────────────────────────────────────
🧑‍💻 Author
────────────────────────────────────────────
Zain Ul Abdin  
💻 Cybersecurity Enthusiast | Ethical Hacker in Training | Python Developer  
📍 Pakistan  
GitHub: https://github.com/ZAINULABDIN19  
LinkedIn: https://linkedin.com/in/zain-ul-abdin-88157b332  

────────────────────────────────────────────
🛡️ License
────────────────────────────────────────────
This project is released under the MIT License — you are free to use, modify, and distribute it.

────────────────────────────────────────────
⚠️ Disclaimer
────────────────────────────────────────────
This project is for learning and cybersecurity awareness purposes only.
It performs all checks locally and never sends your passwords over the internet.
Always use unique, complex passwords for each online account.

⭐ If you find SecurePass Pro helpful, please star the repository!
