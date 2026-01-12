# Post a Composition (Vital Signs)

## Endpoint
POST /ehrbase/rest/openehr/v1/ehr/{ehr_id}/composition

## Query params used
- templateId=vital_sign.v0
- format=FLAT

## Headers
- Content-Type: application/json
- Accept: application/json

## Body
Used the FLAT JSON in:
04_compositions/vital_signs_flat.json

## Result
HTTP 204 No Content (success)
