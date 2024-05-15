This application converts text from a PDF file into speech and saves it as an MP3 audio file.

Features

Converts PDF files to MP3 audio format.

Allows selecting specific page ranges from the PDF.

User-friendly interface provided by Tkinter.

Utilizes PyPDF2 for PDF manipulation and gTTS (Google Text-to-Speech) for text-to-speech conversion.


Installation

No installation is needed.


Usage

Download the EXE file and double click to execute.

Run the pdf_to_mp3.py script.

Select a PDF file from your system.

Specify the page range to convert.

Wait for the conversion process to finish.

Once completed, the MP3 file will be saved in the same directory as the input PDF file.

If the conversion is successful, the folder containing the MP3 file will be opened automatically.

Example

Suppose you have a PDF file named example.pdf with 10 pages. To convert pages 3 to 7 into an MP3 file, follow these steps:

Run the EXE file.
Select example.pdf.
Enter 3 as the start page and 7 as the end page.
Wait for the conversion to complete.
The resulting MP3 file, named example_pages_3-7.mp3, will be available in the same directory as example.pdf.

Notes
Make sure the PDF file does not have any restrictions (e.g., password protection) preventing text extraction.
The converted MP3 file's quality and voice depend on the text-to-speech engine (gTTS) and may vary.
For optimal results, ensure a stable internet connection for gTTS to function properly.

License
This project is licensed under the MIT License.
