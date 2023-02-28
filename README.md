# Uniprot-scraper

## Installation requirements

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the requests library.

```bash
pip install requests
```

## Explanation
Uniprot database has a REST API interface that allows us to access data in JSON format. Given an UniProt entry ID for the desired protein,
the script retrieves the data from the interface, accesses the protein name, the organism and the OpenTargets identifiers and prints these values out to a file.

## Usage

```python

# returns 'words'
foobar.pluralize('word')

# returns 'geese'
foobar.pluralize('goose')

# returns 'phenomenon'
foobar.singularize('phenomena')
```
