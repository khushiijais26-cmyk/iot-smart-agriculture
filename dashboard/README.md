## Topic and message format

Topic: `smart-agriculture/readings`

Publish one JSON message containing both measurements:

```json
{
  "soil_moisture": 42,
  "water_level_cm": 8.5,
  "timestamp": "2026-10-12T12:00:00Z"
}

soil_moisture is a percentage from 0 to 100.
water_level_cm is the measured distance in centimeters.
timestamp is an ISO 8601 UTC timestamp
