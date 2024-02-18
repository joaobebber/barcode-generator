# Barcode Generator

## Description

This project uses:

- Python: 3.11.3
- Flask: 3.0.2

## How to run

First, we need to create a virtual environment (.venv/):

```bash
  python3 -m venv .venv
```

Also, we need to install all dependencies listed in <requirements.txt>:

```bash
  pip3 install -r requirements.txt
```

To initialize the server, after configuration, we only need to execute:

```bash
  python3 run.py
```

### Where are my generated barcodes?

All barcodes generated via HTTP requests are stored in <public/assets/barcodes/>

### Dependencies

- Cerberus: 1.3.5
- Flask: 3.0.2
- pillow: 10.2.0
- pre-commit: 3.6.1
- pylint: 3.0.3
- pytest: 8.0.1
- python-barcode: 0.15.1
- virtualenv: 20.25.0
