# shot-timer

Web page for the **Special Pie M1A2+** shot timer over Web Bluetooth.

Open: https://dadada3000.github.io/shot-timer/

- iPhone: open the link in **Bluefy – Web BLE Browser**, or in Safari with the **WebBLE** extension enabled.
- Android / desktop: Chrome or Edge.

Shows shot times and splits live, keeps string history locally in the browser, exports CSV.
The Debug section logs raw BLE packets.

Protocol notes are from [jkesseler/sg-timer-led-display](https://github.com/jkesseler/sg-timer-led-display)
(service `FFF0`, notify `FFF1`, frames `F8 F9 … F9 F8`: `0x34` start, `0x36` shot, `0x18` stop).
