# What is An IP camera?

An IP camera (Internet Protocol Camera) is a digital camera that transmits video data through a computer network using IP protocols

Unlike traditional USB webcam, IP camera is standalone network device with:
- their own CPU
- embedded firmware
- network interface
- web server
- streaming server

IP camera are commonly used in:
- Industrial system
- AI computer vision system
- Smart agriculture
- Edge AI deployment

# Basic Architecture

```text
IP Camera
    ↓
Router / Switch
    ↓
Linux PC / AI Server
    ↓
OpenCV / AI Model
```

# Main components inside an IP camera

An IP camera usually contains:

- Image sensor
- Embedded processor
- Video encoder
- Ethernet controller
- Firmware
- Web interface
- Streaming server

# Video Compression

IP cameras usually support:

- H.264
- H.265

Benefits:
- lower bandwidth
- lower storage usage
- stable streaming

# Common Streaming Protocol

## RTSP

Stand for Realtime Streaming Protocol

Most important protocol for AI applications

Used for:
- OpenCV
- FFmpeg
- VLC
- GStreamer
- YOLO
- InsightFace

Ex:
```text
rtsp://admin:password@192.168.1.100:554/Streaming/Channel/101
```

# Typical AI Pipeline

```text
IP Camera
    ↓ RTSP
OpenCV / FFmpeg
    ↓
AI Model
    ↓
Detection / Tracking / Recognition
```
