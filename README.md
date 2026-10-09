# Awesome-Streaming-Real-Time-Engagement

## Top Streaming Real-Time Engagement Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Live Video, Real-Time Messaging & Self-Hosted Engagement Platforms*  

**Last updated: October 2026**



This repository tracks notable **commercial real-time engagement platforms** and **open-source projects** that power live streaming, interactive video, real-time messaging, and audience engagement — from sub-second latency video to scalable pub/sub infrastructure.



**Examples** include Salesforce Real-Time Engagement, Agora.io, Twilio Live, LiveKit, Daily.co, Vonage Video API, Pusher, Ably, PubNub, and Sendbird Calls (the category leaders).



**Open-source emphasis**: Streaming real-time engagement is one of the strongest open-source domains. **LiveKit** leads as the open-source WebRTC platform with 20,700+ GitHub_Stars, powering ChatGPT's Advanced Voice Mode and used by Character.AI, Spotify, and Salesforce . **Jitsi** provides the most widely deployed open-source video conferencing with 25,000+ stars . **Centrifugo** delivers scalable real-time messaging with 8,000+ stars . **MediaMTX** brings zero-dependency multi-protocol media routing . **SRS** powers production live streaming with 29,000+ stars . **Janus** provides a general-purpose WebRTC gateway with 9,100+ stars . This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



> **Market Size & Structure:** The global Real-Time Engagement (CPaaS & WebRTC) market is estimated at **~$15 Billion – $20 Billion** and is **moderately fragmented**, featuring large enterprise market leaders alongside specialized infrastructure platforms.

| Product / Platform | Company Scale (Valuation / Revenue) | Starting Price (Paid Tier) | Free Tier / Trial Limit | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Salesforce Real-Time Engagement](https://www.salesforce.com/)** | **$186B Market Cap** ($41.5B Annual Rev) | $25/user/month (Salesforce Starter / Service Cloud baseline) | 30-day free trial (full environment access) | Salesforce's real-time engagement platform — integrated with Salesforce CRM for omnichannel customer engagement. Best for Salesforce enterprise customers. |
| **[Twilio Live](https://www.twilio.com/)** | **$42B Market Cap** ($5.07B Annual Rev) | $0.004/video participant min ($0.001/audio min) | $15 – $25 free trial credit upon sign-up | Twilio's live streaming & real-time communication platform — low-latency interactive video integrated with Twilio APIs. Best for interactive live events. |
| **[Vonage Video API](https://www.vonage.com/)** | **$6.2B Acquisition** ($1.4B Annual Rev) | $0.0041/participant minute | 100,000 free minutes trial (75k video / 25k advanced) | Video API platform (formerly TokBox OpenTok) — embed live WebRTC video. Best for interactive enterprise video applications. |
| **[Ably](https://ably.com/)** | **$2.1B Valuation** ($18.3M Annual Rev) | $29/month (Standard Plan; $2.50/M extra msgs) | 6,000,000 messages/month & 200 concurrent connections | Real-time messaging infrastructure — pub/sub with guaranteed delivery at scale. Best for mission-critical real-time messaging. |
| **[Sendbird Calls](https://sendbird.com/)** | **$1.1B Valuation** ($50M+ Annual Rev) | $399/month (Starter tier for up to 5k MAU) | Developer Plan: 100 MAUs free forever (or 30-day trial for 1,000 MAUs) | Voice and video calling API & SDKs — embed high-quality calling directly in mobile & web applications. Best for in-app communication. |
| **[Agora.io](https://www.agora.io/)** | **$345M Market Cap** ($160M+ Annual Rev) | $0.99 / 1,000 audio mins ($3.99 / 1,000 HD video mins) | 10,000 combined RTC minutes free every month | Real-time engagement platform — voice, video, and interactive streaming with sub-second latency and SDKs for every major platform. Best for interactive live streaming & social apps. |
| **[PubNub](https://www.pubnub.com/)** | **$220M Valuation** ($40M+ Annual Rev) | $98/month (Starter plan up to 1,000 MAU) | 200 MAUs & 1,000,000 transactions/month free | Real-time communication platform — pub/sub messaging, presence, and chat. Best for real-time applications at scale. |
| **[Daily.co](https://www.daily.co/)** | **~$150M Valuation** (Privately Held) | $0.004/participant minute (pay-as-you-go) | 10,000 participant minutes free every month | Real-time video and audio APIs — embed video calls in applications with simple SDKs. Best for developer-friendly video integration. |
| **[Pusher](https://pusher.com/)** | **$35M Acquisition** ($1.5M+ ARR) | $49/month (Startup plan: 1M msgs/day, 500 connections) | Sandbox plan: 200,000 messages/day & 100 concurrent connections | Real-time messaging platform — WebSocket-based pub/sub channels for applications. Best for developer real-time features. |





## Open-Source GitHub Projects



### WebRTC & Real-Time Video Platforms



- **[LiveKit](https://github.com/livekit/livekit)**  

  **End-to-end realtime stack for connecting humans and AI**, Apache-2.0 licensed with **20,705+ GitHub_Stars** . **Scalable, distributed WebRTC SFU written in Go using Pion** . **Modern client SDKs for JavaScript, Swift, Kotlin, Flutter, React Native, and Rust** . **Built for production with JWT authentication and robust networking (UDP/TCP/TURN)** . **Powers ChatGPT's Advanced Voice Mode; used by Character.AI, Spotify, and Salesforce** . **Easy to deploy: single binary, Docker, or Kubernetes** . **The leading open-source WebRTC platform for AI and real-time engagement** . **Best for building scalable real-time video applications** .



- **[Jitsi Meet](https://github.com/jitsi/jitsi-meet)**  

  **The leading open-source video conferencing platform**, Apache-2.0 licensed with **25,000+ GitHub_Stars** . **WebRTC-based with scalable SFU** . **Embeddable via IFrame API and SDKs** . **No account required** — start a meeting instantly . **Best for video conferencing** .



- **[Janus WebRTC Server](https://github.com/meetecho/janus-gateway)**  

  **General-purpose WebRTC server**, GPL-3.0 licensed with **9,159+ GitHub_Stars** . **Plugin architecture for VideoRoom, SIP, streaming, and more** . **Supports WebSockets, MQTT, RabbitMQ, and Data Channels** . **The reference for flexible WebRTC deployments** . **Best for custom WebRTC applications** .



- **[Jitsi Videobridge](https://github.com/jitsi/jitsi-videobridge)**  

  **WebRTC-compatible video router/SFU**, Apache-2.0 licensed with **3,103+ GitHub_Stars** . **Lets you build highly scalable video conferencing infrastructure** . **Powers Jitsi Meet** . **Best for scalable video conferencing** .



- **[mediasoup](https://github.com/versatica/mediasoup)**  

  **High-performance SFU library for WebRTC**, ISC licensed . **C++ core with Node.js signaling** . **Best for building custom WebRTC applications** .



- **[OpenVidu](https://github.com/OpenVidu/openvidu)**  

  **Open-source WebRTC platform**, Apache-2.0 licensed . **Build custom video applications with SDKs for JavaScript, React, Angular, Vue, iOS, Android, and Flutter** . **Best for custom video apps** .



### Real-Time Messaging & Pub/Sub



- **[Centrifugo](https://github.com/centrifugal/centrifugo)**  

  **Scalable real-time messaging server**, Apache-2.0 licensed with **8,000+ GitHub_Stars** . **WebSocket, HTTP-streaming, SSE, and GRPC** . **Pub/sub channels with presence and history** . **Best for real-time pub/sub messaging** .



- **[Mercure](https://github.com/dunglas/mercure)**  

  **Open-source protocol for real-time updates**, AGPL-3.0 licensed . **Server-sent events (SSE) based** . **Best for real-time web updates** .



- **[NATS](https://github.com/nats-io/nats-server)**  

  **Cloud-native messaging system**, Apache-2.0 licensed with **15,000+ GitHub_Stars** . **Lightweight, high-performance pub/sub** with JetStream for persistence . **Best for IoT and edge real-time messaging** .



- **[Socket.IO](https://github.com/socketio/socket.io)**  

  **Bidirectional event-based communication**, MIT licensed with **60,000+ GitHub_Stars** . **WebSocket with fallback to HTTP long-polling** . **Best for real-time web applications** .



- **[SignalR](https://github.com/dotnet/aspnetcore)**  

  **Microsoft's real-time web functionality**, Apache-2.0 licensed . **WebSocket with fallback transports** . **Best for .NET applications** .



### Live Streaming



- **[SRS (Simple Realtime Server)](https://github.com/ossrs/srs)**  

  **The leading open-source live streaming server**, MIT/MulanPSL-2.0 licensed with **29,206+ GitHub_Stars** . **Supports RTMP, WebRTC, HLS, HTTP-FLV, SRT, MPEG-DASH** . **RTMP latency 0.8–3s**; **min-latency mode ~0.1s for video-only** . **Scalable to millions of viewers** . **Best for production live streaming** .



- **[MediaMTX](https://github.com/bluenviron/mediamtx)**  

  **Ready-to-use zero-dependency live media server and media proxy**, MIT licensed . **Supports Media-over-QUIC, SRT, WebRTC, RTSP, RTMP, LL-HLS, MPEG-TS, and RTP** . **Automatic protocol conversion** . **Single executable, no dependencies** . **Best for edge and simple deployments** .



- **[Ant Media Server](https://github.com/ant-media/Ant-Media-Server)**  

  **Ultra-low latency streaming engine with WebRTC (~0.5s)**, open-source with **4,727+ GitHub_Stars** . **Supports WebRTC, SRT, RTMP, HLS, CMAF, RTSP, and H.265/HEVC** . **SDKs for iOS, Android, React Native, Flutter, Unity, and JavaScript** . **Best for ultra-low latency interactive streaming** .



- **[OvenMediaEngine](https://github.com/AirenSoft/OvenMediaEngine)**  

  **Sub-second latency live streaming server**, AGPL-3.0 licensed with **3,272+ GitHub_Stars** . **Supports WebRTC, LL-HLS, and SRT** for large-scale high-definition streaming . **Best for ultra-low latency** .



### Additional Strong Open-Source Options



- **SocketCluster** — Scalable pub/sub with WebSockets .

- **Deepstream** — Real-time data sync and messaging server .

- **Primus** — Universal WebSocket wrapper .

- **Faye** — Pub/sub messaging for web .

- **ActionCable** — Rails WebSocket integration .

- **Firebase Realtime Database** — Real-time data sync (not open-source) .

- **Supabase Realtime** — Open-source real-time subscriptions on PostgreSQL .

- **Appwrite Realtime** — Open-source real-time messaging .



**Frameworks for building custom real-time engagement solutions**: Combine **LiveKit** for scalable WebRTC video with AI integration and modern SDKs . Use **Jitsi** for video conferencing with IFrame embedding . Deploy **Centrifugo** for scalable real-time pub/sub messaging . Choose **SRS** or **MediaMTX** for live streaming with multi-protocol support . Integrate **Ant Media Server** or **OvenMediaEngine** for ultra-low latency WebRTC streaming . Use **Janus** for flexible WebRTC with plugin architecture . Note that true managed real-time engagement with global infrastructure, automatic scaling, and vendor-supported SLAs (Agora, Twilio Live, Daily.co) remains primarily commercial territory; open-source stacks provide strong WebRTC platforms, pub/sub messaging, and live streaming foundations that require integration for complete real-time engagement.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Real-time engagement platforms handle bandwidth-intensive workloads and may process sensitive communications. Self-hosted solutions require proper security hardening, bandwidth planning, and compliance with content regulations.

- **Latency vs. scalability trade-offs** — WebRTC delivers sub-second latency but scales to hundreds; HLS/DASH scales to millions but adds 6-30 seconds latency . Choose based on interactivity requirements.

- **TURN servers (Coturn)** are essential for NAT traversal — without them, WebRTC calls fail for users behind symmetric NAT or corporate firewalls .

- **License considerations**: LiveKit uses Apache-2.0 , Jitsi uses Apache-2.0 , Centrifugo uses Apache-2.0 , SRS uses MIT/MulanPSL-2.0 , and Ant Media Server is open-source . Verify licensing against your use case before committing.

- The open-source ecosystem provides strong WebRTC platforms, pub/sub messaging, and live streaming foundations, but **global infrastructure, automatic scaling, and vendor-supported SLAs** remain primarily commercial offerings.



---



**Made for real-time engineers, streaming architects, and organizations seeking real-time engagement sovereignty.**  

Let's make streaming real-time engagement more open, transparent, and interactive.
