# Picamera h264 Web Streaming
Demo of h264 live streaming from Raspberry Pi using Python and Broadway.js.

## Motivation

[Broadway.js](https://github.com/mbebenita/Broadway) is an amazing JavaScript h264 decoder which can decode raw h264 produced by [PiCamera](https://github.com/waveform80/picamera). This allows 1280 x 720 real time (~ 100ms latency) streaming to a web browser even from Raspberry Pi Zero!

## Usage

1. Clone this repository

```
git clone https://github.com/Onixaz/picamera-h264-web-streaming.git
cd picamera-h264-web-streaming
```

2. Create Python3 virtual enviroment (optional)

```
python3 -m venv venv
source venv/bin/activate
```

3. Install dependencies

```
pip install picamera, ws4py
```

4. Launch the server

```
python server.py
```
5. Navigate to http://your-raspberrypi-ip:8082 on your PC/smartphone and the stream should appear.

Tested with Chrome and Firefox on Windows 10 and Chrome for Android (Nokia 6.1) 

## Based on

* https://github.com/waveform80/pistreaming
* https://github.com/Dregu/visio



