cinepass-pythonclient, a Python SDK for cinepass.de - by CLIQZ
=====================

![Cliqz logo](https://github.com/gabormay/cinepass-pythonclient/blob/img/cliqz250x88.png?raw=true)
> Cliqz, a German company owned by Mozilla and Hubert Burda Media, is a provider of innovative, privacy-focused browser technologies with integrated quick-search functionality and anti-tracking. Visit https://cliqz.com for more information.

This library can be used for access to
https://cinepass.de REST API via Python.
Detailed description of API you can find at https://api.cinepass.de/documentation.


Basic usage:

```python
    from cinepass import Client
    client = Client(api_key='<your api key>')
    client.movies.all()  # get list of all movies
    client.cinemas.all(location='52.50,13.37')  # get cinemas around location
    ...  # and so on
```

## Installation

## Tests

## Documentation
