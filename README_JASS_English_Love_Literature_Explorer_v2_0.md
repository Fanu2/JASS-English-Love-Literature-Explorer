# JASS English Love Literature Explorer

**Version 2.0**

A lightweight PySide6 desktop reader and library explorer for an offline collection of English EPUB books focused on romance, love, courtship, passion, sensual literature, and related fiction.

The application is designed to work directly with an existing EPUB collection without requiring a database, internet connection, AI model, or heavy machine-learning framework.

---

## Features

### 📚 EPUB Library

- Recursively scans the selected folder for `.epub` files.
- Displays the complete book collection in a searchable library.
- Opens EPUB content directly inside the application.
- No conversion of the original EPUB files is required.

### 🔎 Library Search

Search the collection by:

- Book title
- Author
- Filename

The list updates as you type.

### 🏷️ Categories

Books can be filtered into:

- **All categories**
- **Love / Romance**
- **Romance / Courtship**
- **Sensual / Erotic Literature**
- **Classical / Legendary Romance**
- **Fiction / Related**
- **★ Favorites**

Categories are lightweight, filename/title-based classifications intended for convenient browsing rather than scholarly metadata classification.

### ⭐ Favorites

Books can be marked as favorites.

Favorites are stored locally and remain available when the application is restarted.

### 📖 EPUB Reader

The integrated reader provides:

- Comfortable long-form reading
- Book title and author information
- Category information
- Previous/Next content-section navigation
- Adjustable reading font size
- Georgia reading font
- Text selection

### 🔍 Find Within Book

Use the reader search field to find text inside the currently displayed book section.

The application automatically wraps around to the beginning when appropriate.

### 🔤 Reading Controls

Text size can be changed using:

- **A−**
- **A+**
- View → Larger Text
- View → Smaller Text
- View → Reset Text Size

The selected font size is remembered between sessions.

### 📂 Folder Selection

The default library folder is:

```text
C:\Users\singh\Downloads\JASS_English_Love_Literature
```

You can choose another EPUB collection through:

**File → Choose EPUB Folder...**

The selected folder is remembered.

### 📊 Library Statistics

The Statistics window reports:

- Total EPUB books
- Number of favorites
- Books by category

### 📤 Export

The application can export:

#### Current Book

The currently displayed text can be exported to a `.txt` file.

#### Book Inventory

The complete library inventory can be exported with:

- Number
- Title
- Author
- Category
- Filename

---

## Requirements

### Software

- Python 3.10+
- PySide6

For the user's current environment, Python 3.14 and PySide6 are supported by the application's standard Python implementation.

Install PySide6 if necessary:

```powershell
py -m pip install PySide6
```

### No Heavy Dependencies

This application does **not** require:

- PyTorch
- TensorFlow
- Transformers
- Ollama
- CUDA
- GPU
- Hugging Face libraries
- SQLite
- External EPUB libraries

EPUB extraction is performed using Python's standard-library ZIP and HTML functionality.

---

## Running the Application

Place the Python file in your Downloads folder, or in the project directory.

Example:

```powershell
cd C:\Users\singh\Downloads
py JASS_English_Love_Literature_Explorer_v2_0.py
```

The application will automatically look for:

```text
C:\Users\singh\Downloads\JASS_English_Love_Literature
```

If that folder is not available, use:

**File → Choose EPUB Folder...**

---

## Recommended Folder Structure

```text
JASS_English_Love_Literature
│
├── *.epub
├── *.epub
├── *.epub
└── ...
```

Subfolders are also supported because the application scans recursively.

For example:

```text
JASS_English_Love_Literature
│
├── Romance
│   ├── book1.epub
│   └── book2.epub
│
├── Classic
│   ├── book3.epub
│   └── book4.epub
│
└── Sensual
    └── book5.epub
```

---

## Application Layout

```text
┌─────────────────────────────────────────────────────────────┐
│ JASS English Love Literature Explorer                       │
├─────────────────────────────────────────────────────────────┤
│ Search │ Category │ Show file path │ Results                │
├──────────────────────┬──────────────────────────────────────┤
│                      │ Book Title                            │
│   Book Library       │ Author • Category • Filename          │
│                      │                                      │
│   ★ Book 1           │                                      │
│   Book 2              │             EPUB READER              │
│   Book 3              │                                      │
│   Book 4              │                                      │
│                      │                                      │
├──────────────────────┴──────────────────────────────────────┤
│ Find text in this book...                                   │
└─────────────────────────────────────────────────────────────┘
```

---

## Local Settings

The application uses `QSettings` to remember user preferences.

Stored settings include:

```text
Selected EPUB folder
Favorite books
Recent reading history
Reader font size
```

No account or online service is required.

---

## Privacy

JASS English Love Literature Explorer is designed as a **local/offline application**.

It does not:

- Upload books
- Send reading searches to a server
- Require an online account
- Connect to an AI service
- Require cloud storage

Your EPUB files remain on your computer.

---

## Current Version

### v2.0

Enhanced release containing:

- EPUB library scanner
- Recursive folder scanning
- Search
- Category filtering
- Favorites
- EPUB reader
- Section navigation
- In-book search
- Font controls
- Persistent settings
- Library statistics
- Current-book export
- Book-list export
- Folder selection
- Refresh library

---

## Project Philosophy

The project intentionally follows a simple architecture:

```text
EPUB files
    ↓
JASS Explorer
    ↓
Library Browser
    ↓
EPUB Reader
    ↓
Local Search / Reading
```

There is no requirement to preprocess the collection into a database before reading it.

This makes the application particularly suitable for experimenting with large literary collections while keeping the installation lightweight.

---

## Possible Future Enhancements

Potential future versions could add:

- Chapter/table-of-contents navigation
- Persistent bookmarks with saved positions
- Reading history window
- Recently opened books
- Better EPUB metadata extraction
- Cover-image display
- Global full-text search across all EPUBs
- Search-result highlighting
- Notes and annotations
- Custom reading themes
- Dark reading mode
- Database indexing for very large collections
- Duplicate-book detection
- Automatic metadata extraction
- Gutenberg/source ID tracking
- Corpus statistics
- Export to SQLite/FTS5

These are intentionally left outside v2.0 to keep the current application stable and lightweight.

---

## Project Name

**JASS English Love Literature Explorer**

Suggested repository name:

```text
JASS-English-Love-Literature-Explorer
```

Suggested Python filename:

```text
JASS_English_Love_Literature_Explorer_v2_0.py
```

---

## License / Source Material

The application code is a JASS project.

The EPUB files are separate source materials and may have their own copyright and licensing conditions. Users should verify the copyright status and applicable usage rights for each book before redistribution.

For public-domain material obtained from Project Gutenberg or other sources, retain the source's attribution and applicable license/public-domain notices.

---

## Status

**Stable v2.0**

The application is considered a practical stable release for browsing and reading the current EPUB collection.

Future development can focus on incremental improvements without changing the basic lightweight architecture.

---

## Author

**JASS**

Offline-first • Lightweight • Local Library Tools
