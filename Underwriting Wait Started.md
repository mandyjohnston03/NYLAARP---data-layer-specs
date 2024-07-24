# Underwriting Wait Started
Send this when the wait time starts

## JavaScript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
    "event”: "User Interaction”
  	"action”: "Underwriting Wait Started”
    "waitDetail"{
    		"maximumWaitTime”: 240 
		}
});
```
