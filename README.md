<div align="center">

<img alt="FacePlugin" src="https://raw.githubusercontent.com/Faceplugin-ltd/faceplugin-assets/main/brand/logo.png" width="380"/>

# Face Recognition SDK — Fully On-Premise

### 1:1 verification and 1:N identification with passive liveness, on your own servers and devices

**On-device and on-premise face recognition for Android, iOS, Flutter, React Native, .NET MAUI, Ionic, Web, Windows and Docker. No cloud, no per-match fees, and no biometric data leaving your infrastructure.**

<a href="https://faceplugin.com/"><img src="https://img.shields.io/badge/Website-faceplugin.com-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white" alt="FacePlugin face recognition SDK"></a>
<a href="https://doc.faceplugin.com/"><img src="https://img.shields.io/badge/Docs-doc.faceplugin.com-0A66C2?style=for-the-badge&logo=readthedocs&logoColor=white" alt="Face recognition SDK documentation"></a>
<a href="https://hub.docker.com/u/faceplugin"><img src="https://img.shields.io/badge/Docker%20Hub-faceplugin-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="FacePlugin Docker images"></a>
<a href="https://faceplugin.com/contact-us/"><img src="https://img.shields.io/badge/Request-License%20%26%20Demo-FF6F00?style=for-the-badge" alt="Request a face recognition SDK license"></a>

`NIST FRVT evaluated` · `1:1 verification` · `1:N identification` · `passive 2D liveness` · `100% offline` · `unlimited matching`

</div>

---

## What this repository is

This is the **product hub** for the FacePlugin **Face Recognition SDK**. Pick your platform below and clone that repository — each one is a complete, runnable demo app with the SDK already wired in.

Every platform wraps the **same native engine**, so a template extracted on Android matches the same face on iOS or on the server. Enrollment, template storage and search stay in **your** database.

## Choose your platform

| Platform | Repository | What you get |
| -------- | ---------- | ------------ |
| **Android** | [FaceRecognition-LivenessDetection-Android](https://github.com/Faceplugin-ltd/FaceRecognition-LivenessDetection-Android) | Native AAR, five-tab demo app |
| **iOS** | [FaceRecognition-LivenessDetection-iOS](https://github.com/Faceplugin-ltd/FaceRecognition-LivenessDetection-iOS) | Swift package and engine frameworks |
| **Flutter** | [FaceRecognition-LivenessDetection-Flutter](https://github.com/Faceplugin-ltd/FaceRecognition-LivenessDetection-Flutter) | `face_recognition_sdk` plugin |
| **React Native** | [FaceRecognition-LivenessDetection-ReactNative](https://github.com/Faceplugin-ltd/FaceRecognition-LivenessDetection-ReactNative) | `face-recognition-sdk` plugin |
| **.NET MAUI** | [FaceRecognition-LivenessDetection-DotNet-MAUI](https://github.com/Faceplugin-ltd/FaceRecognition-LivenessDetection-DotNet-MAUI) | One C# codebase, Android and iOS |
| **Ionic Capacitor** | [FaceRecognition-LivenessDetection-Ionic-Capacitor](https://github.com/Faceplugin-ltd/FaceRecognition-LivenessDetection-Ionic-Capacitor) | `face-recognition-capacitor` plugin |
| **Ionic Cordova** | [FaceRecognition-LivenessDetection-Ionic-Cordova](https://github.com/Faceplugin-ltd/FaceRecognition-LivenessDetection-Ionic-Cordova) | Cordova plugin |
| **JavaScript / Web** | [FaceRecognition-LivenessDetection-Javascript](https://github.com/Faceplugin-ltd/FaceRecognition-LivenessDetection-Javascript) | Face recognition in the browser |
| **React** | [FaceRecognition-React](https://github.com/Faceplugin-ltd/FaceRecognition-React) | React web demo |
| **Vue** | [FaceRecognition-Vue](https://github.com/Faceplugin-ltd/FaceRecognition-Vue) | Vue web demo |
| **Windows** | [FaceRecognition-Windows](https://github.com/Faceplugin-ltd/FaceRecognition-Windows) | On-premise HTTP API |
| **Linux / Docker** | [FaceRecognition-Docker](https://github.com/Faceplugin-ltd/FaceRecognition-Docker) | On-premise HTTP API |

> **Open source:** [Open-Source-Face-Recognition-SDK](https://github.com/Faceplugin-ltd/Open-Source-Face-Recognition-SDK) — the free, open-source face recognition SDK.

## What the SDK does

| Capability | Detail |
| ---------- | ------ |
| **Face detection** | Bounding box, landmarks, pose (yaw / pitch / roll), image quality |
| **1:1 verification** | Compare two faces and get a similarity score |
| **1:N identification** | Live search against your enrolled gallery |
| **Face templates** | Extract a compact template and store it in your own database |
| **Passive 2D liveness** | Anti-spoofing built into the mobile identify flow |
| **Face attributes** | Age, gender, emotion, mask, glasses, eye state, occlusion |

Mobile defaults: identify threshold **0.67**, liveness threshold **0.5**. The server HTTP API listens on port **8092**.

## Quick start

```bash
docker pull faceplugin/face-recognition:latest
```

On mobile, clone the platform repository above, place the engine from its Releases page, and run the demo on a physical phone. Full setup and API reference: **[doc.faceplugin.com](https://doc.faceplugin.com/)**.

## Other FacePlugin products

| Product | Hub | Use it when |
| ------- | --- | ----------- |
| **Face Liveness Detection** | [Face-Liveness-Detection-SDK](https://github.com/Faceplugin-ltd/Face-Liveness-Detection-SDK) | You need anti-spoofing **without** enrollment or 1:N |
| **ID Document Recognition** | [ID-Document-Recognition-SDK](https://github.com/Faceplugin-ltd/ID-Document-Recognition-SDK) | Passport, driving licence and ID card OCR, MRZ and barcode |

Combine all three for a complete **eKYC** flow: read the document, confirm it is genuine, check the selfie is a live person, then match that selfie to the document photo.

## Frequently asked questions

<details>
<summary><b>Is this a cloud API?</b></summary>

No. Everything runs on your own servers or on the end user's device. Face images and templates never leave your infrastructure, which keeps data residency and privacy compliance simple.
</details>

<details>
<summary><b>Does face recognition work offline?</b></summary>

Yes. Licensing is offline and inference needs no internet connection, including in air-gapped environments.
</details>

<details>
<summary><b>What is the difference between 1:1 and 1:N?</b></summary>

1:1 verification compares two faces and answers "are these the same person?". 1:N identification searches a live face against an enrolled gallery and answers "who is this?".
</details>

<details>
<summary><b>Are there per-match or per-API-call fees?</b></summary>

No. Licences are offline and matching is unlimited.
</details>

<details>
<summary><b>Where are face templates stored?</b></summary>

In your database. The SDK extracts a template and hands it back; it never uploads or stores it for you.
</details>

<details>
<summary><b>Can I try it before buying?</b></summary>

Yes. Every platform repository ships a runnable demo app with a sample licence key. [Request a key](https://faceplugin.com/contact-us/) for your own application id.
</details>

## Support

| | |
| --- | --- |
| 🌐 Website | [faceplugin.com](https://faceplugin.com) |
| 📘 Documentation | [doc.faceplugin.com](https://doc.faceplugin.com) |
| 🤗 Hugging Face | [FacePlugin-Ltd](https://huggingface.co/FacePlugin-Ltd) |
| 🐳 Docker Hub | [faceplugin](https://hub.docker.com/u/faceplugin) |
| ✉️ Email | [info@faceplugin.com](mailto:info@faceplugin.com) |
| 💬 Telegram | [@FacePluginSupport](https://t.me/FacePluginSupport) |
| 📱 WhatsApp | [+1 (469) 278-4822](https://wa.me/14692784822) |

<div align="center">
<sub><b>Keywords:</b> face recognition SDK · face verification · face identification · 1:1 face matching · 1:N face search · face detection · face landmarks · face attributes · face liveness detection · anti-spoofing · biometric authentication · identity verification · eKYC · KYC · on-premise face recognition · offline face recognition · Android · iOS · Flutter · React Native · .NET MAUI · Ionic · JavaScript · React · Vue · Windows · Linux · Docker</sub>
</div>
