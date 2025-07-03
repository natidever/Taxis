


# 📁 Taxis
A blazing-fast Rust CLI tool to **automatically organize your messy folders** into neat subdirectories like `Videos`, `Music`, `Photos`, `Documents`, and more — all with a single command.

---

## ✨ Features

- 🧠 Categorizes files by type: Videos, Music, Photos, Documents, Archives, and Others  
- ⚡ Built with Rust for lightning-fast performance  
- 📂 Works recursively through nested folders  
- 🧼 Keeps your workspace clean and structured  
- 🔧 Simple CLI interface – one command is all it takes

---

## 🚀 Installation



clone the repo and build it manually:

```bash
git clone https://github.com/your-username/file_sorter_rs.git
cd file_sorter_rs
cargo build --release
```

The binary will be in `target/release/file_sorter_rs`.

---

## 🛠️ Usage

```bash
file_sorter_rs /path/to/your/folder
```

Example:

```bash
file_sorter_rs ~/Downloads
```

### ✅ What It Does:

Given a folder like this:

```
Downloads/
├── vacation.jpg
├── song.mp3
├── movie.mp4
├── document.pdf
├── archive.zip
```

After running the tool:

```
Downloads/
├── Photos/
│   └── vacation.jpg
├── Music/
│   └── song.mp3
├── Videos/
│   └── movie.mp4
├── Documents/
│   └── document.pdf
├── Archives/
│   └── archive.zip
```

---

## 📂 Supported File Types

| Category   | Extensions                                   |
|------------|----------------------------------------------|
| Videos     | `.mp4`, `.mkv`, `.avi`, `.mov`, `.webm`      |
| Music      | `.mp3`, `.wav`, `.flac`, `.aac`, `.ogg`      |
| Photos     | `.jpg`, `.jpeg`, `.png`, `.gif`, `.bmp`, `.svg` |
| Documents  | `.pdf`, `.docx`, `.txt`, `.pptx`, `.xlsx`    |
| Archives   | `.zip`, `.rar`, `.7z`, `.tar`, `.gz`         |
| Others     | Everything else goes here                   |

---

## About the Name: Taxis

**Taxis** (τάξις) is a Greek word meaning **order**, **arrangement**, or **organization**. 

In ancient Greek philosophy and biology, *taxis* refers to the natural ordering or classification of things — making sense out of chaos by arranging elements systematically.

The name perfectly reflects the purpose of this tool: to bring structure and order to your files in an efficient and elegant way.



## 🦀 Built With

- [Rust](https://www.rust-lang.org/) – Safe, fast, and fearless

---

## 📜 License

MIT License © 2025 Natnael Sisay

---
