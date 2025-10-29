# Transmembrane_Voltage_Data_Analysis

This Google Colab notebook was developed during my 2025 summer research lab work to automate the processing and visualization of '.abf' (Axon Binary Format) files collected from biosensors. The tool efficiently reads multiple .abf files, extracts signal data, generates plots, performs statistical analyses, and exports the results into a spreadsheet for further interpretation. 

--- 

## Main features: 
- Automatic file detection: Loads all relevant .abf files from a specified folder.
- Trace plotting: Visualizes each trace contained within a files.
- Data analysis: Identifies x-intercepts relevant to the lab's research and calculates summary statistics.
- Exports results: Saves processed graphs, values, and statistics to an '.xlsx' file in the same folder.

## How to use: 
1. Open the notebook in Google Colab
2. Specify the folder to be analysed from your Google Drive containing the `.abf` files
3. Run each cell sequentially. 
Note: Any incompatible or unreadable files will be marked by 'NaN' values in all fields of the resulting '.xlsx' file.

## Background: 
This project was created as part of a biophysics research lab workflow. By automating the processing of multiple `.abf` files, it significantly reduced manual labor and saves time, allowing student researchers to quickly extract meaningful insights from experimental data.


