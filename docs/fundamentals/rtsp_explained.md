# RTSP - Realtime Streaming Protocol

RTSP is the most important protocol used n IP camera streaming for AI and computer vision systems.
It allows applications to receive realtime video streams from network cameras

# Why RTSP Matters

RTSP is the bridge between:
- IP camera
- Linux system
- AI inference pipeline

# RTSP Architecture

```text
IP Camera
    ↓ RTSP
Network
    ↓
OpenCV / FFmpeg / VLC
    ↓
AI Model
```

# RTSP URL Structure

Typical format:

```text
rtsp://USERNAME:PASSWORD@IP_ADDRESS:PORT/PATH
```

Example:

```text
rtsp://admin:password@192.168.1.100:554/Streaming/Channels/101
```

# RTSP And OpenCV

Basic OpenCV usage:

```python
import cv2

rtsp_url = "rtsp://..."

cap = cv2.VideoCapture(rtsp_url)

while True:

    ret, frame = cap.read()

    if not ret:
        break

    cv2.imshow("RTSP", frame)

    if cv2.waitKey(1) == 27:
        break
```
