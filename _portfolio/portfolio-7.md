---
title: "AI YouTube Auto Cutter & Smart Framing System"
excerpt: "A web-based system for automatically cutting long YouTube videos into short vertical clips with intelligent face tracking and framing. <br/><img src='/images/701.png'>"
collection: portfolio
---

This project presents a full-stack web application designed to automate the process of converting long-form YouTube videos into short, engaging vertical clips (9:16) suitable for platforms like TikTok, Reels, and Shorts.

The system integrates AI-based face detection and smart cropping to ensure that the main speaker remains the focus throughout the video, even when multiple people are present.

## Key Features

- **YouTube Video Integration**  
  Users can directly input a YouTube URL, and the system will load and process the video automatically.

- **Automatic Video Cutting (Batch Processing)**  
  Splits long videos into multiple short clips (e.g., 90 seconds each) with batch processing support.

- **Smart Face Tracking & Framing**  
  Uses AI to detect and follow the active speaker’s face, ensuring proper focus in vertical format (9:16).

- **Multiple Aspect Ratio Support**  
  Supports various output formats:
  - Landscape (16:9)
  - Vertical / Story (9:16)
  - Square (1:1)
  - Tall Feed (4:5)

- **Real-Time Processing Status**  
  Displays system status such as:
  - Live
  - Recording
  - Capturing
  - Processing
  - Finished

- **Recent Recording History**  
  Shows recently processed video clips for quick access and monitoring.

- **Downloadable Output Clips**  
  Users can easily download generated clips after processing is completed.

## Technologies Used

- **Backend**: Python (Video processing, AI detection), PHP (API & server logic)  
- **Frontend**: HTML, CSS, JavaScript  
- **Video Processing**: FFmpeg  
- **AI Processing**: OpenCV (Face Detection & Tracking)  
- **Integration**: YouTube API  
- **UI Design**: Custom dashboard interface  

## System Workflow

1. User inputs YouTube link  
2. System loads video metadata  
3. User selects:
   - Start time
   - End time
   - Clip duration  
4. AI processes video:
   - Detect faces
   - Track active speaker  
5. Video is automatically split into segments  
6. Output clips are generated in selected aspect ratio  
7. User downloads results  

## Outcome

This system helps:
- Automate content repurposing for social media  
- Save time in manual video editing  
- Improve engagement through smart framing  
- Enable scalable short-form content production  

## Interface Preview

<img src='/images/701.png' alt='AI Video Cutter Interface Preview'>
 
