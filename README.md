# ENCORI-INT-retriever

INT-retriever automatizes the retrieval of miRNA–mRNA, miRNA–lncRNA, and miRNA–circRNA interactions from the ENCORI database through its web interface, displaying real-time progress indicators.

The tool is implemented in Python and can be executed either from the Windows IDLE environment or directly from the Python shell.

🔧 Usage instructions

**1)** Select the appropriate script:

-Use INT-retriever-win.py for Windows IDLE.

-Use INT-retriever.py for other environments.

**2)** Prepare your parameters and input file:
- Choose the genome by editing the field next to "assembly", for example "mm10" (or "hg38" for human).
-Choose the type of interaction by editing the field next to "geneType", for example "mRNA" (other valid options are "lncRNA" and "circRNA").
- Edit the miR.txt path field in the script to match your directory.
- Create a tab-separated file named miR.txt containing your list of miRNAs in full species-specific format (e.g., hsa-miR-185-5p, mmu-miR-185-5p).
- Include one miRNA per line, without a header.

**3)** Set the output directory:

Modify the output file path in the script (default: raw_int_ENCORI.txt) to match your preferred folder.

**4)** Install dependencies:
- Ensure the requests package is installed:
**Other:** pip install requests
**Windows IDLE:**
  import os
os.system("pip install requests")
**5)** Run the script


