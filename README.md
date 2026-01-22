📁 Directory Tree Analyzer

A Python CLI tool that analyzes any folder on your computer.
It recursively scans directories, counts files and folders, calculates total size, groups files by extension, and shows the top 5 largest files.

🔹 Features

Recursively scan any folder and subfolders

Count total files and folders

Calculate total size of all files (human-readable: B, KB, MB, GB)

Group files by file extension

Display top 5 largest files

Skips hidden files automatically

Handles permission errors safely

Clear and formatted terminal output

💻 Installation

Make sure you have Python 3.x installed. You can check by running:

python --version


or

python3 --version


Clone the repository:

git clone https://github.com/Kolins854/directory-tree-analyzer.git


Navigate to the project folder:

cd directory-tree-analyzer

🚀 Usage

Run the program:

python directory_analyzer.py


or, on some systems:

python3 directory_analyzer.py


Enter the full path of the directory you want to analyze when prompted:

Enter the directory to analyze: C:\Users\YourName\Documents\TestFolder


View the analysis results in the terminal.

📊 Example Output
Analysis Complete:
Total folders: 10
Total files: 42
Total size: 120.34 MB

Files by extension:
.py: 12 files
.txt: 20 files
.jpg: 5 files
No Extension: 5 files

Top 5 largest files:
/Users/YourName/Documents/TestFolder/video.mp4 (45.23 MB)
/Users/YourName/Documents/TestFolder/archive.zip (30.00 MB)
...

🛠️ How It Works

Uses Python’s os.walk() to traverse directories recursively

Tracks file counts, folder counts, and file sizes

Groups files using a dictionary keyed by extension

Finds the largest files by sorting a list of (size, file_path) tuples

Formats file sizes to human-readable units

⚠️ Notes

Hidden files (starting with .) are skipped by default

Permission errors are caught, so the script won’t crash

Works on Windows, Mac, and Linux

📂 Folder Structure
directory-tree-analyzer/
├── directory_analyzer.py
├── README.md

📌 License

MIT License © 2026 R.C. Njenga
