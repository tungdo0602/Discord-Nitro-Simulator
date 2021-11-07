# UPDATE!!!!
# WORKED AGAIN THANKS @steinhorror FOR THE Template CODE (his github: https://github.com/steinhorror), and also can use animated emoji correctly (maybe)
# Discord Nitro Simulator
#### Client side discord nitro

# How To Use:
#### 1. open Developer tools by press f12 or press Ctrl + Shift + I
#### 2. paste this code to the console tab and press enter!
```javascript
window.webpackChunkdiscord_app.push([[Math.random()], {}, (req) => {for (const m of Object.keys(req.c).map((x) => req.c[x].exports).filter((x) => x)) {if (m.default && m.default.getCurrentUser !== undefined) {return m.default.getCurrentUser().premiumType = 2;}if (m.getCurrentUser !== undefined) {return m.getCurrentUser().premiumType = 2}}}]);
window.webpackChunkdiscord_app.push([[Math.random()], {}, (req) => {for (const m of Object.keys(req.c).map((x) => req.c[x].exports).filter((x) => x)) {if (m.default && m.default.canUseAnimatedEmojis !== void 0) {return m.default.canUseAnimatedEmojis("" + true) + true;}if (m.canUseAnimatedEmojis !== void 0) {return m.canUseAnimatedEmojis("" + true) + true}}}]);
```
