# Organization classification

Adds an array of classification objects to an organization's details, in order to categorize it.

## Legal context

In the European Union, this extension's fields correspond to [eForms BT-10 (Activity Authority)](https://docs.ted.europa.eu/eforms/latest/reference/business-terms/). For correspondences to Tenders Electronic Daily (TED), see [OCDS for the European Union](http://standard.open-contracting.org/profiles/eu/latest/en/).

## Examples

```json
{
  "parties": [
    {
      "id": "1",
      "details": {
        "classifications": [
          {
            "id": "10",
            "scheme": "TED_CA_ACTIVITY",
            "description": "Social protection"
          }
        ]
      }
    }
  ]
}
```

## Issues

Report issues for this extension in the [ocds-extensions repository](https://github.com/open-contracting/ocds-extensions/issues), putting the extension's name in the issue's title.

## Changelog

### 2020-04-24

* Add `minProperties`, `minItems` and/or `minLength` properties.

This extension was originally discussed as part of the [OCDS for EU profile](https://github.com/open-contracting-extensions/european-union/issues), in [pull requests](https://github.com/open-contracting-extensions/ocds_organizationClassification_extension/pulls?q=is%3Apr+is%3Aclosed) and in <https://github.com/open-contracting/standard/issues/711>.
