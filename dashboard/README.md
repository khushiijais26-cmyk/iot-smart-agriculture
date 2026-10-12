## Topic and message format

Topic: `smart-agriculture/readings`

Publish one JSON message containing both measurements:

```json
{
  "soil_moisture": 42,
  "water_level_cm": 8.5,
  "timestamp": "2026-10-12T12:00:00Z"
}

```
soil_moisture: percentage from 0 to 100
water_level_cm: measured distance in centimeters
timestamp: ISO 8601 timestamp in UTC
