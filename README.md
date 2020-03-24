# Watermark_PDF_Merger

Add Watermark to pdf files

To make the converter work u need to download pip to also install the PyPDF2 library used for PDF processing in the project and u have install python3 on the computer

PDF toolkit https://pypi.org/project/PyPDF2/

Orginal.pdf is the test file to add watermark 2 but can ofc be used with any pdf file just change the template = PyPDF2.PdfFileReader(open('{FILENAME}.pdf', 'rb'))

--Running Script--

1: To run the script open a terminal and CD to the PDFMerger folder (Desktop\PDFMerger)

2: change the watermark variabl with the watermark u want to add to all the pages watermark = PyPDF2.PdfFileReader(open('{WATER MARK FILE NAME}.pdf', 'rb'))

3: type in the terminal: Python PDFMerger.py

