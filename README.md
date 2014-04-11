# PDF-embed-test

A very simple test case for embedding PDFs.

1. embed the file using `<object>` – this allows fallback content which will be *automatically* shown by the 
browser if no plugin can handle displaying the file.
2. As fallback content for the `<object>`, we load the PDF with `pdf.js`
3. Profit

## References

- Documentation of [pdfobject](http://pdfobject.com/) (library itself not used here)
- [Adobe's PDF Open Parameters](http://www.adobe.com/content/dam/Adobe/en/devnet/acrobat/pdfs/pdf_open_parameters.pdf)