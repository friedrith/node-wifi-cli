# node-wifi-cli
A command line interface for node-wifi.

This library is a wrapper around [node-wifi](https://github.com/friedrith/node-wifi).

## Getting started

```bash
npm install node-wifi-cli -g

node-wifi-cli --scan 

node-wifi-cli --connect --ssid <ssid> --password <password> [--iface <wlan0>] 

node-wifi-cli --disconnect

node-wifi-cli --current 

# You can also use npx 

npx node-wifi-cli --scan


```


## Contribute

Please read [development guidelines](./CONTRIBUTING.md) before proposing a pull request.