# URLMetaExtractor

This project is an API that takes a URL as input and returns its metadata in the response.

## Installation

Clone the repository:

```
git clone https://github.com/juniorvish/URLMetaExtractor.git
```

Navigate to the project directory:

```
cd URLMetaExtractor
```

Install the required dependencies:

```
pip install -r requirements.txt
```

## Usage

Run the application:

```
python app.py
```

Send a POST request to the API with the URL as a parameter in the request body:

```json
{
  "url": "https://example.com"
}
```

The API will return the metadata in the response body:

```json
{
  "url": "https://example.com",
  "metadata": {
    "title": "Example Domain",
    "description": "This domain is for use in illustrative examples in documents.",
    "image": "https://example.com/favicon.ico"
  }
}
```