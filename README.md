# XRD Data Extraction from .ras Files

During my research on thin films, I performed X-ray diffraction (XRD) analysis and received data in `.ras` files. To analyze this data in Origin, I needed to extract the `2theta` and `intensity` values. To streamline this process, I created a Jupyter notebook for easy extraction of the required data into a new Excel file.

## Features

- Upload `.ras` files directly in the notebook
- Extract data starting from the 345th row
- Save the extracted data into new Excel files with columns named `2theta` and `intensity`

## Requirements

- Python 3.x
- pandas
- openpyxl
- Google Colab (for running the notebook)

## Usage
## Open the Notebook in Google Colab

Click the button below to open the notebook in Google Colab.

!Open In Colab

## Upload and Process Files

1. Run the notebook cells to upload your `.ras` files.
2. The notebook will process each file and save the results as separate Excel files.

