# OpenVPN Proxy

How to connect your browser to a VPN through proxy

Forked from https://github.com/jonohill/docker-openvpn-proxy

## Usage

1. Clone the repo
1. Move your `.opvn` file here
1. Create a `.env` file with following
```
OPENVPN_FILE=OVPN_FILE.ovpn
OPENVPN_USERNAME=YOUR_USERNAME
OPENVPN_PASSWORD=YOUR_PASSWORD
```
4. Build and Run
```
$ docker-compose build
$ docker-compose up -d
```
5. Install any extension that allows proxy in your browser, i.e. [SwitchyOmega](https://github.com/FelisCatus/SwitchyOmega).
1. Point the proxy to `localhost:8081`, and you're up and running.

