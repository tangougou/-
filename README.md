# 海康威视摄像机批量截图
食用方法：
在py目录放入ffmpeg.exe以及准备一份“海康摄像头IP地址.txt”放入海康摄像机的IP地址(每行一个)形如：
192.168.1.2
192.168.1.3
...

海康威视IPC通过RSTP协议FFMPEG截图保存以便留存巡检

# Hikvision IPC Batch Snapshot Tool

A professional Python tool for batch capturing snapshots from Hikvision IP cameras via RTSP using FFmpeg.

本项目用于海康威视 IPC 摄像机批量截图，通过 RTSP 调用 FFmpeg 实现自动抓图，适用于监控巡检与离线排查。

---

## 🚀 Features

- Batch snapshot from multiple IPC cameras
- RTSP stream capture
- FFmpeg based grabbing
- Timeout control
- Automatic image saving
- Simple configuration

---

## 🏗 Supported Devices

- Hikvision IPC


---

## 🧰 Tech Stack

- Python 3.x
- FFmpeg
- RTSP protocol


