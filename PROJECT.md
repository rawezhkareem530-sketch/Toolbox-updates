# ToolBox POS — handoff note

- App = one file: ToolBox.html (folder: Desktop\ToolBox). Build id in `<meta name="tb-build">` (UTC yyyymmddhhmm).
- Online updates: GitHub repo rawezhkareem530-sketch/Toolbox-updates, latest.json signed with ECDSA (public key UPD_PUB in the app). The private signing key is NOT in this folder.

## 2026-11-22 (build 202611221830)
- Phone version number: the computer writes its app version into settings.appVer (synced); Settings › About shows settings.appVer on phones too.
- Product (and other #q) search: keepTyping() in renderNow keeps the same input element while typing, so the phone keyboard stays open. q.oninput instead of addEventListener.
- Change dialog: USD quick notes no longer cut to 3, so $100 shows too.
- Not tested yet (user tests on request).
