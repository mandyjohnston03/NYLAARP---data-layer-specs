# SS Wait Milestone Reached
Send this event every 5 seconds that the user has been waiting

## JavaScript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  	"event": "User Interaction", 
	"action": "SS Wait Milestone Reached",
	"waitDetail"{
    		"incrementSeconds": 5, 
    		"totalSeconds”: 15,
    		"maximumWaitTime”: 240 
		}
});
```


## Variable Definitions
| Path     | Definition | Possible Values | Data Type |
|----------|----------|----------|----------|
| waitDetail.incrementSeconds  | This should represent the increment that this event is sent | 5 | Intejer | 
| waitDetail.totalSeconds | This should represent the total seconds that the user has waited | 5/10/15 etc. | Integer | 						
| waitDetail.maximumWaitTime | This should represent the total possible seconds that the wait time will last before it would time out | 240 for a 4 minute wait cap | Integer | 
