# Discord Nitro Simulator
### Client side **Discord Nitro**
# **Credit:** steinhorror for the webpack fix part (https://github.com/steinhorror)

# How To Use:
#### 1. open Developer tools by press f12 or press Ctrl + Shift + I
#### 2. paste this code to the console tab and press enter!
```javascript
window.webpackChunkdiscord_app.push([[Math.random()], {}, (req) => {for (const m of Object.keys(req.c).map((x) => req.c[x].exports).filter((x) => x)) {if (m.default && m.default.getCurrentUser !== undefined) {return m.default.getCurrentUser().premiumType = 2;}if (m.getCurrentUser !== undefined) {return m.getCurrentUser().premiumType = 2;}}}]);console.clear();console.log(`%cNitro Perk Has Successfully enabled on your client!`, "font-size: 32px; color: #00ffff")
```
