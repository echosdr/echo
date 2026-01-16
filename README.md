# Echo

> **Featured on [RTL-SDR.com](https://www.rtl-sdr.com/echo-a-native-ios-client-for-kiwisdr-openwebrx/)** — _"Really cool looking app"_

**[Click here to join the TestFlight Beta Waitlist](https://forms.gle/uC7W8VTDodvbsQ21A)**

A native iOS command center for the KiwiSDR & OpenWebRX networks.

KiwiSDR & OpenWebRX provide global reception capabilities via their web interfaces. Echo builds upon this by wrapping the reliable web stream in a native iOS environment, enabling features that are only possible with a dedicated app.

## Features

- **Audio Engine Passthrough:** Uses the standard KiwiSDR/OpenWebRX web client for the waterfall & signal processing. This ensures 100% compatibility with all server decoding modes & extensions.
- **Scanner Mode:** Automatically cycles through a list of stations or presets at a set interval.
- **Global Map:** Native MapKit integration to visually explore the station network. Filtering available to isolate specific networks (KiwiSDR/OpenWebRX) or regions (e.g., "USA Only") on the map. 
- **Live Signal Metrics:** Real-time SNR (Signal-to-Noise) sorting to instantly identify the strongest receivers in the list.
- **Offline Frequency Library:** A searchable, local database of 20,000+ global frequencies that works without an internet connection.
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

**Current Version:** Alpha / Dev Build  
**TestFlight:** Coming February 2026

## Acknowledgments
Echo is an independent client and is not officially affiliated with the KiwiSDR or OpenWebRX projects.
* **KiwiSDR:** Created by John Seamons. Key Contributor: Christoph Mayer (Author of many core Kiwi features).
* **OpenWebRX:** Originally created by András Retzler, with ongoing development by Jakob Ketterl and the community.

Special thanks to these developers for building the incredible platforms that make this app possible.

---

### Screenshots
<img width="645" height="1398" alt="IMG_5147" src="https://github.com/user-attachments/assets/4d2248e7-7d69-4982-bede-f0260d8957b6" />
<img width="645" height="1398" alt="IMG_5148" src="https://github.com/user-attachments/assets/af75c62c-e4ae-4ea0-bc26-402aa04c2b49" />
<img width="645" height="1398" alt="IMG_5150" src="https://github.com/user-attachments/assets/b51c84c9-1fd0-4e05-9ec0-e97db3e75945" />
<img width="645" height="1398" alt="IMG_5153" src="https://github.com/user-attachments/assets/cf9b8af6-51e9-462d-9ae4-1ea15fcb23b2" /><img width="645" height="1398" alt="IMG_4959" src="https://github.com/user-attachments/assets/54b528fb-f77e-4bc3-b630-e47084e70a6d" />
