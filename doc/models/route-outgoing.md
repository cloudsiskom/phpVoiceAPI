
# Route Outgoing

## Structure

`RouteOutgoing`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `response` | `bool` | Required | - | getResponse(): bool | setResponse(bool response): void |
| `device` | `string` | Required | - | getDevice(): string | setDevice(string device): void |
| `routeTo` | `string` | Required | - | getRouteTo(): string | setRouteTo(string routeTo): void |
| `routeDetail` | `string` | Required | - | getRouteDetail(): string | setRouteDetail(string routeDetail): void |

## Example (as JSON)

```json
{
  "response": true,
  "device": "8210000000001",
  "route_to": "RANDOM",
  "route_detail": "RDM1"
}
```

