# Awesome-Interactive-Presentation-Platform

## Top Interactive Live Mobile App Testing Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Real Device Clouds, Remote Device Farms, Live Interactive Debugging, Screen Mirroring & Emulators*  

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Interactive Live Mobile App Testing**. These tools enable QA engineers and mobile developers to interactively test, stream, mirror, and debug Android (`.apk`, `.aab`) and iOS (`.ipa`) applications on physical devices and emulators directly from a web browser.



**Examples** include BrowserStack App Live, Sauce Labs Real Device Live, AWS Device Farm Remote Access, Kobiton Live, Perfecto Interactive, BitBar Live, HeadSpin Remote, TestGrid Live, Genymotion SaaS, and Appetize.io (the category leaders). 



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting private device farms, ultra-low-latency screen mirroring, remote ADB/WebDriverAgent control, and containerized Android/iOS emulators — ideal for mobile QA teams, SDETs, and platform engineers building on-premises device labs.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[BrowserStack App Live](https://browserstack.com)**  

  Cloud-hosted real device testing platform allowing interactive manual testing of native and hybrid mobile apps across thousands of iOS and Android devices.



- **[Sauce Labs Real Device Cloud](https://saucelabs.com)**  

  Enterprise mobile testing platform providing live interactive access to physical smartphones and tablets with network throttling, biometrics, and dev tools.



- **[AWS Device Farm Remote Access](https://amazon.com)**  

  Cloud-based app testing service enabling developers to interact directly with real Android and iOS devices hosted in AWS data centers via a browser.



- **[Kobiton Live](https://kobiton.com)**  

  Mobile-first real device testing platform offering ultra-responsive live manual sessions, gesture controls, session recording, and real-time logs.



- **[Perfecto Interactive (Perforce)](https://perfecto.io)**  

  Enterprise continuous testing cloud supporting live manual debugging, location spoofing, and biometric injection on real mobile devices.



- **[SmartBear BitBar Live](https://bitbar.com)**  

  Flexible cloud-based mobile testing lab providing instant browser access to real Android and iOS devices for manual and exploratory testing.



- **[HeadSpin Remote](https://headspin.io)**  

  Global real-device experience platform offering remote interactive testing across carrier networks with deep audio, video, and network telemetry.



- **[TestGrid Live](https://testgrid.io)**  

  End-to-end mobile testing cloud offering interactive manual testing on real devices alongside automated test execution and performance metrics.



- **[Genymotion SaaS](https://genymotion.com)**  

  Cloud-based Android virtual device platform allowing developers to stream and interact with scalable Android emulators directly in the browser.



- **[Appetize.io](https://appetize.io)**  

  Browser-based iOS simulators and Android emulators enabling instant zero-install app streaming for demos, QA testing, and customer support.



## Open-Source GitHub Projects



- **[DeviceFarmer / STF (Smartphone Test Farm)](https://github.com)**  

  Flagship open-source web application for remotely controlling, viewing, and debugging dozens of real Android and iOS smartphones directly from a browser.



- **[scrcpy (by Genymobile)](https://github.com)**  

  Ultra-low-latency, high-performance open-source screen mirroring and remote control tool for Android devices connected via USB or TCP/IP.



- **[ws-scrcpy](https://github.com)**  

  Web client prototype for `scrcpy` enabling multi-touch interactive Android screen streaming, shell access, and file management in any modern browser.



- **[Appium Device Farm](https://github.com)**  

  Open-source Appium plugin that turns connected Android and iOS devices into a shareable web-accessible device lab with live video streaming and manual control.



- **[Sonic Cloud](https://github.com)**  

  Enterprise-grade open-source remote control and automated testing platform for Android, iOS, and HarmonyOS devices with real-time browser mirroring.



- **[GADS (Go Appium Device Server)](https://github.com)**  

  Lightweight open-source device farm built in Go supporting real-time interactive browser streaming and management for both Android and iOS physical devices.



- **[Appium WebDriverAgent (WDA)](https://github.com)**  

  Core open-source WebDriver server implementation for iOS that powers remote touch injection, screen streaming, and live UI inspection on iPhones and iPads.



- **[idb (iOS Development Bridge by Meta)](https://github.com)**  

  Flexible open-source command-line interface and daemon for automating and interactively controlling iOS simulators and physical devices remotely.



- **[go-ios](https://github.com)**  

  Cross-platform open-source tool written in Go enabling iOS device management, app installation, UI automation, and screen streaming on Linux, macOS, and Windows.



- **[Android-Docker (by budtmo)](https://github.com)**  

  Containerized Android emulator solution packaged with noVNC, Appium, and ADB so teams can interactively test mobile apps inside a web browser.



- **[Redroid (Remote Android)](https://github.com)**  

  GPU-accelerated Android-in-Cloud (AIC) Docker solution enabling high-density cloud gaming, live mobile app testing, and remote desktop streaming.



- **[Waydroid](https://github.com)**  

  Container-based approach to boot a full Android system on standard Linux hosts with near-native performance for fast interactive app testing.



- **[Bliss OS / Android-x86](https://github.com)**  

  Open-source Android OS builds engineered for x86_64 virtual machines and cloud hypervisors to run interactive Android testing instances at scale.



- **[Selenoid / Moon (Aerokube)](https://github.com)**  

  Lightweight Golang Selenium/Appium hub executing containerized browser and Android emulator sessions with live VNC screen viewing.



- **[Vysor / QtScrcpy](https://github.com)**  

  Cross-platform open-source Android real-time display control software offering multi-device group control, keymapping, and wireless debugging.



- **[Flipper (by Meta)](https://github.com)**  

  Extensible open-source desktop debugging platform for iOS, Android, and React Native apps featuring live layout inspection, network logs, and database viewers.



- **[Mobile Security Framework (MobSF)](https://github.com)**  

  Open-source mobile app pentesting and dynamic analysis framework featuring an interactive instrumented Android/iOS runtime environment.



- **[Appium Inspector](https://github.com)**  

  Open-source GUI inspector for Appium allowing QA engineers to interactively tap, swipe, view live screenshots, and inspect native UI hierarchies.



- **[Maestro](https://github.com)**  

  Modern open-source mobile UI testing framework with an interactive Studio mode for live element inspection and rapid flow authoring on iOS and Android.



- **[Selenium Grid 4 (with Appium Relay)](https://github.com)**  

  Distributed open-source grid capable of routing live interactive VNC/video streams and WebDriver sessions across connected mobile nodes.



### Additional Strong Open-Source Options



- **[ADB over WebRTC / WebSockets Bridges](https://github.com)** for building custom low-latency browser-based remote Android labs.

- **[libimobiledevice](https://github.com)** for cross-platform native communication with iOS devices without relying on proprietary Apple tools.

- **[noVNC & TigerVNC Web Clients](https://github.com)** for embedding interactive HTML5 VNC streams of containerized Android emulators into internal QA portals.

- **[USB/IP & Networked USB Hubs](https://github.com)** for exposing physically racked smartphones across distributed CI/CD worker nodes.

- Many community **Kubernetes device-plugin manifests** for scheduling real USB-attached Android and iOS devices inside K8s clusters.



**Frameworks for building custom systems**: Combine **DeviceFarmer STF** or **Appium Device Farm** with **scrcpy / ws-scrcpy**, **go-ios / WebDriverAgent**, and **Docker-Android** alongside **Appium Inspector** for a self-hosted, BrowserStack-like interactive real device cloud.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Self-hosted real device farms require proper physical thermal/battery management (smart USB hubs, battery charge limiters) to prevent device swelling.

- Remote device labs must enforce strict session cleanup, app data wiping, network isolation, and access controls between test runs.



---
