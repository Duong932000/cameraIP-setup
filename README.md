# cameraIP-setup — Camera IP Knowledge and Setting Up

A practical engineering knowledge base for understanding, configuringm and integrating IP cameras with Linux, OpenCV, RTSP streaming, and AI computer vision system.

This repo focuses on:

- IP camera fundamentals
- RTSP streaming
- Hikvision camera setup
- Linux streaming pipelines
- OpenCV integration
- AI realtime inference
- Low latency optimization
- Edge AI deployment

The goal is to build reusable infrastructure knowledge for:
- Multi-camera AI system
- Edge AI deployments


# Repo Structure

## docs/

Technical knowledge and engineering notes:

### fundamentals/
Core concepts behind IP camera system

Topics:
- What is an IP camera
- RTSP protocol
- ONVIF
- PoE
- H264 vs H265
- Mainstram and Substream
- Buffer and latency

### hikvision/
Hikvision-specific setup and optimization

Topics:
- Initial camera setup
- RTSP configuration
- WebUI usage
- AI optimized settings
- Troubleshooting

### linux/
Linux streaming and video pipeline

Topics:
- VLC
- FFmpeg
- OpenCV VideoCapture
- GStreamer
- RTSP debugging

### networking/
Networking fundamentals for IP cameras

Topics:
- Static IP
- DHCP
- Router and switch
- VLAN
- Remote access

### ai_integration/
AI and computer vision integration

Topics:
- InsightFace + RTSP
- YOLO + RTSP
- Multi-camera pipeline
- Low latency inference
- Edge AI architecture

### deployment/
Procduction deployment notes

Topics:
- Docker
- systemd services
- GPU acceleration
- Production deployment


# scripts/
Reusable Python and shell scripts.

Examples:
- RTSP test
- Multi-camera test
- Recording
- Snapshot capture
- Network scanning


# configs/
Example configurations for:
- RTSP
- Hikvision
- Multi-camera systems


# assets/

Repository assets:
- diagrams
- screenshots
- gifs


# Current Hardware

## IP Camera
- Hikvision DS-2CD2046G2H-I2U/S(L)(RB)

## Operating System
- Linux Fedora/Ubuntu

## AI Framework
- OpenCV
- InsightFace
- YOLO

# Author

```text
Nguyen Dac Duong
```