## Img2PDF

**DRAFT**

Python script to create PDFs from TIFFs for UCLA IDEP newpapers.

Instructions for DL student workstations:

_Note: You will need Babun, Python (Anaconda), and Img2PDF installed._

1. Clone the Img2PDF repo from Github (you'll probably want to use Babun for this)
2. Open the Projects folder using "Run": `\\svm_dlib\Projects` (do not map the network drive)
  * Navigate to the newspaper/year folder that contains the TIFFs folder that you want to batch convert to PDFs
  * In this folder, create a new folder named "PDFs"
  * Leave this window open for the next step
3. Open Anaconda Prompt
  * To install the Python package Img2PDF, type `pip install img2pdf`
  * Navigate to the Image2PDF repo that you cloned (type `cd`, then drag the Image2PDF directory onto the Anaconda Prompt window to add the path, hit enter)
  * Type `python PdfFromImages.py`, hit Enter
  * The script will ask for the path to the TIFFs, - go back to the File Explorer and drag the TIFFs folder onto the Anaconda Prompt to copy the path. It should look something like `\\svm_dlib\Projects\...` - hit Enter
  * The script will now ask for the path where the PDFs should go - drag the PDFs folder onto the Anaconda Prompt to copy the path - hit Enter
  * The Anaconda Prompt terminal should start listing the TIFF files the script found and give you feedback as it creates each PDF. The process takes a while, so you can do something else while it runs, but check the progress to make sure there are no errors.
4. If you get any permission errors or "no TIFFS found" errors, let Dawn know.
