
# Folder Parsers

A collection of simple Python scripts for extracting file names, formatting lists, and parsing biological pathway data.

## Scripts

### parser.py
Reads a specified folder and prints the names of all PDF and TXT files without their extensions.

### reader.py
Takes a multiline list of file names and converts it into a comma-separated, quoted Python list format.

### KEGG-Reader.py
Uses Biopython to read KEGG pathway files (KGML), extract gene information, remove duplicates, and print the resulting gene names.

## Requirements

- Python 3
- Biopython (for KEGG-Reader.py)

Install Biopython using:

pip install biopython

## Usage

1. Clone the repository:

   git clone https://github.com/VivanNyati/Folder_Parsers.git

2. Navigate to the repository:

   cd Folder_Parsers

3. Edit the desired script:

   - parser.py: Enter the folder path in folder_reader().
   - reader.py: Paste file names into the folder_chunk variable.
   - KEGG-Reader.py: Call reader(path, clock_name) with a KGML file path and a label.

4. Run the script:

   python parser.py

   or

   python reader.py

Note: KEGG-Reader.py defines a function and must be called with the appropriate arguments to produce output.

## Author

Vivan Nyati
