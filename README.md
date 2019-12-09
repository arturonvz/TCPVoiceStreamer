# TCPVoiceStreamer
TCP Audio Streamer and Player (Voice Chat over IP) from CodeProject

# Introduction
This is a proprietary VoIP project to send and receive audio data by TCP. It's an extension of my first article Play or Capture Audio Sound. Send and Receive as Multicast (RTP). This application streams the audio data not by multicast but by TCP. So you can be sure there is no data lost and you can transfer them over subnets and routers away. The audio codec is U-Law. The sample rate is selectable from 5000 to 44100.

The server can run on your local PC. You can get your current IP4-Address with help of running cmd.exe and typing "ipconfig". You should use a static IP-Address, so that possible clients do not have to change their settings after reconnecting some days later. The clients must connect to the IP4-Address and port configured on the running server. The server can be run in silent mode (no input, no output) just transferring audio data between all connected clients.

Choose a free port that is not used by another application (do not use 80 or other reserved ports). You can connect within LAN or Internet. For Internet chatting, you can configure a port forwarding on your router.

Note !!! This is a proprietary project. You can't use my servers or clients with any other standardized servers or clients. I don't use standards like RTCP or SDP.
