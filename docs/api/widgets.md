Foloving API calls will give you basic information all senzors connected to SimpleHome server.

***

### Flip the Switch

`POST: example.com/api/widgets/{widgetId}/run`

**Authentication Reguired: YES**

**Example Response:**
```json
{
  "value": true
}
```
### Get Device Detail Data

`GET: example.com/api/widgets/{widgetId}/detail`

**Authentication Reguired: YES**

**Example Response:**
```json
{
  "records": [
    {
      "record_id": 0,
      "subdevice_id": 11,
      "value": 1,
      "time": "2020-07-21 16:23:44",
      "execuded": 1
    },
    {
      "record_id": 0,
      "subdevice_id": 11,
      "value": 0,
      "time": "2020-07-20 18:12:39",
      "execuded": 1
    },
    {
      "record_id": 0,
      "subdevice_id": 11,
      "value": 1,
      "time": "2020-07-20 17:52:04",
      "execuded": 1
    },
    {
      "record_id": 0,
      "subdevice_id": 11,
      "value": 1,
      "time": "2020-07-20 16:02:50",
      "execuded": 1
    },
    {
      "record_id": 0,
      "subdevice_id": 11,
      "value": 0,
      "time": "2020-07-20 12:45:08",
      "execuded": 1
    }
  ],
  "comError": false,
  "lastConnectionTime": "1 day ago"
}
```
