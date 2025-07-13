# Transmembrane_Voltage_Data_Analysis

This Google Colab notebook was developed during my 2025 summer research lab work to automate the processing and visualization of '.abf' (Axon Binary Format) files collected from biosensors. The tool reads multiple .abf files, extracts relevant signal data, generates plots, performs quick statistical analyses, and exports the results into a spreadsheet for further interpretation. 

Main features: 
- Automatically detects and loads relevant .abf files from a specified folder.
- Plots each trace contained within a file.
- Identifies x-intercepts relevant to the lab's research and calculates summary statistics.
- Saves processed outputs (graphs, values, and stats) to a '.xlsx' file in the same folder.

How to use: 
Open the notebook in Google Colab, specify the folder to be analysed from your personal Google Drive and run each cell sequentially.

Background: 
This project was created as part of a biophysics research lab, where sensor data needed to be processed efficiently to extract meaningful insights. 


