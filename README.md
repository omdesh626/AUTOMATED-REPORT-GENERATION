# AUTOMATED-REPORT-GENERATION

COMPANY:CODTECH IT SOLUTIONS

NAME:om suresh deshmukh

INTERN ID:CT08KWT

DOMAIN:PYTHON PROGRAMMING

DURATION:4 WEEKS

MENTOR:NELLA SANTOSH

**Data Analysis Report Generator**

This project is a Jupyter Notebook script that generates a PDF report analyzing data from a CSV file. It leverages the FPDF library for creating the PDF and the csv module to process and summarize the data.

Features
Reads data from a CSV file and calculates the total number of records.
Identifies and lists unique values for each column in the CSV file.
Creates a professional PDF report summarizing the analysis.
Automatically includes page numbering in the PDF footer.

How It Works:
Input:
The script reads a CSV file named data.csv. Ensure the file is in the same directory as the notebook.

Processing:
Uses Python's csv.DictReader to read and process the data.
Calculates the total number of records (rows) in the file.
Extracts and lists unique values for each column in the CSV file.

Output:
A PDF report named report.pdf is generated, which contains:
Title: "Data Analysis Report".
Total Records: The count of rows in the dataset.
Unique Values: For each column, all unique entries are listed.
Page Number: Included at the bottom of the PDF.

PDF Structure:
Title: Centered at the top of the first page.
Content: Structured with clear headings and values, making it easy to read.
Footer: Automatically generated page numbers.

Libraries Used:
FPDF: For creating and formatting the PDF.
csv: For reading and analyzing the CSV data.

*How to Run*
Prerequisites:
Python 3.x installed on your system.
Install the required library using pip:

pip install fpdf

*Steps to Execute:*

Open the Jupyter Notebook (Data_Analysis_Report.ipynb) in your preferred environment (e.g., Jupyter Notebook, JupyterLab, or VS Code).
Ensure the data.csv file is present in the same directory as the notebook.
Run all the cells in the notebook.
After execution, the file report.pdf will be generated in the same directory.

*How Others Can Use It*
Clone or download the repository containing the notebook.
Replace the data.csv file with your own CSV file for analysis.
Execute the notebook as described above to generate a custom report.
Share the PDF report with others as needed.

*Use Case*
This project is ideal for generating quick summaries of datasets in PDF format. It can be used for:

Business data analysis.
Academic research.
Summarizing tabular data for presentations.

*OUTPUT*:
