# Login Type


## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Page Data",
  "user": {
    "loginType": "Approved"
}
});
```


## Dynamic Variable Definitions
| Path     | Definition | Possible Values | Data Type |
|----------|----------|----------|----------|
| user.loginType  | The purpose of this value is to identify users logging in through CSW Lite | Regular/Lite | String |
