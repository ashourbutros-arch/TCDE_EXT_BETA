# TCDE PDF Extractor (Beta)

A Windows desktop tool that scans a folder of PDF engineering drawings and
extracts title-block information (location, title, revision, dates, etc.)
into an Excel sheet.

## Installation

1. Go to the **Releases** page of this repository.
2. Download `TCDE_PDF_Extractor_Beta_v1.3.exe` from the latest release.
3. Save it anywhere on your Windows PC (no installer needed — it's a
   single standalone file).
4. Double-click it to run.

That's it — no Python installation required.

## Optional: enable OCR-dependent fields

Some fields on older scanned drawings are read using OCR. If you want
those to work, install Tesseract OCR once:

```bash
winget install --id UB-Mannheim.TesseractOCR -e
```

Without it, the app still runs fine — those specific fields are just left
blank.

## First run

On first launch you'll be asked to accept the app's Terms and Conditions
(viewable in full from the popup or the About tab) before you can use it.

## Notes

- This is a **beta build** for testing and feedback.
- Windows only.
- No internet connection or account is required to use the app; it only
  reads the PDF files you point it at.

## Support

Questions or issues: contact the developers listed in the app's About tab.
