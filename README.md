# Echo

### **The Universal iOS SDR Client** 

### 🚀 Now Available on the App Store
**Status:** Echo is officially live! You can now download the universal SDR client for iOS.

[![Download on the App Store](https://img.shields.io/badge/Download_on_the-App_Store-000000?style=for-the-badge&logo=apple&logoColor=white)](https://apps.apple.com/app/echo-global-sdr-receiver/id6759174390)


> Listen to anything, from anywhere. Echo connects you to 2000+ community-hosted radio receivers spanning every continent. Tune into shortwave broadcasts from Asia, aviation communications over the Atlantic, mysterious numbers stations, or distant FM stations from hundreds of miles away, all from your iPhone. **KiwiSDR, OpenWebRX, WebSDR, and FM-DX Webserver** provide global reception capabilities via their web interfaces. Echo builds upon this by integrating these reliable streams into a native iOS environment, enabling features that are only possible with a dedicated app.

### As seen on [Radio World](https://www.radioworld.com/tech-and-gear/nicks-signal-spot/echo-app-brings-the-power-of-sdrs-into-your-pocket)
> Praised as a standout mobile solution for the community, Echo features a **"thoughtfully designed interface"** that reviewer Nick Langan has **"loved using."** *Radio World* celebrates the app for making it easier to search and listen to public receivers straight from your iPhone or iPad, noting there has **"never been a better time to engage in the hobby"** [(Apr '26)](https://www.radioworld.com/tech-and-gear/nicks-signal-spot/echo-app-brings-the-power-of-sdrs-into-your-pocket).

### As seen on [RTL-SDR.com](https://www.rtl-sdr.com/echo-kiwisdr-openwebrx-websdr-and-fm-dx-ios-browser-app-now-officially-released/)
> First described as a **"really cool looking app"** [(Jan '26)](https://www.rtl-sdr.com/echo-a-native-ios-client-for-kiwisdr-openwebrx/), Echo is recognized as being **"designed to make it easy to search for and view public receivers on iOS"** [(Feb '26)](https://www.rtl-sdr.com/echo-ios-kiwisdr-openwebrx-app-now-in-beta-testing/). RTL-SDR covered Echo's official launch on the App Store [(Apr '26)](https://www.rtl-sdr.com/echo-kiwisdr-openwebrx-websdr-and-fm-dx-ios-browser-app-now-officially-released/).


### As seen on [SWLing Post](https://swling.com/blog/2026/04/scott-recommends-the-new-echo-global-sdr-ios-app/)
> Praised as a **"very capable listening companion"** that is **"very stable for long listening sessions,"** Echo leverages its native iOS development to feature **"full background audio for uninterrupted listening"** [(Apr '26)](https://swling.com/blog/2026/04/scott-recommends-the-new-echo-global-sdr-ios-app/).

---

### Support Development 
If you enjoy using Echo and want to help cover developer fees and future features, consider supporting the project:

[![Support Echo](https://img.shields.io/badge/Support_Echo-Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/EchoSDR)

## Features

- **Background Audio:** Maintains connection & audio playback even when the device is locked or multitasking.
- **Audio Engine Passthrough:** Echo interfaces directly with the core KiwiSDR, OpenWebRX, WebSDR, and FM-DX Webserver signal processors for waterfall rendering and audio decoding. This ensures 100% compatibility with all server-side modes, plugins, and extensions.
- **Intelligent Profile Switching:** When tuning outside an OpenWebRX server's current frequency range, Echo automatically switches to the correct profile and displays visual "Switching Band..." feedback during the transition.
- **Scanner Mode:** Automatically cycles through a list of stations or presets at a set interval.
- **Global Map:** Native MapKit integration to visually explore the station network. Filtering available to isolate specific networks (KiwiSDR/OpenWebRX/WebSDR/FM-DX Webserver) on the map or regions (e.g., "USA Only") in the server list. 
- **Server Search:** Instantly search 2,000+ SDR receivers by name or location with dynamic result counts.
- **Custom Servers:** Add your own private or unlisted servers by selecting the server type (KiwiSDR, OpenWebRX, WebSDR, or FM-DX Webserver) and entering the URL.
- **Smart Manual Tuner:** Intelligently detects your input format (kHz vs. MHz) to instantly tune the correct band. Simply type "101.1" for FM or "15000" for Shortwave without ever needing to toggle a unit switch.
- **Offline Frequency Library:** A searchable, local EIBI database of 9000+ global shortwave and utility frequencies.
- **Station Logging:** Integrated database for saving your favorite frequencies & station details.

## Echo Pro

Echo Pro expands what you can do with the signals you hear, adding recording, live transcription, saved-audio transcription, translation, and iCloud sync directly inside Echo.

- **Live Transcription:** Follow spoken radio audio as text in real time while continuing to listen and use the receiver.
- **Smart Recording:** Record audio directly from the receiver and keep each recording organized with its station, frequency, mode, date, and duration.
- **Saved-Audio Transcription:** Turn recordings into timestamped transcripts that can be reviewed, copied, saved, or shared later.
- **On-Device Translation:** Detect supported languages and translate transcripts into English directly on-device.
- **Recording Search:** Search your saved recordings and quickly return to past stations, frequencies, and broadcasts.
- **iCloud Sync:** Keep recordings, audio, and associated information synchronized across your Apple devices with iCloud.
- **On-Device Processing:** Transcription, language detection, and translation are processed directly on your device.

Echo Pro is an optional subscription. The core Echo SDR experience remains available without Pro. 

## Technical Implementation

- **Native UI and Mapping:** 100% SwiftUI interface paired with a highly optimized MapKit clustering engine, capable of rendering 2000+ global server nodes smoothly without the lag of traditional web wrappers.
- **Custom Audio Bridge:** A specialized background audio implementation that intercepts and processes complex SDR streams, enabling true lock-screen controls and uninterrupted iOS background playback.
- **On-Device Speech Processing:** Live transcription, saved-audio transcription, language detection, and translation are integrated directly into Echo and processed on-device.
- **iCloud Sync:** Echo Pro can synchronize recording metadata and the actual recorded audio between your Apple devices using iCloud.
- **Privacy:** Zero tracking. No analytics. No Ad IDs. Transcription, language detection, and translation happen on-device. Favorites, logs, recordings, and other synced Echo data remain on your devices or in your personal iCloud container.

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

<img width="1290" height="2796" alt="Sideways" src="https://github.com/user-attachments/assets/b3a98e0b-be92-4ba8-8851-dde6315af24b" />
<img width="1290" height="2796" alt="Home" src="https://github.com/user-attachments/assets/53a3f1b7-5b60-46b4-802d-ea8eb021e365" />
<img width="1290" height="2796" alt="Scan" src="https://github.com/user-attachments/assets/62e54e17-d362-481f-8eb0-c2e7ea8d3295" />
<img width="1290" height="2796" alt="Capture" src="https://github.com/user-attachments/assets/8543b4b5-41b9-4b32-893a-fc9397b5a477" />
<img width="1290" height="2796" alt="Read" src="https://github.com/user-attachments/assets/e36ef6be-5d58-4b55-bb87-5714f2292116" />
<img width="1284" height="2778" alt="5 2" src="https://github.com/user-attachments/assets/5073e891-bd74-4b4e-abd1-1f50bb50b942" />







#

