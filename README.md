# 📂 Automated File Sorter using Python

A simple yet powerful Python script that automatically organizes files in your **File Explorer** (Windows/Linux/macOS) by moving them into categorized folders based on their file extensions.

## ⚙️ Features

- Sorts files by type (Images, Documents, Videos, Audio, Archives, etc.)
- Automatically creates folders if they don’t exist
- Supports multiple file extensions per category
- Works in any directory (Desktop, Downloads, custom path)
- Clean and beginner-friendly Python code

## 🧰 Categories Supported

- 📷 **Images:** `.jpg`, `.png`, `.jpeg`, `.gif`, `.bmp`
- 📄 **Documents:** `.pdf`, `.docx`, `.txt`, `.xlsx`, `.pptx`
- 🎥 **Videos:** `.mp4`, `.mkv`, `.avi`, `.mov`
- 🎵 **Audio:** `.mp3`, `.wav`, `.aac`
- 🗜️ **Archives:** `.zip`, `.rar`, `.tar`, `.gz`
- 📦 **Executables & Others:** `.exe`, `.msi`, `.apk`, etc.

## 📦 Requirements

- Python 3.6 or higher
- No external libraries required (uses `os`, `shutil`)

## 🚀 How to Use

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/automated-file-sorter.git
   cd automated-file-sorter
2. 	Run the script:
        	python file_sorter.py
3. 	Input the path of the folder you want to organize when prompted.
   
 automated-file-sorter/
├── file_sorter.py
└── README.md

   🧠 How It Works
	•	Scans the target folder for files
	•	Matches file extensions with predefined categories
	•	Moves each file into a corresponding folder
	•	Creates new folders as needed

🖼 Example
Before:
Downloads/
├── report.pdf
├── photo.jpg
├── movie.mp4
After running script:
Downloads/
├── Documents/
│   └── report.pdf
├── Images/
│   └── photo.jpg
├── Videos/
│   └── movie.mp4

🛡️ License

This project is licensed under the MIT License.

🤝 Contributing

Have a suggestion? Found a bug? Open an issue or submit a pull request!

Made with ❤️ in Python
---

Let me know if your script includes extra features (e.g., real-time sorting with watchdog, GUI with Tkinter, or tray notifications), and I can extend the README for that too.

   
	
