# Accommodation Booking Started

### 

## Javascript Code
```js
window.appEventData00000 = window.appEventData00000 || [];;;
appEventData00000.push({
  "event": "Accommodation Booking Started",
    "booking": {
        "roomList": [
            {
                "location": {
                    "locationId": "<locationId>"
                },
                "room": {
                    "numAdults": <numAdults>,
                    "numKids": <numKids>,
                    "numberInMultiRoomReservation": <numberInMultiRoomReservation>,
                    "stayDate": "<stayDate>"
                }
            }
        ],
        "total": {
            "currency": "<currency>"
        }
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|currency|string|Currency of the payment for the booking. ISO 4217 \(3 character alpha\), uppercase |USD, CAD, GBP, CHF|^[A-Z]{3}$|3|3||||
|locationId|string|Unique Identifier of a Location. |155, 65588, 987764448|||||||
|numAdults|integer|Integer number of adults for the booking.|1, 2, 3, 4, 5||||1|||
|numKids|integer|Integer number of kids for the booking.|1, 2, 3, 4, 5||||0|||
|numberInMultiRoomReservation|integer|Integer position of a room in a multi-room booking action.|1, 2, 3||||1|||
|stayDate|string|Date of each room night. ISO 8601 form \(YYYY-MM-DD\). Jan 1, 2019 is 2019-01-01|2001-12-22, 2011-01-01|^([0-9]{4})-(1[0-2]|0[1-9])-(3[01]|0[1-9]|[12][0-9])$||||||




