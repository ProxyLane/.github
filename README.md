# ProxyLane organization profile

`profile/README.md` is the page shown on https://github.com/ProxyLane. Images in `profile/assets/` are rendered from the HTML in `src/` with headless Chrome at 2x:

```sh
chrome --headless=new --hide-scrollbars --force-device-scale-factor=2 --window-size=1280,560 --screenshot=profile/assets/banner.png "file://$PWD/src/banner.html"
chrome --headless=new --hide-scrollbars --force-device-scale-factor=2 --window-size=1280,520 --screenshot=profile/assets/ladder.png "file://$PWD/src/ladder.html"
```
