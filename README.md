# Discord Nitro Simulator
### Client side **Discord Nitro**
# How To Use:
#### 1. open Developer tools by press f12 or press Ctrl + Shift + I
#### 2. paste this code to the console tab and press enter!
```javascript
window.webpackChunkdiscord_app.push([[Math.random()], {}, (req) => {for (const m of Object.keys(req.c).map((x) => req.c[x].exports).filter((x) => x)) {if (m.default && m.default.getCurrentUser !== undefined) {return m.default.getCurrentUser().premiumType = 2;}}}]);
```
