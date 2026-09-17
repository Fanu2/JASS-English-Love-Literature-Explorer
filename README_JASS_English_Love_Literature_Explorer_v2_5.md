# JASS English Love Literature Explorer v2.5

A desktop literature exploration and creative-writing companion built with **Python + PySide6**.

The application combines an English love-literature library reader with a visual **Creative Studio** for turning literary discoveries, quotations, passages, and personal thoughts into beautiful shareable designs.

---

## ✨ Highlights

### 📚 Library Reader

- Browse a curated collection of English literature in EPUB format.
- Explore books from the local literature folder.
- Read book content inside the application.
- Use the reader as a source of quotations and ideas for the Creative Studio.
- Designed for a local/offline personal literature collection.

### 🎨 Creative Studio

The Creative Studio is the main creative workspace of v2.5.

It can be used to create:

- 💌 Love letters
- 💬 Quotations
- 📖 Literary pages
- ❤️ Romantic messages
- ✨ Shareable literary cards
- 📝 Personal notes inspired by literature

The canvas provides a visual preview while designs are being created.

---

## 🖱️ Interactive Text Blocks

Text elements are designed to behave like objects on a page.

### Move

Select a text block and drag it to another position.

### Resize

Use the resize handle on the selected text block to change its width.

### Font controls

Text can be customized with options including:

- Font family
- Font size
- Bold
- Italic
- Alignment
- Text colour

Changes are reflected directly on the canvas.

---

## 🎨 Text Colour

v2.5 includes a reliable text-colour workflow.

1. Click a text block on the canvas.
2. Use **Choose Text Color…**
3. Select the desired colour.
4. Apply the colour.
5. The selected text block updates immediately.

Quick colour choices are also available for faster design work.

The colour selection is associated with the active text element so opening the colour dialog does not accidentally lose the selected text.

---

## 🖼️ Backgrounds

Creative Studio supports both simple and photographic backgrounds.

### Background colour

Choose a custom canvas background colour.

### Background image

Select an image from the computer and use it as the canvas background.

### Background opacity

Adjust the transparency of the background image using the opacity control.

This makes it possible to create subtle photographic backgrounds that do not overpower the text.

### Remove background

The background image can be removed without removing the text elements.

---

## 📄 Multi-Page Documents

Creative Studio supports designs that extend beyond a single page.

Pages can be:

- Added
- Removed
- Scrolled vertically
- Exported individually
- Exported as a complete document

Long passages can flow across multiple pages.

### Word-style margins

Multi-page text uses document margins so that each page has a clean:

- Top margin
- Bottom margin
- Left margin
- Right margin

This prevents text from being placed directly against page edges.

Margins can be adjusted from the **Document Margins** controls.

---

## 📐 Page Sizes

Creative Studio supports different canvas/page formats, including portrait and letter-style layouts.

The page window is vertically scrollable, making it practical to work with long literary passages and multi-page designs.

---

## 🌹 Themes

Creative Studio includes a collection of romantic and literary visual themes.

Themes include styles such as:

- Romantic
- Literary
- Elegant
- Vintage
- Soft
- Dark
- Minimal
- Warm
- Wine & Velvet
- Moonlit Blue
- Sage & Cream
- Peach Glow
- Mauve Poetry
- Black & Champagne

Themes provide a starting point and can then be customized using the available controls.

---

## 💌 Creative Uses

The studio is particularly suited to creating material that can be shared with another person.

Examples:

### Love quotation

> A beautiful quotation discovered while reading.

### Personal message

A short message written specifically for someone.

### Love letter

A longer multi-page letter with custom typography and background imagery.

### Literary card

A quotation combined with a carefully selected background and theme.

### Reading discovery

A memorable passage transformed into a visual literary page.

---

## 💾 Save & Share

Creative projects can be saved and loaded for later editing.

Available functions include:

- Export PNG
- Copy PNG to Clipboard
- Save Design Project
- Load Design Project
- Clear Text Elements
- Export pages separately

This makes the application useful both as a literature reader and as a small personal publishing/design tool.

---

## 🧭 Typical Workflow

### 1. Read

Open the **Library Reader** and browse the local EPUB collection.

### 2. Discover

Find a quotation, passage, idea, or literary inspiration.

### 3. Create

Move to **Creative Studio**.

### 4. Choose a design

Select a suitable theme or create a new design.

### 5. Add text

Add the discovery as:

- Quote
- Body text
- Personal message

### 6. Customize

Adjust:

- Font
- Font size
- Alignment
- Bold/italic
- Text colour
- Background colour
- Background image
- Background opacity
- Margins
- Page size

### 7. Arrange

Drag and resize text blocks until the composition looks right.

### 8. Export

Save the finished design as PNG or copy it directly to the clipboard for sharing.

---

## 🛠️ Technology

- **Python 3**
- **PySide6**
- Qt Graphics View / Graphics Scene
- QGraphicsTextItem-based text elements
- Local EPUB literature collection
- PNG image export
- JSON-style project persistence

No cloud service is required for the core application.

---

## 📁 Suggested Project Structure

```text
JASS English Love Literature Explorer
│
├── JASS_English_Love_Literature_Explorer_v2_5_Creative_Studio.py
├── README.md
│
└── JASS_English_Love_Literature/
    └── *.epub
```

The EPUB directory can contain the user's own legally obtained literature collection.

---

## ▶️ Running the Application

From PowerShell:

```powershell
cd C:\Users\singh\Downloads
py JASS_English_Love_Literature_Explorer_v2_5_Creative_Studio.py
```

Make sure PySide6 is installed:

```powershell
py -m pip install PySide6
```

---

## 🖥️ Design Philosophy

JASS English Love Literature Explorer is intended to be more than an EPUB reader.

Its purpose is to connect:

**Reading → Discovery → Reflection → Creation → Sharing**

A passage discovered while reading can become a quotation card, a literary page, a personal message, or a complete love letter without leaving the application.

The Creative Studio therefore acts as a small personal literary publishing workspace.

---

## 🔒 Local-First Approach

The application is designed around a local collection of books and local creative projects.

Your literature collection and saved designs can remain on your own computer.

No online account is required for the core reading and creative workflow.

---

## 📌 Version

**JASS English Love Literature Explorer v2.5**

### v2.5 milestone

This version establishes the current **stable Creative Studio baseline** with:

- Functional text colour selection
- Quick text colours
- Draggable text blocks
- Resizable text blocks
- Live canvas updates
- Background colour controls
- Background image controls
- Background opacity
- Multi-page canvas
- Scrollable document workspace
- Word-style page margins
- Multiple themes
- PNG export
- Clipboard export
- Design project save/load

---

## 🌹 Stable Baseline

**v2.5 should be treated as the stable Creative Studio baseline.**

Future improvements should preferably extend the existing architecture without unnecessarily changing or removing the features that are already working reliably.

---

## License

This project is a personal software project.

Book files and literary texts are separate from the application and remain subject to their respective copyright and licensing terms.

---

**JASS English Love Literature Explorer — Read. Discover. Create. Share.**
