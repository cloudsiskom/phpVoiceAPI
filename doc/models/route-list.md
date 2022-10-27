
# Route List

## Structure

`RouteList`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `response` | `bool` | Required | - | getResponse(): bool | setResponse(bool response): void |
| `incomingRoute` | [`IncomingRoute[]`](../../doc/models/incoming-route.md) | Required | - | getIncomingRoute(): array | setIncomingRoute(array incomingRoute): void |
| `outgoingRoute` | [`OutgoingRoute[]`](../../doc/models/outgoing-route.md) | Required | - | getOutgoingRoute(): array | setOutgoingRoute(array outgoingRoute): void |

## Example (as JSON)

```json
{
  "response": true,
  "incoming_route": [
    {
      "id": 57,
      "transaction_id": null,
      "customer_code": "GOJEK",
      "did": "6285757920462",
      "destination": "DTMFTEST",
      "destination_detail": null,
      "create_date": "2022-08-23T22:57:32.000Z",
      "isActive": 1
    },
    {
      "id": 65,
      "transaction_id": null,
      "customer_code": "GOJEK",
      "did": "6285592055238",
      "destination": "CVAI",
      "destination_detail": "BANK_BKKN",
      "create_date": "2022-09-01T17:00:23.000Z",
      "isActive": 1
    },
    {
      "id": 69,
      "transaction_id": null,
      "customer_code": "GOJEK",
      "did": "02150995134",
      "destination": "IVR",
      "destination_detail": "TOKO_BUAH",
      "create_date": "2022-09-14T02:37:27.000Z",
      "isActive": 1
    },
    {
      "id": 72,
      "transaction_id": null,
      "customer_code": "GOJEK",
      "did": "6285757920463",
      "destination": "TRUNK",
      "destination_detail": "CVAI",
      "create_date": "2022-09-16T03:45:38.000Z",
      "isActive": 1
    }
  ],
  "outgoing_route": [
    {
      "id": 582,
      "customer_code": "GOJEK",
      "extension": "ALL",
      "route_to": "PROVIDER",
      "route_detail": "6285592055236",
      "tech_prefix": "",
      "create_date": "2022-09-14T19:40:24.000Z",
      "isActive": 1
    },
    {
      "id": 583,
      "customer_code": "GOJEK",
      "extension": "8210000000001",
      "route_to": "RANDOM",
      "route_detail": "RDM1",
      "tech_prefix": "198767",
      "create_date": "2022-09-16T03:45:44.000Z",
      "isActive": 1
    }
  ]
}
```

