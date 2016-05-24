# demos
All test demos for nw issues.

## srcDemo

Issue:
https://github.com/nwjs/nw.js/issues/4843

Temporary solution:
```
 use win.enterFullscreen() or win.enterKioskMode() instead of win.on("close", function() {}) to hide close button.
```

## crash_reports_by_http(s)_child_process.zip

Issue:
https://github.com/nwjs/nw.js/issues/4855

Temporary solution:
```
1. At least one network adapter(when no network adapter, could install virtual network adapter)
2. Enable the network adapter
3. Set DNS: 8.8.8.8(using static DNS to fix)
```

## ShortcutDemo.zip

Issue:
https://github.com/nwjs/nw.js/issues/4863

Temporary solution:
```
Two plans:
one. use jquery.hotkeys instead of nw.App.registerGlobalHotKey, but all pages to add jquery.hotkeys codes
two. use nw.App.(un)registerGlobalHotKey for every page
```
