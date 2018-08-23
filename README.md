# Camera-Access-Example
Camera access example with HTML5 on android, ios, desktop.

# Prerequisites

- [python2](https://www.python.org/downloads/)
- **server available to public access** or **local aera netowrk for all clients, server(wifi)**
- On linux, install openssl. On windows, install git(for gitbash) (Optionally)

# Setup

1) run `pip install -U Flask`
2) Downlaod all files to workspace
3) Run `openssl req -new -x509 -keyout server.pem -out server.pem -days 365 -nodes` to make a certificate. (Optionally)
4) Run python simple-https-server.py
5) run following codes in terminal
```
  set FLASK_APP=upload-server.py
  flask run --host=0.0.0.0
```
6) Browse https://[ip]:4443/camera.html 
7) Test and check terminal output

# Reference

- https://stackoverflow.com/questions/13198131/how-to-save-an-html5-canvas-as-an-image-on-a-server
- https://developers.google.com/web/fundamentals/media/capturing-images/?hl=ko
- https://gist.github.com/dergachev/7028596
