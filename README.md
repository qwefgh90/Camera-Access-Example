# Camera-Access-Example
Camera access example with HTML5 on android, ios, desktop.

# Prerequisites

- [python2](https://www.python.org/downloads/)
- **server available to public access** or **local aera netowrk for all clients, server(wifi)**
- On linux, install openssl. On windows, install git(for gitbash)

# Setup

1) Downlaod all files to workspace.
2) Run `openssl req -new -x509 -keyout server.pem -out server.pem -days 365 -nodes` to make a certificate.
3) Run python simple-https-server.py
4) Browse https://[ip]:4443/camera.html 
