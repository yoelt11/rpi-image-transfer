# rpi-image-transfer
Transfer Images from rpi camera to pc via a websocket connection.

### Instructions:
1) Place and run the client.py in raspeberry pi
```
python3 client.py HOST
```
where HOST is e.g: 10.0.0.1

2) Run the server in pc
```
python3 server.py HOST
```
where HOST is e.g: 10.0.0.1

Note:
The port is 6000 by default.

