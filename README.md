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
Echo is an independent client and is not officially affiliated with the KiwiSDR or OpenWebRX projects.
* **KiwiSDR:** Created by John Seamons. Key Contributor: Christoph Mayer (Author of many core Kiwi features).
* **OpenWebRX:** Originally created by András Retzler, with ongoing development by Jakob Ketterl and the community.

Special thanks to these developers for building the incredible platforms that make this app possible.

---

### Screenshots
<img width="645" height="1398" alt="IMG_5508" src="https://github.com/user-attachments/assets/fa9d9580-fdce-43a7-80ac-182b5be507cd" />
<img width="645" height="1398" alt="IMG_5509" src="https://github.com/user-attachments/assets/59dc4b97-f3b1-4662-bf1f-fdb80e639939" />
<img width="645" height="1398" alt="IMG_5513" src="https://github.com/user-attachments/assets/e9359d9b-8522-4c63-87a3-7e8e3ac53b2e" />
<img width="645" height="1398" alt="IMG_5514" src="https://github.com/user-attachments/assets/978bf59f-9144-46f7-b872-dfb699fe5511" />
<img width="645" height="1398" alt="IMG_5515" src="https://github.com/user-attachments/assets/f57bf2bf-a8c6-4134-afc9-464e45d3d7a8" />


