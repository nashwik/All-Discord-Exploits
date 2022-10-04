# Gives you All Badges
```js
(() => {
  webpackChunkdiscord_app.push([[Math.random()], {}, req => {
    for (const m of Object.keys(req.c).map((x) => req.c[x].exports).filter(x => x)) {
      if (m.default && m.default.getCurrentUser !== undefined) {
        return m.default.getCurrentUser().flags = Object.values({ DISCORD_EMPLOYEE: 1 << 0, PARTNERED_SERVER_OWNER: 1 << 1, HYPESQUAD_EVENTS: 1 << 2, BUGHUNTER_LEVEL_1: 1 << 3, HOUSE_BRAVERY: 1 << 6, HOUSE_BRILLIANCE: 1 << 7, HOUSE_BALANCE: 1 << 8, EARLY_SUPPORTER: 1 << 9, BUGHUNTER_LEVEL_2: 1 << 14, EARLY_VERIFIED_BOT_DEVELOPER: 1 << 17, DISCORD_CERTIFIED_MODERATOR: 1 << 18 }).reduce((pre, cur) => pre + cur, 0);
      }
    }
  }]);
})();
```

# place your account under "quarantine"
```js
webpackChunkdiscord_app.push([[Math.random()],{},(req)=>{for(const m of Object.keys(req.c).map((x)=>req.c[x].exports).filter((x)=>x)){if(m.default&&m.default.getCurrentUser!==undefined){return m.default.getCurrentUser().flags=-1}}}]);
```

# Gives you Specified Badges
```js
const flags = { 
  DISCORD_EMPLOYEE: 1 << 0, 
  PARTNERED_SERVER_OWNER: 1 << 1, 
  HYPESQUAD_EVENTS: 1 << 2, 
  BUGHUNTER_LEVEL_1: 1 << 3, 
  HOUSE_BRAVERY: 1 << 6, 
  HOUSE_BRILLIANCE: 1 << 7, 
  HOUSE_BALANCE: 1 << 8, 
  EARLY_SUPPORTER: 1 << 9, 
  BUGHUNTER_LEVEL_2: 1 << 14, 
  EARLY_VERIFIED_BOT_DEVELOPER: 1 << 17, 
  DISCORD_CERTIFIED_MODERATOR: 1 << 18
};

function setBadge(badge) { window.webpackChunkdiscord_app.push([[Math.random()], {}, (req) => {for (const m of Object.keys(req.c).map((x) => req.c[x].exports).filter((x) => x)) {if (m.default && m.default.getCurrentUser !== undefined) {return m.default.getCurrentUser().flags = badge;}if (m.getCurrentUser !== undefined) {return m.getCurrentUser().flags = badge}}}]); }

function getBadge(badge) { window.webpackChunkdiscord_app.push([[Math.random()], {}, (req) => {for (const m of Object.keys(req.c).map((x) => req.c[x].exports).filter((x) => x)) {if (m.default && m.default.getCurrentUser !== undefined) {return m.default.getCurrentUser().flags += badge;}if (m.getCurrentUser !== undefined) {return m.getCurrentUser().flags += badge}}}]); }

function remBadge(badge) { window.webpackChunkdiscord_app.push([[Math.random()], {}, (req) => {for (const m of Object.keys(req.c).map((x) => req.c[x].exports).filter((x) => x)) {if (m.default && m.default.getCurrentUser !== undefined) {return m.default.getCurrentUser().flags -= badge;}if (m.getCurrentUser !== undefined) {return m.getCurrentUser().flags -= badge}}}]); }

function resBadge() { window.webpackChunkdiscord_app.push([[Math.random()], {}, (req) => {for (const m of Object.keys(req.c).map((x) => req.c[x].exports).filter((x) => x)) {if (m.default && m.default.getCurrentUser !== undefined) {return m.default.getCurrentUser().flags = 0;}if (m.getCurrentUser !== undefined) {return m.getCurrentUser().flags = 0}}}]); }

// exemple:
setBadge(flags.EARLY_SUPPORTER + flags.DISCORD_CERTIFIED_MODERATOR) // Set Discord Staff badge and Certified Moderator Badges
getBadge(flags.EARLY_SUPPORTER) // Add Discord Staff Badge
remBadge(flags.EARLY_SUPPORTER) // Remove Discord Staff Badge
resBadge() // Remove all badges
```

# Gives you the Bot tag
```js
var findModule=(item)=>window.webpackChunkdiscord_app.push([[Math.random()],{},(req)=>{for(const m of Object.keys(req.c).map((x)=>req.c[x].exports).filter((x)=>x)){if(m.default&&m.default[item]!==undefined)return m.default}}])
findModule('getCurrentUser').getCurrentUser().bot = true;
```

# Gives you the verified system tag
```js
var findModule=(item)=>window.webpackChunkdiscord_app.push([[Math.random()],{},(req)=>{for(const m of Object.keys(req.c).map((x)=>req.c[x].exports).filter((x)=>x)){if(m.default&&m.default[item]!==undefined)return m.default}}])
findModule('getCurrentUser').getCurrentUser().system = true;
```
## Change system tag
**does not work anymore**
```js
var findModule=(item)=>window.webpackChunkdiscord_app.push([[Math.random()],{},(req)=>{for(const m of Object.keys(req.c).map((x)=>req.c[x].exports).filter((x)=>x)){if(m.default&&m.default[item]!==undefined)return m.default}}])
findModule('Messages').Messages.SYSTEM_DM_TAG_SYSTEM = 'System Tag Name Here';
```