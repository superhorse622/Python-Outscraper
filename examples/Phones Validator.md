# Phone Numbers Enricher/Validator With Python

Returns phones carrier data (name/type), validates phones, ensures messages deliverability via [Outscraper API](https://app.outscraper.com/api-docs#tag/Phones/paths/~1phones-enricher/get).

## Installation

Python 3+
```bash
pip install outscraper
```

[Link to the Python package page](https://pypi.org/project/outscraper/)

## Initialization
```python
from outscraper import ApiClient

client = ApiClient(api_key='SECRET_API_KEY')
```
[Link to the profile page to create the API key](https://app.outscraper.com/profile)

## Usage

```python
# Get information about the phone number:
results = client.phones_enricher(['12812368208'])
```
