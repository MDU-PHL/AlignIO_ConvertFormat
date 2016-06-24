# AlignIO_ConvertFormat.py
Convert DNA alignments between BioPython-supported formats.
## Example usage:

```bash
python AlignIO_ConvertFormat.py -a *_AA.fasta -l A -o nexus -h
usage: AlignIO_ConvertFormat.py [-h] -a ALIGNMENT [ALIGNMENT ...]
                                [-i INFORMAT] [-l LETTER_ALPHABET]
                                [-o OUTFORMAT]

Convert DNA alignments between BioPython-supported formats. Handles many input
alignments (with e.g., *.fasta).

optional arguments:
  -h, --help            show this help message and exit
  -a ALIGNMENT [ALIGNMENT ...], --alignment ALIGNMENT [ALIGNMENT ...]
                        Input alignment(s)
  -i INFORMAT, --informat INFORMAT
                        Alignment input format (default fasta)
  -l LETTER_ALPHABET, --letter_alphabet LETTER_ALPHABET
                        Use A for Amino Acids, D for DNA
  -o OUTFORMAT, --outformat OUTFORMAT
                        Alignment output format (default fasta)
```
