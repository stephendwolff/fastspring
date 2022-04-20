# fastspring

This is a simple Python module designed to interact with the FastSpring ordering
and subscription API. This module requires [xmltodict][1] to work. Data is
passed into and returned from the API object in dicts.

## Methods

Each method of the API class corresponds directly to an API endpoint. The
[official FastSpring API documentation][2] is the best reference for
understanding what does what. More explicit documentation will be forthcoming
here in the future.

[1]: https://github.com/martinblech/xmltodict/
[2]: https://github.com/fastspring/fastspring-api/