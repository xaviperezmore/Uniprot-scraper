# Uniprot-scraper

## Installation requirements

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the requests library.

```bash
pip install requests
```

## Explanation
Uniprot database has a REST API interface that allows us to access data in JSON format. Given the UniProt website for the desired protein,
the script retrieves the data from the interface, accesses the protein name, the organism and the OpenTargets identifiers and prints these values out to a file.

## Usage

To use the script, the following command must be executed. In the example, the argument is the example website from the test, but it can be used for another protein by entering the corresponding website as the argument in the same format.

```python


python Nuritas_uniprot_test_xavierperez.py https://www.uniprot.org/uniprot/P40925


```
