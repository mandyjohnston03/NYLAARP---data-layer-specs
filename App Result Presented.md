# App Result Presented


## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "User Interaction",
  "action”: "App Result Presented”
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
| result.type | This should represent a coded value associated with the actual underwriting status if the message is "Pending"  | |String |	
