# PDF Translation: File Uploads, Retention and Privacy

[Product overview](../README.md) · [Official Privacy Policy](https://pdftranslator.org/privacy-policy) · [Terms of Service](https://pdftranslator.org/terms-of-service)

PDFTranslator.org requires uploading PDFs for server processing. It is not a browser-only translation tool. This guide summarizes the published file-handling information and distinguishes server files from browser-local task history.

## What happens when you translate a PDF?

The website obtains an upload URL for object storage, uploads the selected PDF, and creates a translation task using your selected settings. When processing completes, the website provides result preview and download actions.

The service processes the document content and relevant metadata needed to perform translation. Do not infer that online translation happens entirely on your device because some file checks or preview operations run in the browser.

## Three different retention windows

| Item | Published behavior |
| --- | --- |
| Source PDFs and files related to cancelled or failed tasks | Automatically deleted within 24 hours of upload. |
| Generated translations and download links | Retained for up to 24 hours after task completion. |
| Recent task records in browser localStorage | Kept for up to 24 hours after task creation; they may be removed sooner from the browser. |

These windows begin at different events. A visible local task record does not guarantee an available download, and removing browser history does not itself delete server files. Save a copy of the translated PDF promptly rather than relying on recent tasks for storage.

## Browser storage, analytics and service providers

The website uses browser storage for recent tasks and preferences. Recent records are specific to the current browser profile; they are not an account-based archive shared between devices.

The published Privacy Policy describes object storage, analytics such as Google Analytics 4, and technical logs used to operate and improve the service. No account requirement does not mean that the site collects no usage data or makes no network requests.

Refer to the [Privacy Policy](https://pdftranslator.org/privacy-policy) for the current scope, purposes, third parties, security measures, and other details. This guide does not add a promise of immediate deletion, permanent availability, or zero data collection.

## Before uploading and sharing

Use only documents you are authorized to process and follow the site's [Terms of Service](https://pdftranslator.org/terms-of-service). Review the document for sensitive information before uploading it.

For public feedback or documentation contributions, use non-sensitive examples. Never post private PDFs, personal or confidential information, task identifiers, or signed upload and download links. Signed links can provide access to files while they remain valid.

## Related resources

- [PDF translation usage and troubleshooting](usage-guide.md)
- [Translation and formatting review](translation-review.md)
- [Product feedback on FeedLog](https://pdftranslator-org.feedlog.ai/)

Last checked: October 18, 2026. This is a product guide; the live website's published policies describe the current service.
