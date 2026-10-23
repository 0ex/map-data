**OSM to Google Place IDs**

A mapping of OSM places to Google places.

Grouped by country / city / eight-character Plus-code prefix (about 280 m bltiles).

## Example

File: [nl/amsterdam/9F469VFJ/id-map.json](nl/amsterdam/9F469VFJ/id-map.json)

Contents:

```json
{
  "n295378745": {
    "google_place_id": "ChIJ65_VXdAJxkcRMSIPupGG_eQ",
    "google_cid": "16500492570205299249",
    "confidence": 0.99
  }
}
```

## Schema

Each file is a JSON object keyed by OSM ID. Every value contains exactly:

- `google_place_id`: Google place ID, or `null`
- `google_cid`: decimal Google CID, or `null`
- `confidence`: JSON number from `0` through `1`
