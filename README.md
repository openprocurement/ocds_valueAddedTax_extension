# Tax Included
The extension indicates whether the value tax was included.

## Overview
The field introduced by this extension is:
- `value/valueAddedTaxIncluded` - A Yes/No field to indicate whether the value 
tax was included. It should be boolean value.

## Examples
The following extract illustrates this property in use within the `tender/value` 
block.
```
{
    "tender": {
        "id": "SPA160032275",
        "value": {
          "currency": "GEL",
          "amount": 9800.0,
          "valueAddedTaxIncluded": true
        }
    },
}
```