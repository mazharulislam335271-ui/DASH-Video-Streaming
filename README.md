DASH Video Streaming & QoE Analysis
📌 Overview

This project implements Dynamic Adaptive Streaming over HTTP (DASH) using two Linux virtual machines.
Videos are transcoded into multiple bitrates and streamed via a web server. Network performance is evaluated using traffic control mechanisms.
Implementation
Videos transcoded using FFmpeg (1.5, 2, 4 Mbps)
DASH manifest and segments generated
Apache server used for hosting
VLC used for playback
iPerf used for bandwidth testing

FFmpeg setup and video processing
DASH packaging and segments generation
Apache server and streaming URLs
VLC playback
iPerf testing
Traffic control (TBF, Policing)
Conclusion

The project shows that network conditions affect streaming quality.
Adaptive streaming helps maintain better user experience under bandwidth limitations.
