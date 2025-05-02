
📂 Downloads Folder Auto-Organizer

This Python script automatically monitors your `Downloads` folder and moves files into organized categories like Music, Videos, Images, Documents, and SFX (Sound Effects).

---

🚀 Features

- 🧠 Smart Sorting: Categorizes files based on their extensions  
- 📁 Folder Creation: Automatically creates destination folders if they don't exist  
- 🔁 Real-time Monitoring: Uses the `watchdog` library to monitor the folder live  
- 🛡️ Safe File Moving: Prevents file overwrites with a uniqueness check  
- 🧹 Lightweight & Efficient: Runs in the background with minimal resource usage

---

🛠️ Technologies Used

- Python 3
- `os`, `shutil`, and `time` for file handling
- `watchdog` for real-time folder observation
- `logging` for activity tracking

---
 📦 Supported File Types

- Images: `.jpg`, `.png`, `.svg`, `.bmp`, etc.  
- Videos: `.mp4`, `.avi`, `.mov`, etc.  
- Audio: `.mp3`, `.wav`, `.flac`, etc.  
- Documents: `.pdf`, `.docx`, `.xlsx`, etc.  
- SFX: Audio files under 10MB or with "SFX" in the name  

---

 ▶️ How to Run

1. Install the `watchdog` library:
   ```bash
   pip install watchdog
   ```

2. Update the following variables in the script:
   ```python
   source_dir = "C:\Users\YourUsername\Downloads"
   dest_dir_music = "C:\Categories\Music"
   # ... (update other paths as needed)
   ```

3. Run the script:
   ```bash
   python auto_organizer.py
   ```

4. The script will now monitor your Downloads folder and auto-move new files into their respective folders.

---

## 🙋‍♂️ Why I Built This

I built this script as a small automation project in my free time to improve productivity and learn more about real-time file monitoring in Python. It helped me keep my system tidy while exploring practical scripting.

---

## 📬 Feedback & Contributions

If you have suggestions or would like to contribute, feel free to open an issue or pull request.
