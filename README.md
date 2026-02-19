# Echo

### **The Universal iOS SDR Client** 

> Listen to anything, from anywhere. Echo connects you to 2000+ community-hosted radio receivers spanning every continent. Tune into shortwave broadcasts from Asia, aviation communications over the Atlantic, mysterious numbers stations, or distant FM stations from hundreds of miles away, all from your iPhone. **KiwiSDR, OpenWebRX, WebSDR, and FM-DX** provide global reception capabilities via their web interfaces. Echo builds upon this by integrating these reliable streams into a native iOS environment, enabling features that are only possible with a dedicated app.

### As seen on [RTL-SDR.com](https://www.rtl-sdr.com/echo-ios-kiwisdr-openwebrx-app-now-in-beta-testing/)
> First described as a **"really cool looking app"** [(Jan '26)](https://www.rtl-sdr.com/echo-a-native-ios-client-for-kiwisdr-openwebrx/), Echo is now recognized as being **"designed to make it easy to search for and view public receivers on iOS"** [(Feb '26)](https://www.rtl-sdr.com/echo-ios-kiwisdr-openwebrx-app-now-in-beta-testing/).
### Beta Access
**Status:** The TestFlight Beta is **LIVE**.

* **Joined the waitlist?** All invites have been sent. Check your inbox!
* **Missed the list?** The free waitlist is now **closed**. You can still get immediate access to the beta by supporting the project:

[![Get Beta Access](https://img.shields.io/badge/Get_Beta_Access-Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/EchoSDR)

## Features

- **Background Audio:** Maintains connection & audio playback even when the device is locked or multitasking.
- **Audio Engine Passthrough:** Echo interfaces directly with the core KiwiSDR, OpenWebRX, WebSDR, and FM-DX signal processors for waterfall rendering and audio decoding. This ensures 100% compatibility with all server-side modes, plugins, and extensions.
- **Intelligent Profile Switching:** When tuning outside an OpenWebRX server's current frequency range, Echo automatically switches to the correct profile and displays visual "Switching Band..." feedback during the transition.
- **Scanner Mode:** Automatically cycles through a list of stations or presets at a set interval.
- **Global Map:** Native MapKit integration to visually explore the station network. Filtering available to isolate specific networks (KiwiSDR/OpenWebRX/WebSDR/FM-DX) on the map or regions (e.g., "USA Only") in the server list. 
- **Server Search:** Instantly search 2,000+ SDR receivers by name or location with dynamic result counts.
- **Custom Servers:** Add your own private or unlisted servers by selecting the server type (KiwiSDR, OpenWebRX, WebSDR, or FM-DX) and entering the URL.
- **Smart Manual Tuner:** Intelligently detects your input format (kHz vs. MHz) to instantly tune the correct band. Simply type "101.1" for FM or "15000" for Shortwave without ever needing to toggle a unit switch.
- **Live Signal Metrics:** Real-time SNR (Signal-to-Noise) sorting to instantly identify the strongest receivers in the list.
- **Offline Frequency Library:** A searchable, local EIBI database of 11,000+ global shortwave and utility frequencies.
- **Station Logging:** Integrated database for saving your favorite frequencies & station details.

## Roadmap (Coming Soon)
- **Smart Interpreter:** Live speech-to-text transcription and real-time language translation. 
- **Smart Recording:** One-tap audio capture with built-in speech-to-text transcription/translation to automatically document and identify station content. 

## Technical Implementation

- **Native UI and Mapping:** 100% SwiftUI interface paired with a highly optimized MapKit clustering engine, capable of rendering 2000+ global server nodes smoothly without the lag of traditional web wrappers.
- **Custom Audio Bridge:** A specialized background audio implementation that intercepts and processes complex SDR streams, enabling true lock-screen controls and uninterrupted iOS background playback.
- **Privacy:** Zero tracking. No analytics, no proprietary servers, no Ad IDs. All database entries (favorites/logs) are stored locally on-device or in your personal, encrypted iCloud container.

## Requirements

iOS 17+, iPhone/iPad/macOS (Apple Silicon)

## Acknowledgments
Echo is an independent client and is not officially affiliated with the KiwiSDR, OpenWebRX, WebSDR, or FMDX projects.
* **KiwiSDR:** Created by John Seamons. Key Contributor: Christoph Mayer (Author of many core Kiwi features).
* **OpenWebRX:** Originally created by András Retzler, with ongoing development by Jakob Ketterl and the community.
* **WebSDR:** Created by Pieter-Tjerk de Boer.
* **FM-DX:** Created by Marek Farkaš.

Special thanks to these developers for building the incredible platforms that make this app possible.

---

### Screenshots
<img width="645" height="1398" alt="IMG_5822" src="https://github.com/user-attachments/assets/08aee867-5547-4084-ae49-ad2664cab08d" />
<img width="645" height="1398" alt="IMG_5823" src="https://github.com/user-attachments/assets/ca8f2b40-b373-4ef7-a361-3eabbcfc76ea" />
<img width="1366" height="1024" alt="IMG_1267" src="https://github.com/user-attachments/assets/86cd775b-c792-4cdd-a81c-a20b4f20eb2b" />
<img width="645" height="1398" alt="IMG_5824" src="https://github.com/user-attachments/assets/c91713fe-9b9e-4d33-b99c-6e55f0705973" />
<img width="645" height="1398" alt="IMG_5281" src="https://github.com/user-attachments/assets/2bb1697a-fc81-420e-9946-a2d6cf8012af" />


