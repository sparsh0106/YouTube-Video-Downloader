# 🎬 YouTube Video Downloader (Tkinter GUI)

A desktop GUI application built with **Python**, **Tkinter**, and **pytube** that downloads YouTube videos in their highest available resolution directly from a pasted video URL.

---

## 📂 Repository Structure

- `another_one.py`: Main Tkinter GUI application and `pytube` stream downloader.
- `Synopsis.docx`: Project synopsis and documentation report.
- `README.md`: Setup and usage instructions.

---

## ✨ Features

- **Highest-Resolution Stream Selection**: Automatically queries and downloads the highest progressive resolution stream available (`yt.streams.get_highest_resolution()`).
- **Minimal Desktop UI**: Paste any YouTube URL and trigger the download with a single click, with completion status displayed in the window.

---

## 🚀 Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/sparsh0106/YouTube-Video-Downloader.git
   cd YouTube-Video-Downloader
   ```

2. **Install dependencies**:
   ```bash
   pip install pytube
   ```

3. **Run the application**:
   ```bash
   python another_one.py
   ```
   *(Note: You can customize the `save_path` variable inside `another_one.py` to your preferred local downloads directory.)*

---

## 👤 Author

**Sparsh Agarwal** — [GitHub](https://github.com/sparsh0106) · [LinkedIn](https://www.linkedin.com/in/sparsh-agarwal-4b443b304/)
