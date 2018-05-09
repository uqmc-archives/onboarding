# Title: How To Archive (onboard) Documents for the UQMC

# Author: Nicholas Tierney

# Date last modified: 2018-05-09

Ok, so here are some of my guidelines for the process of archiving material from the UQMC, known as "onboarding".

This document will change over timem and should be regarded as a Work In Progress.

The overall process should follow these steps:

1. Record documents in the highest possible resoulution
2. Save documents with the filename yyyy-mm-dd-brief-description-of-text
3. After the document is scanned, do a quality check
4. Backup the digital archives in separate locations online
5. Produce optical character recognition (OCR) where possible
6. Validate the OCR process

These are now outlined in more detail

**note**: These steps may seem excessive, but this is how state of the art research is performed, and I think that we have a responsibility to ensure that this is held at a high standard.

# 1. Record documents in the highest possible resoulution

Current standard is 600 DPI with the highest possible quality (least amount of compression)

# 2. Save documents with the filename yyyy-mm-dd-brief-description-of-text

E.g, "1954-10-25-vidlers-chimney.pdf"

# 3. After the document is scanned, do a quality check

- Inspect page margins, is anything cut off?
- Inspect page numbers, are there any pages missing?
- Are the pages oriented the right way up?
- Is the quality good?
- Have all pages been included?
- Have the document alongside with you when you do this check

# 4. Backup the digital archives in separate locations online

For example I have:

- one copy on my computer
- one copy on a personal hard disk
- one copy on google drive

# 5. Produce text from image using optical character recognition (OCR) where possible

A really good (free!) way to automate this is to use the OCR software [OCRmyPDF](https://ocrmypdf.readthedocs.io/en/latest/cookbook.html), which adds the text into the PDF. 
It is powered by the software "Tesseract", which is FOSS.

You can create a text file and add the text to the PDF with the command:

```
ocrmypdf --sidecar output.txt input.pdf output.pdf
```

This performs the OCR on "input.pdf" and produces a textfile "output.txt" and PDF "output.pdf".

There then needs to be some way to add the text back to the PDF, but in my opinion, that is not as big a priority.

The PDF is then checked in to the online archive.

# 6. Validate the OCR process

Once the OCR is done, the text should be checked into github, and then a branch made to read over the text.

Ideally, two people make branches and compare then to each other. 

Some notes on doing the comparison

- The text file must be edited in a plain text file editor, such as notepad, notepad++, textwrangler, atom, sublime, etc.
- Do not use Microsoft Word, OpenOffice, or similar. This is because software like Microsoft word adds extra hidden character information in a page which means that the text may not be able to be searched effectively or correctly. This is very important!
- Read through the text file and the scanned file, and make corrections in the text file.

Once both editors have made their suggestions and changes, they are to compare text documents for any errors or questions. 

# 7. Share online

Sharing online means that a few things need to be done:

- PDFs need to be compressed / quality reduced to a reasonable size (~200kb / page)
- Text either added as an accompanying document or included somehow into the PDF

# 8. Sharing photos / albums

Would be great to share some of the old club trip photos from the past.
We could host them on the website or something, but I'm not really sure
if we should have a process where we just choose the best photos?
Also, I totally need to get back to Nigel about these climbing magazine issues.
