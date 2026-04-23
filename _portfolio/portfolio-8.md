---
title: "Android Live Streaming App (StreamPack Integration) - Mobile SRT Broadcaster"
excerpt: "A production-ready Android live streaming application built with StreamPack library, supporting SRT protocol for low-latency video broadcasting. Successfully deployed in real-world production environment.<br/><img src='/images/srt-streaming-preview-main.jpg'>"
collection: portfolio
---

This project showcases a **production-ready mobile live streaming application** developed for Android devices using the **[StreamPack library](https://github.com/ThibaultBee/StreamPack)**. The system enables real-time video broadcasting with **low-latency SRT (Secure Reliable Transport)** protocol, making it ideal for professional broadcasting environments, live reporting, studio monitoring, and mobile journalism.

The application has been **successfully implemented and used in real-world production**, demonstrating its reliability, stability, and performance in actual broadcasting scenarios.

---

## 📱 Application Overview

<div style="text-align: center; margin: 20px 0;">
  <img src="/images/srt-streaming-preview-main.jpg" alt="Live Streaming Preview Main Interface" style="width: 100%; max-width: 800px; border-radius: 16px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);">
  <p style="color: #666; font-size: 0.9rem; margin-top: 8px;">Main interface – Live streaming control panel</p>
</div>

This Android application allows users to capture and stream video directly from their mobile devices to any SRT-compatible server, transforming Android devices into professional broadcasting tools.

---

## 🚀 Key Features

### 🎥 Real-Time Video Streaming
- Live video capture from Android camera  
- Low-latency streaming with SRT protocol  
- Stable transmission optimized for mobile networks (4G/5G/Wi-Fi)  
- Production-ready performance  

<div style="margin: 20px 0;">
  <img src="/images/srt-streaming-live-view.jpg" alt="Live Streaming View Interface" style="width: 100%; border-radius: 16px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);">
  <p style="color: #666; font-size: 0.9rem; text-align: center; margin-top: 8px;">Live streaming view – Real-time monitoring</p>
</div>

---

### ⚙️ Advanced Encoder Configuration

| Setting | Value |
|---------|-------|
| Encoder | H.264 / AVC |
| Resolution | 1280x720 (HD Ready) |
| Frame Rate | 30 fps |
| Profile | High |
| Level | 5.2 |
| Bitrate | Adjustable |

<div style="margin: 20px 0;">
  <img src="/images/srt-streaming-video-settings.jpg" alt="Video Configuration Settings" style="width: 100%; border-radius: 16px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);">
  <p style="color: #666; font-size: 0.9rem; text-align: center; margin-top: 8px;">Video encoder configuration panel</p>
</div>

---

### 🔊 Professional Audio Streaming

| Setting | Value |
|---------|-------|
| Encoder | AAC (Advanced Audio Coding) |
| Channels | Stereo |
| Bitrate | 128 Kbps |
| Sample Rate | 44.1 kHz |
| Byte Format | 16-bit |
| Profile | Low-Complexity (LC) |

<div style="margin: 20px 0;">
  <img src="/images/srt-streaming-audio-settings.jpg" alt="Audio Configuration Settings" style="width: 100%; border-radius: 16px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);">
  <p style="color: #666; font-size: 0.9rem; text-align: center; margin-top: 8px;">Audio encoder configuration panel</p>
</div>

---

### 🌐 SRT Protocol Integration (StreamPack)

| Parameter | Value |
|-----------|-------|
| Protocol | SRT (Secure Reliable Transport) |
| Mode | Caller |
| Endpoint | `srt://[IP]:[PORT]?mode=caller` |
| Features | Secure & reliable over unpredictable networks |

<div style="margin: 20px 0;">
  <img src="/images/srt-streaming-srt-config.jpg" alt="SRT Protocol Configuration" style="width: 100%; border-radius: 16px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);">
  <p style="color: #666; font-size: 0.9rem; text-align: center; margin-top: 8px;">SRT server configuration – Endpoint settings</p>
</div>

---

### 📱 Real-Time Control Interface
- One-tap Start/Stop streaming  
- Live preview monitoring  
- Camera switching (front/back)  
- Zoom control  
- Real-time status indicators (connection, bitrate, latency)  

---

## 🛠 Technologies Used

<div style="display: flex; flex-wrap: wrap; gap: 16px; margin: 20px 0;">
  <div style="flex: 1; min-width: 200px; background: #f8f9fa; padding: 16px; border-radius: 12px; border-left: 4px solid #667eea;">
    <strong>📱 Mobile Platform</strong><br>Android (Java/Kotlin)
  </div>
  <div style="flex: 1; min-width: 200px; background: #f8f9fa; padding: 16px; border-radius: 12px; border-left: 4px solid #667eea;">
    <strong>📚 Streaming Library</strong><br><a href="https://github.com/ThibaultBee/StreamPack" target="_blank">StreamPack</a>
  </div>
  <div style="flex: 1; min-width: 200px; background: #f8f9fa; padding: 16px; border-radius: 12px; border-left: 4px solid #667eea;">
    <strong>🎬 Video Codec</strong><br>H.264 / AVC
  </div>
  <div style="flex: 1; min-width: 200px; background: #f8f9fa; padding: 16px; border-radius: 12px; border-left: 4px solid #667eea;">
    <strong>🔊 Audio Codec</strong><br>AAC-LC
  </div>
  <div style="flex: 1; min-width: 200px; background: #f8f9fa; padding: 16px; border-radius: 12px; border-left: 4px solid #667eea;">
    <strong>🌐 Streaming Protocol</strong><br>SRT (Secure Reliable Transport)
  </div>
  <div style="flex: 1; min-width: 200px; background: #f8f9fa; padding: 16px; border-radius: 12px; border-left: 4px solid #667eea;">
    <strong>📡 Network</strong><br>4G/5G/Wi-Fi
  </div>
</div>

---

## 🔄 System Workflow

1. **Launch Android App**  
2. **Configure Streaming Parameters**  
   - Video resolution & bitrate  
   - Audio bitrate & channels  
   - SRT server IP & port  
3. **Connect to SRT Server**  
4. **Start Live Streaming**  
5. **Real-time Encoding** (H.264 + AAC)  
6. **SRT Packet Transmission**  
7. **Server Receives & Distributes Stream**  

---

## 🎯 Production Outcome

This application delivers:

- ✅ **Professional-grade live streaming** from Android devices  
- ✅ **Low-latency transmission** using SRT protocol  
- ✅ **Portable broadcasting solution** eliminating heavy equipment  
- ✅ **Seamless integration** with existing broadcast infrastructure  
- ✅ **Proven reliability** in actual production environments  

**Use Cases:**  
📺 TV News & Live Reporting · 🎪 Event Broadcasting · 🏟 Sports Coverage · 📡 Remote Studio Monitoring · 🚁 Mobile Journalism (MoJo)

---

## 🖼 Complete Interface Gallery

<div style="display: flex; flex-wrap: wrap; gap: 16px; justify-content: center; margin: 20px 0;">
  <div style="flex: 1; min-width: 200px;">
    <img src="/images/srt-streaming-preview-main.jpg" alt="Main Preview" style="width: 100%; border-radius: 12px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
    <p style="text-align: center; font-size: 0.8rem;">Main Preview</p>
  </div>
  <div style="flex: 1; min-width: 200px;">
    <img src="/images/srt-streaming-live-view.jpg" alt="Live View" style="width: 100%; border-radius: 12px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
    <p style="text-align: center; font-size: 0.8rem;">Live View</p>
  </div>
  <div style="flex: 1; min-width: 200px;">
    <img src="/images/srt-streaming-video-settings.jpg" alt="Video Settings" style="width: 100%; border-radius: 12px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
    <p style="text-align: center; font-size: 0.8rem;">Video Settings</p>
  </div>
</div>

<div style="display: flex; flex-wrap: wrap; gap: 16px; justify-content: center; margin: 20px 0;">
  <div style="flex: 1; min-width: 200px;">
    <img src="/images/srt-streaming-audio-settings.jpg" alt="Audio Settings" style="width: 100%; border-radius: 12px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
    <p style="text-align: center; font-size: 0.8rem;">Audio Settings</p>
  </div>
  <div style="flex: 1; min-width: 200px;">
    <img src="/images/srt-streaming-srt-config.jpg" alt="SRT Config" style="width: 100%; border-radius: 12px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
    <p style="text-align: center; font-size: 0.8rem;">SRT Configuration</p>
  </div>
</div>

---

## 📚 References

- [StreamPack Library](https://github.com/ThibaultBee/StreamPack) – Android streaming library used in this project  
- [SRT Alliance](https://www.srtalliance.org/) – Secure Reliable Transport protocol  
- [Android Camera2 API](https://developer.android.com/training/camera2) – Camera implementation  

---

> **Status:** ✅ Production Ready – Successfully deployed in live broadcasting environment
