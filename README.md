# TNFD Trend Analysis (2023-2025)
*A Research Data Analyst Project under [Professor Zoey Yiyuan Zhou](https://scholar.google.com/citations?user=WO978u4AAAAJ&hl=en).*

This Python-based project analyzes the emerging trends in Task Force Nature-related Financial Disclosures (TNFD) reports from year 2023 to 2025 through text mining and vizualisation. The workflow of this project consists of:
1. Preprocessing: Converting PDF reports to TXT format
2. Analysis: Generating word clouds to identify trend

## Workflow
### Phase 1: Preprocessing (PDF to TxT)
- Input: TNFD (or similar type) reports manually downloaded from [TNFD Global Website](https://tnfd.global/knowledge-hub/example-tnfd-reporting/).
- Tool: [convert_txt.ipynb](https://github.com/nichosimanjuntak/Analyzing-TNFD-Trend/blob/main/convert_txt.ipynb)
*Raw code was provided by Prof. Zoey, then modified to make it align with the website's PDF and desired TxT 
- Output: [Database Folder](https://drive.google.com/file/d/1AsY9r6aolIHtvmYe54aZPCx8qq2mJ0HV/view?usp=share_link) consist of all raw PDFs and converted TXTs and [PDFandTXT.xlsx](https://github.com/nichosimanjuntak/Analyzing-TNFD-Trend/blob/main/PDFandTXT.xlsx) report for successful conversion
  - Converted TXTs (marked "1")
  - Unconvertible PDFs (marked "0")

### Phase 2: Trend Analysis (Generating Word Cloud)
- Tool: [wordcloud.ipynb](https://github.com/nichosimanjuntak/Analyzing-TNFD-Trend/blob/main/wordcloud.ipynb) processes all TXT files
  1. Clean text: remove stopwords, punctuations, and short words
  2. Extraction: Count word frequency
  3. Vizualisation: Generate word clouds where font size reflects word frequency

## Output
#### Top terms like "climate", "sustainability", "management" reflect 2023-2025 TNFD focus areas.
<img src="https://github.com/nichosimanjuntak/Analyzing-TNFD-Trend/blob/main/Output.png">


*The resulting image may be differ every run but the reflected word will be more or less the same.*

## Acknowledgments
- Professor Zoey for guidance, instruction, assistance
- All reports are online available at TNFD global websites

