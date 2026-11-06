# QFormat — Question Formatter & PDF Maker

**Transform plain text into beautifully formatted study sheets and professional PDFs.**

QFormat is a browser-based tool designed to turn simple questions, answers, and study notes into professionally formatted revision sheets and exam papers.

Simply paste your content, customize its appearance, preview the result in real time, and export it as a PDF.

## ✨ Features

### 📝 Smart Text Formatting
- Convert plain text into structured documents.
- Automatically recognize numbered questions.
- Support multiple-choice questions and answers.
- Organize content into sections.
- Highlight notes, key terms, and important facts.
- Support reading passages with source citations.
- Support essay questions with customizable answer lines.

### 🌍 Arabic & English Support
- Full Arabic and English content support.
- Automatic text direction detection (RTL / LTR).
- Arabic question formats and answer keywords.
- Support Arabic and English numbering styles.

### 🎨 Document Customization
- 6 built-in color themes.
- 6 document layout styles.
- Custom title, question, answer, and note colors.
- Multiple font options.
- Adjustable font sizes and spacing.
- Custom page margins.
- Decorative page borders and frames.

### 📄 Page Settings
- A4, Letter, and A5 paper sizes.
- Portrait and Landscape orientations.
- Automatic multi-page document layout.
- Live document preview.

### 📚 Revision & Exam Modes
- **Revision Mode:** Display answers directly below their questions.
- **Exam Mode:** Move answers into a separate Answer Key and generate dotted answer lines for essay questions.

### 📥 PDF Export
- **Quick PDF:** Fast, image-based PDF export.
- **High Quality PDF:** Sharp, selectable, and searchable text using a local PDF rendering service.

### 💾 Project Management
- Save and load projects.
- Rename documents.
- Delete saved projects.
- Automatically save changes.
- Store project settings and formatting preferences locally.

## 🛠️ Built With

- HTML5
- CSS3
- JavaScript
- html2canvas
- jsPDF
- Google Fonts
- Headless Chromium (High Quality PDF service)

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone YOUR_REPOSITORY_URL
```

### 2. Open the Project

Open the project folder and launch:

```text
index.html
```

You can use QFormat directly in your browser.

### 3. High Quality PDF Export (Optional)

High Quality PDF export requires the separate local PDF service.

Navigate to the `qformat-pdf-service` directory and run:

```bash
npm install
npm start
```

The service runs locally and handles PDF rendering through headless Chromium.

## 📖 Supported Text Format

QFormat uses a simple text-based syntax.

| Syntax | Purpose |
|---|---|
| `# Title` | Document title |
| `## Section` | Section heading |
| `1. Question` | Numbered question |
| `A) Option` | Multiple-choice option |
| `Answer: text` | Question answer |
| `Note: text` | Highlighted note |
| `Key Term: text` | Important term |
| `Key Fact: text` | Important fact |
| `Passage: text` | Reading passage |
| `Source: name` | Passage source |

Arabic equivalents are also supported.

## 🎯 Who Is It For?

- Students preparing revision sheets.
- Teachers creating exam papers.
- Educators organizing questions and answers.
- Anyone who wants to turn plain text into structured study documents.

## 🔮 Future Improvements

- More document templates.
- Additional customization options.
- Enhanced PDF export capabilities.
- More question formatting options.

## 👨‍💻 Developer

**Developed by CodePrint**

- GitHub: [@codeprintomar](https://github.com/codeprintomar)
- Website: [CodePrint](https://code-print.wasmer.app/)
- Projects: [Explore CodePrint](https://code-print.wasmer.app/projects.html)

---

<p align="center">
  **QFormat** — Make your study materials look better.
  <br>
  Made with ❤️ by CodePrint
</p>
