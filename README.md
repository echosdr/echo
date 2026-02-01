# Echo

[![Support Echo on Ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/EchoSDR)

**The universal radio receiver for iOS.** 

> Listen to anything, from anywhere. Echo connects you to 600+ community-hosted radio receivers spanning every continent. Tune into shortwave broadcasts from Asia, aviation communications over the Atlantic, mysterious numbers stations, or distant FM stations from hundreds of miles away, all from your iPhone. No antenna required.

> **Featured on [RTL-SDR.com](https://www.rtl-sdr.com/echo-a-native-ios-client-for-kiwisdr-openwebrx/)** — _"Really cool looking app"_

### ✈️ Beta Access
**Status:** 🟡 Free Waitlist is **CLOSED**.

You can still get **Guaranteed Priority Access** (and 3 months of Pro) by backing the Launch Fund:

[![Join Priority Waitlist](https://img.shields.io/badge/Join_Priority_Waitlist-Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/EchoSDR)

A native iOS command center for the KiwiSDR, OpenWebRX, WebSDR, and FM-DX networks.

KiwiSDR, OpenWebRX, WebSDR, and FM-DX provide global reception capabilities via their web interfaces. Echo builds upon this by wrapping the reliable web stream in a native iOS environment, enabling features that are only possible with a dedicated app.

## Features

- **Audio Engine Passthrough:** Uses the standard KiwiSDR/OpenWebRX/WebSDR/FM-DX web client for the waterfall & signal processing. This ensures 100% compatibility with all server decoding modes & extensions.
- **Scanner Mode:** Automatically cycles through a list of stations or presets at a set interval.
- **Global Map:** Native MapKit integration to visually explore the station network. Filtering available to isolate specific networks (KiwiSDR/OpenWebRX/WebSDR/FM-DX) or regions (e.g., "USA Only") on the map. 
- **Live Signal Metrics:** Real-time SNR (Signal-to-Noise) sorting to instantly identify the strongest receivers in the list.
- **Offline Frequency Library:** A searchable, local database of 10,000+ global frequencies.
- **Station Logging:** Integrated database for saving frequencies & station details.
- **Quick Presets:** Optimized interface for switching bands on a touch screen.

## Roadmap (Coming Soon)
- **Background Audio:** Maintains connection & audio playback even when the device is locked or multitasking.
- **Smart Interpreter:** Live speech-to-text transcription and real-time language translation. 
- **Smart Recording:** One-tap audio capture with built-in speech-to-text transcription/translation to automatically document and identify station content. 

## Technical Implementation

- **UI/Logic:** 100% Native SwiftUI (Maps, Database, Settings, Transcription).
- **Privacy:** Zero tracking. No analytics, no proprietary servers, no Ad IDs. All database entries (favorites/logs) are stored locally on-device or in your personal, encrypted iCloud container.


## Requirements

iOS 16+, iPhone/iPad/macOS (Apple Silicon)

## Status

**Current Version:** Beta

**TestFlight:** Coming February 2026

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
<img width="1366" height="1024" alt="IMG_5821" src="https://github.com/user-attachments/assets/d80ed25f-76d6-45ba-9869-c0db3cb7646e" />
<img width="645" height="1398" alt="IMG_5824" src="https://github.com/user-attachments/assets/c91713fe-9b9e-4d33-b99c-6e55f0705973" />
<img width="645" height="1398" alt="IMG_5281" src="https://github.com/user-attachments/assets/2bb1697a-fc81-420e-9946-a2d6cf8012af" />


