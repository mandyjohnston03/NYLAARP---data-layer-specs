# SS Result Displayed


## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "User Interaction",
  "action”: "SS Result”
  "result": {
    "message": "Approved",
    "type": "1"
}
});
```


##Dynamic Variable Definitions
| Path     | Definition | Possible Values | Data Type |
|----------|----------|----------|----------|
| result.message  | This value for now will either be "Approved" or "Pending" - this will reflect the type of message you recieve | Approved/Pending | String |
| result.type | This should be an empty string for now, but I added it as a placeholder for the future. The purpose is to add a coded value (like 1,2,3,4 etc.) to represent the actual status if the message is "Pending"  | |String |	
