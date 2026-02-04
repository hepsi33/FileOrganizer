
📂 Universal Python File Organiser
A high-speed, intelligent file management utility that cleans up any directory with a single click. Unlike static scripts, this tool provides a Universal Folder Selector and uses Multithreading to sort thousands of files across your system in seconds.

📺 Demo in Action
<p align="center">
<video src="YOUR_UPLOADED_VIDEO_LINK_HERE" width="90%" controls></video>
</p>

https://github.com/user-attachments/assets/fb7bd956-3660-4be0-86ae-96679cdd6f69


✨ Key Features
🌍 Universal Target: Works on any folder—Downloads, Desktop, External Drives, or custom project paths.

⚡ Multithreaded Engine: Uses a ThreadPoolExecutor to perform file I/O operations in parallel, making it up to 5x faster than standard scripts.

🛡️ Smart Collision Logic: Never loses data. If report.pdf already exists in the destination, it intelligently renames the new file to report_1.pdf.

🖱️ One-Click GUI: A clean tkinter interface allows you to select folders visually—no path typing required.

🏷️ Auto-Categorization: Uses a comprehensive extension map to sort files into logical groups:

Media: Photos, Videos, Audio

Work: PDFs, Docs, Spreadsheets

Dev: Scripts, JSON, Code

Archives: ZIP, RAR, Tarballs

🚀 How to Use
Clone & Setup:

Bash
git clone https://github.com/yourusername/universal-file-organiser.git
cd universal-file-organiser
Run the Application:

Bash
python main.py
Organise:

A folder picker will appear.

Select the messy folder you want to clean.

Watch the robot sort everything into categorized sub-folders!

⚙️ Configuration
You can customize the folder categories by editing the MAP dictionary in main.py. For example, to add a "Gaming" category:

Python
MAP = {
    "Gaming": [".iso", ".rom", ".sav"],
    # ... other categories
}
🛠️ Technical Details
Language: Python 3.10+

Concurrency: concurrent.futures.ThreadPoolExecutor

File System: pathlib (Modern, cross-platform path handling)

UI: tkinter (Native Windows/Mac/Linux support)
