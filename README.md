# ble-scanner

This Node.js bluetooth low energy scanner scans for bluetooth advertisements and logs all "nRF5x Mesh Switch" advertisements.

It appears that Node version 10 has issues with bluetooth-hci-socket [[1](https://github.com/noble/node-bluetooth-hci-socket/issues/84), [2](https://github.com/noble/bleno/issues/440), [3](https://github.com/DigitalSecurity/btlejuice/issues/15)] so we downgraded our Node to version 8.10.0.

Noble requires bluetooth 4.0 to function, which may cause issues in Windows environments.
