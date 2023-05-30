# Tools Used for Making Documents Accessible

## Document Accessibility

- MS Word - For editing Docx files and making them accessible
- Browser Extensions for Accessiblity Evaluation of HTML documents: 
    -  [WAVE Browser Extension](https://wave.webaim.org/extension/)
    -   [aXe Dev Tools plugin](https://www.deque.com/axe/browser-extensions/)
- Adobe Acrobat Pro - For Editing PDFs and making them accessible
-  [Pandoc 2.13+](https://pandoc.org/installing.html) - Used for coverting to various formats (PDF not supported)
-  [Poppler PDF binaries](http://blog.alivate.com.au/poppler-windows) (pdftotext, pdfinfo, pdfseparate, pdfimages etc.)
-  [MikTeX](https://miktex.org/download) - LaTex to html - A LaTeX installation containing  `make4ht`  and  [tex4ht](https://www.tug.org/tex4ht/)

## Working with Image Based PDFs
- Tools for taking screenshots - [Greenshot](https://getgreenshot.org/downloads/)  (PC or macOS),  [Flameshot](https://github.com/flameshot-org/flameshot/releases)  (Linux)
- OCR tools for PDFs

| S.No. | Name of the tool    | Used for                                                                                                                                                        |
|-------|---------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1     | [Tesseract OCR](https://tesseract-ocr.github.io/tessdoc/Downloads.html)      | An Opensource Tool for OCR of documents with multiple languages and form (provides less accuracy than other paid tools and don't have support for math content) |
| 2     | [Abbyy Finereader](https://pdf.abbyy.com/)    | Provides offline recognition for most of roman scripts based content and other major languages                                                                  |
| 3     | [Infty Reader](https://www.sciaccess.net/en/InftyReader/)        | Provides offline Roman scripts content and Math Recognition                                                                                                     |
| 4     | [Google Cloud Vision](https://cloud.google.com/vision) | API based tool to convert various regional languages and handwritten content. Provided very good accuracy for images with low resolution as well                |
| 5     | [Mathpix](https://mathpix.com/)             | An Online tool for recognizing Math and Chemical diagrams from PDFs. Provides good accuracy for Math, Headings and Tables detection                             |

## EPUB Remediation Tools

-   EPUB Reader - [Thorium](https://www.edrlab.org/software/thorium-reader/)
-   EPUB Accessibility Checker - [DAISY Ace](https://daisy.github.io/ace/)  (“app” or “cli”)
-   EPUB Editor (e.g. [Sigil](https://sigil-ebook.com/sigil/download/))

##  Screen Reading Software

-   Windows: [NVDA](https://www.nvaccess.org/download/)
-   Mac OS: VoiceOver (preinstalled) [Learn more](https://www.youtube.com/watch?v=5R-6WvAihms)
-   ChromeOS: ChromeVox (preinstalled)
-   Linux: Gnome Orca (usually preinstalled)

## Command Line Tools

-  [Powershell](https://docs.microsoft.com/en-us/powershell/scripting/install/installing-powershell), xterm, etc.
-  [Git for Windows](https://git-scm.com/download/win) (PC) or Terminal (Linux/macOS)

## Math Content
- [MathJax](https://www.mathjax.org/) - For rendering math in HTML/EPUB documents
- [MathCAT](https://github.com/NSoiffer/MathCAT) - It provides accessible methods to read mathml content
