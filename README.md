# Access-camera-from-ahywhere

In this lab, I will make your local video streaming system accessible from anywhere over the Internet.

This demonstrates how IoT systems can be accessed remotely.

# Local Video Streaming with ngrok

## 🌐 My ngrok URL
**URL:** (https://pampers-gonad-revolver.ngrok-free.dev/)
*(Note: This link is temporary and only active while my ngrok session is running).*

## 🚀 How I Started the System
To get this system running locally and exposed to the internet, I followed these steps:
1. Navigated to my project directory using the Command Prompt.
2. Started the local Flask video streaming server by running `python app.py`.
3. Verified the stream was working locally at `http://localhost:5000`.
4. Opened a second Command Prompt in the same directory.
5. Started the ngrok tunnel by running `ngrok http 5000`.
6. Copied the generated public URL from the ngrok terminal.

## ✅ External Access Result
**Success!** The external access worked perfectly. I was able to disconnect my smartphone from the local Wi-Fi, use my cellular data network, and access the live camera stream through the public ngrok URL.

## 🛠️ Problems Faced (and Solved)
* The setup was smooth and I didn't encounter any major errors.

<img width="950" height="476" alt="Screenshot 2026-04-15 230836" src="https://github.com/user-attachments/assets/6c705ffb-0881-4ac5-b61a-1b24d7130433" />
<img width="847" height="960" alt="Screenshot 2026-04-15 230900" src="https://github.com/user-attachments/assets/084820af-f0a8-435a-bbbc-205cff47f164" />
<img width="1920" height="1200" alt="Screenshot_2026-04-15-23-13-21-249_com android chrome" src="https://github.com/user-attachments/assets/603b6243-6623-4883-8952-e3945e26726d" />




