# Stop Discord stop Spotify
```js
XMLHttpRequest.prototype.realOpen = XMLHttpRequest.prototype.open;
function myOpen(method, url, async, user, password) {
  if (url == "https://api.spotify.com/v1/me/player/pause" && method == "PUT") url = "127.0.0.1";
  this.realOpen(method, url, async, user, password);
}
XMLHttpRequest.prototype.open = myOpen;
```
