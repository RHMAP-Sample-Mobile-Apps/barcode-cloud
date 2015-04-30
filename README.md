# Barcode Lookup

This service looks up a barcode by UPC id. It connects with a SOAP service, takes a mixed SOAP and CSV response, and returns JSON back to the client, more effectively mobilising the service.

# Group Hello World API

# hello [/hello]

'Barcode Lookup' endpoint.

## hello [POST] 

'Barcode lookup' endpoint.

+ Request (application/json)
    + Body
            {
              "barcode": "9780201896831"
            }

+ Response 200 (application/json)
    + Body
            [
              "Some product data goes here"
            ]
