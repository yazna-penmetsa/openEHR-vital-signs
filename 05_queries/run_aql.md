# Run AQL Queries in Postman

## Endpoint
POST http://localhost:8080/ehrbase/rest/openehr/v1/query/aql

## Headers
- Content-Type: application/json
- Accept: application/json

## Example query
Used queries from:
- 05_queries/list_compositions.aql
- 05_queries/vital_signs_query.aql

## Result
Returned composition IDs and extracted vital signs (pulse and BP).
