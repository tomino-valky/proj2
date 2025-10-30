**DNA Sequence Analyzer**
This is a simple command-line Python script that takes a DNA sequence as input and calculates basic characteristics.

+**Features**
</n>
The script performs the following tasks:

+**RNA Transcription:** Converts the DNA sequence into its corresponding RNA sequence by replacing all occurrences of Thymine (T) with Uracil (U).

+**Sequence Length:** Calculates the total length of the entire input string.

+**GC Content:** Calculates the GC content as a decimal ratio.

Note: This calculation is based only on the counts of A, T, G, and C. Any other characters in the sequence (like 'N' or spaces) are ignored in the GC calculation but are <ins>included</ins> in the total sequence length.

Requirements
Python 3.x

No external libraries are required.

**How to Use:**
</n>
Save the script as a .py file (e.g., dna_analyzer.py).

Run the script from your terminal:

python dna_analyzer.py
The script will prompt you to enter a sequence. Paste or type your sequence and press Enter.

An example of the script interaction, matching the code's exact output:

Hello, please enter your sequence below: 
```
ATTGCTAGGCAAT
```
Expected output:
```
 your sequence: ATTGCTAGGCAAT
 your RNA sequence: AUUGCUAGGCAAU
 your sequence length: 13
 your GC: 0.38
```
