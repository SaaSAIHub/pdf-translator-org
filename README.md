[English](README.md) · [简体中文](README.zh-CN.md) · [Español](README.es.md) · [Português (Brasil)](README.pt-BR.md)

<img src="assets/pdftranslator-logo.png" alt="PDFTranslator.org logo" width="64" height="64">

# PDFTranslator.org — Free PDF Translator Online (AI-Powered)

[PDFTranslator.org](https://pdftranslator.org/) is a free online AI PDF translator for translating complete PDF documents into 100+ languages. Upload a PDF, choose the source and target languages, and preview or download the translated PDF. The service is designed to preserve text layout, tables, images, and page structure as closely as possible.

**No sign-up. Up to 20MB per PDF. 600 free pages per calendar month.**

[Translate a PDF online](https://pdftranslator.org/) · [Feedback and feature requests](https://pdftranslator-org.feedlog.ai/)

This is the official product documentation repository maintained by [SaaSAIHub](https://github.com/SaaSAIHub). It contains guides and translation examples for the hosted website; the application source code and translation engine are not included.

![PDFTranslator.org online PDF translator showing PDF upload, language selection, translation style, and free allowance](assets/pdf-translator-online-homepage.jpg)

## Free AI PDF translation: features and limits

PDFTranslator helps students, researchers, and professionals read foreign-language PDFs without copying and pasting each paragraph into a text translator.

| Feature | Current behavior |
| --- | --- |
| PDF input and output | Upload a PDF; preview and download a translated PDF. |
| 100+ languages | Select the source and target languages for your document. |
| Formatting preservation | Designed to retain layout, tables, images, and page structure; review complex documents. |
| Translation styles | General, Academic, Legal, or Business. |
| Free monthly allowance | 600 pages per calendar month, resetting at the start of each month. |
| File size | Up to 20MB per PDF. |
| Parallel tasks | Up to 3 queued or processing tasks at a time; both use a slot. |
| No sign-up | Use the browser-based service without an account or installation. |
| Recent translations | Track recent tasks in the same browser and save completed results promptly. |

## How to translate a PDF online

1. Open [PDFTranslator.org](https://pdftranslator.org/) and select or drop your PDF.
2. Choose the document's source language and your target language.
3. Select **General**, or choose **Academic**, **Legal**, or **Business** to match the content.
4. Select **Start Translation**. Keep the page open until upload and task creation finish.
5. Follow progress in **Recent translations** on the homepage.
6. Preview or download the completed PDF, then check important text and formatting against the original.

Keep the original and download your result promptly. See the [PDF translation usage guide](docs/usage-guide.md) for file preparation, task limits, and troubleshooting.

## PDF translation examples: research papers, handbooks and textbooks

The following English-to-Chinese page comparisons show document structure and translated text from the product's published examples. They illustrate individual pages, not a guarantee for every PDF or language pair.

### Research paper translation

Read a research abstract in another language while keeping paragraphs and keywords in context.

<table>
<tr><th>English original — abstract and keywords</th><th>Chinese translation — abstract and keywords</th></tr>
<tr><td width="50%"><img src="assets/research-paper-english.webp" alt="Research paper translation — English original — abstract and keywords" width="100%"></td><td width="50%"><img src="assets/research-paper-chinese.webp" alt="Research paper translation — Chinese translation — abstract and keywords" width="100%"></td></tr>
</table>

### Translate PDF handbooks and manuals

Keep section headings, numbered instructions, and lists together when reading a handbook.

<table>
<tr><th>English original — handbook</th><th>Chinese translation — handbook</th></tr>
<tr><td width="50%"><img src="assets/handbook-english.webp" alt="Translate PDF handbooks and manuals — English original — handbook" width="100%"></td><td width="50%"><img src="assets/handbook-chinese.webp" alt="Translate PDF handbooks and manuals — Chinese translation — handbook" width="100%"></td></tr>
</table>

### Translate PDF textbooks and course materials

Compare explanations, lists, and diagrams while studying a translated textbook page.

<table>
<tr><th>English original — textbook</th><th>Chinese translation — textbook</th></tr>
<tr><td width="50%"><img src="assets/textbook-english.webp" alt="Translate PDF textbooks and course materials — English original — textbook" width="100%"></td><td width="50%"><img src="assets/textbook-chinese.webp" alt="Translate PDF textbooks and course materials — Chinese translation — textbook" width="100%"></td></tr>
</table>

For a closer review of terminology, tables, figures, and reading order, use the [translation and formatting checklist](docs/translation-review.md).

## Supported languages and PDF translation use cases

PDFTranslator.org supports 100+ translation languages, including English, Chinese, Spanish, French, German, Portuguese, Japanese, and Korean. The interface language and the document's translation languages are separate choices.

| Reading goal | What to select |
| --- | --- |
| Translate a PDF from English to Spanish | Choose English as the source and Spanish as the target. |
| Translate a PDF document to English | Choose the document's actual source language and English as the target. |
| Translate a PDF to German | Choose the source language and German as the target. |
| Translate an English PDF to Chinese or Portuguese | Choose English and the corresponding target-language option. |

Use **Academic** for research papers and course materials, **Business** for reports and business documents, and **General** for everyday reading and manuals. **Legal** is available for legal terminology; review consequential wording before relying on it.

Website interfaces: [English](https://pdftranslator.org/) · [中文](https://pdftranslator.org/zh) · [Español](https://pdftranslator.org/es) · [Português (Brasil)](https://pdftranslator.org/pt-BR).

## FAQ about PDF translation

### Is PDFTranslator.org a free PDF translator without sign-up?

Yes. PDFTranslator.org currently includes 600 free pages per calendar month without registration. The allowance resets at the start of each month. Each PDF may be up to 20MB, and up to 3 queued or processing tasks can run at once.

### Can I translate a PDF without losing formatting?

PDFTranslator.org aims to preserve the layout, tables, images, and page structure. Translated text can take more or less space than the original. Check complex tables, formulas, fonts, and page breaks; exact formatting is not guaranteed.

### Can I translate long PDF documents?

Yes, within the 20MB file-size limit, remaining monthly allowance, and limits displayed by the service. Splitting a PDF can help select relevant chapters or reduce individual file size, but it does not increase the free monthly allowance.

### Can I translate a scanned PDF?

Image-only scans may need OCR before PDF translation. If the website cannot extract text, follow its OCR guidance or prepare a searchable PDF using an OCR tool, then try again. Review recognized text before translating it.

### Does the service produce a Word document?

The main translation workflow accepts PDFs and returns translated PDFs. This repository does not describe a PDF-to-Word converter or editable DOCX output.

### How long can I access my translated PDF?

The published Privacy Policy states that generated results and their download links are retained for up to 24 hours after completion. Browser-local recent task records last up to 24 hours after task creation, which is a different window. Save your own copy promptly.

### Are my files processed locally?

No. PDF translation requires uploading the document for server processing. According to the [Privacy Policy](https://pdftranslator.org/privacy-policy), source PDFs and files associated with cancelled or failed tasks are deleted within 24 hours of upload. See the [file-handling guide](docs/privacy.md) for retention, local history, and analytics.

### Is this an open-source translator or a public API package?

This repository contains official documentation for the hosted PDFTranslator.org website. It does not include a self-hosted application, translation engine, or public API package.

## Guides, PDF tools and feedback

- [How to translate PDF files: usage and troubleshooting](docs/usage-guide.md)
- [PDF translation quality and formatting review](docs/translation-review.md)
- [File uploads, retention, and privacy](docs/privacy.md)
- [Split PDF](https://pdftranslator.org/tools/split-pdf) · [Merge PDF](https://pdftranslator.org/tools/merge-pdf) · [More PDF tools](https://pdftranslator.org/tools)
- [Report a problem or suggest a feature on FeedLog](https://pdftranslator-org.feedlog.ai/)
- [Contribute a documentation correction](CONTRIBUTING.md)

Use non-sensitive examples when reporting a problem. Do not publish private documents, task identifiers, or signed upload/download links.

**Product details last checked: October 18, 2026.** Features and limits may change; the [live website](https://pdftranslator.org/), [Privacy Policy](https://pdftranslator.org/privacy-policy), and [Terms of Service](https://pdftranslator.org/terms-of-service) describe the current service.
