# BetterLogsDiscord
Get styled logs in terminal and in a discord channel with webhooks!
 
![image](https://user-images.githubusercontent.com/47084010/162233247-933af98b-c295-4bdb-b0a1-01e037972856.png)

## How to use
```js 
 var log = require('betterlogs-discord');

 log.silly("silly")
 
 log.verbose("verbose")
 
 log.info("info")
 
 log.data("data")
 
 log.help("help")
 
 log.warn("warn")
 
 log.debug("debug")
 
 log.server("server")
 
 log.error("error")
 ```
 
 Add this to your .ENV file
 ```json
"LOGURL": "WEBHOOKURL" 
```

## Planned Updates
- [ ] Make it where you can use it without webhook.
- [ ] Add more styles.
- [ ] Make `log()` a defualt style
- [ ] Add delight to the experience when all are complete :tada:


