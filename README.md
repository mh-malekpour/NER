# Pre-process and NER Arabic Text

Pre-process arabic text (remove diacritics, punctuations, and repeating characters) and Extract named-entity.

## Installation

- Install dependencies from <https://polyglot.readthedocs.io/en/latest/Installation.html>
- Download Necessary Models:

```bash
polyglot download embeddings2.ar ner2.ar
```

## Usage

```bash
python NERArabic.py [-h] -i INFILE -o OUTFILE
```

optional arguments:
  -h, --help            show this help message and exit
  -i INFILE, --infile INFILE
                        input file.
  -o OUTFILE, --outfile OUTFILE
                        out file.

## Example

```bash
python NERArabic.py -i infile.txt -o outfile.txt
```
