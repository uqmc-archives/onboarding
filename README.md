# Title: How To Archive (onboard) Documents for the UQMC

# Author: Nicholas Tierney

# Date: 2016-11-20

Ok, so here are some of my guidelines for the process of archiving material from the UQMC, known as "onboarding"
This document will change over timem and should be regarded as a Work In Progress.

The overall process should follow these steps:

1. Record documents in the highest possible resoulution
2. Save documents with the filename yyyy-mm-dd-brief-description-of-text
3. After the document is scanned, do a quality check
4. Backup the digital archives in separate locations online
5. Produce optical character recognition (OCR) where possible
6. Validate the OCR process

These are now outlined in more detail

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
- I recommend having the document alongside with you when you do this check
- This might seem a bit over the top and paranoid, but it is worthwhile doing as it ensures that we have complete archives.

# 4. Backup the digital archives in separate locations online

For example I have:
- one copy on my computer
- one copy on a personal hard disk
- one copy on google drive

# 5. Produce optical character recognition (OCR) where possible

I use the free open source OCR software "Tesseract" along with a makefile written by Lincoln Mullen. This takes a PDF and bursts it into high quality PNG images, then performs the character recognition and puts it into a separate .txt file, and even separates this out into separate pages.

# 6. Validate the OCR process

I have not validated any of the text as yet, but the way I imagine this process is as follows:
- Two people are assigned a single document
- They save a copy of the original OCR text file for editing
- They must edit the text file in a text file editor, such as notepad, notepad++, textwrangler, atom, sublime, etc. They must not use Microsoft Word, OpenOffice, or similar. This is because software like Microsoft word adds extra hidden character information in a page which means that the text may not be able to be searched effectively or correctly. This is very important.
- They read through the (copied for editing) text file and the scanned file, and make corrections in the text file.
- Once both editors have made their suggestions and changes, they are to compare text documents for any errors or questions.
- This may seem excessive, but this is how state of the art research is performed, and I think that we have a responsibility to ensure that this is held at a high standard.

# 7. Share online

Sharing online means that a few things need to be done:
- PDFs need to be compressed / quality reduced to a reasonable size (~200kb / page)
- Text either added as an accompanying document or included somehow into the PDF

# 8. Sharing photos / albums

Would be great to share some of the old club trip photos from the past.
We could host them on the website or something, but I'm not really sure
if we should have a process where we just choose the best photos?
Also, I totally need to get back to Nigel about these climbing magazine issues.
