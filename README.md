# Discord Last Meadow Online (As basic as it is gets)
Auto Clicks Adventure.
```js
var BTN1=document.querySelector('div.gameActions__8e80e div.activityButton__8af73>div[role="button"]');
setInterval(()=>BTN1.click(),50); // 50-100 sweet spot from rate-limits (50 may 429 randomly once or twice)
```

## extras (achievenments)
Auto Clicks the Dragon. for an achievenment
```js
var BTNDRGN=document.querySelector('div.dragonContainer__8e80e div.dragonClickable__8e80e[role="button"]');
setInterval(()=>BTNDRGN.click(),50);
```
