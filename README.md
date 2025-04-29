


# 📁 file_organizer

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

### With `cargo`:

```bash
cargo install file_sorter_rs
```

Or clone the repo and build it manually:

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

## 🧪 Example Output

```bash
> file_sorter_rs ./chaotic_folder
[✓] Moved 5 photos
[✓] Moved 2 videos
[✓] Moved 3 music files
[✓] Moved 4 documents
[✓] Moved 1 archive
```

---

## 🦀 Built With

- [Rust](https://www.rust-lang.org/) – Safe, fast, and fearless

---

## 📜 License

MIT License © 2025 Natnael Sisay

---
