Tabular Data Extraction

Input: OCR processed pdf
Output: .csv and .xls file

The important steps for running the project is as follows:

Windows:
1. Install python 3.6 in the system.
2. Install the required packages mentioned in 'requirement.txt'
	Or simply use the command: 
		pip install -r requirement.txt
3. We have to run the pdftohtml.exe
4. Then we need to keep the ocr processed pdf in data folder of any of the examples and use the command
   pdftohtml -c -hidden -xml ocrProcessedPdf.pdf ocrProcessedPdf.xml
5. Then simply change in the eg named files the path and the file names.
6. Now run the eg.py file. You will get the desired ouput in the generated_output folder.

Linux:
1. Install python 3.6 in the system.
2. Install the required packages mentioned in 'requirement.txt'
	Or simply use the command: 
		pip install -r requirement.txt
3. Then we need to keep the ocr processed pdf in data folder of any of the examples and use the command
   pdftohtml -c -hidden -xml ocrProcessedPdf.pdf ocrProcessedPdf.xml
4. Then simply change in the eg named files the path and the file names.
5. Now run the eg.py file. You will get the desired ouput in the generated_output folder.

**pdftabextract is the package already included in python.