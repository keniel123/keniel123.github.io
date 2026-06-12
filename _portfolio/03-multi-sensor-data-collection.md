---
title: "Multi-Sensor Data Collection (Radar + Azure Kinect)"
excerpt: "A modular GUI that synchronises TI mmWave radar with Azure Kinect RGB-D recording for labelled human-activity data collection."
collection: portfolio
permalink: /portfolio/multi-sensor-data-collection/
---

Collecting labelled multimodal human-sensing data is fiddly: multiple sensors, different SDKs, different clocks. This tool makes it repeatable — a modular GUI that **synchronises TI mmWave radar (AWR2243) captures with Azure Kinect RGB-D recordings** and structures the output for downstream labelling and training.

It underpins the multimodal datasets used in my PhD research on radar-based human activity recognition.

**Details**

* Synchronised capture across TI mmWave Studio (driven via a Lua TCP bridge) and the Azure Kinect SDK
* Structured, labelled recording sessions for repeatable experiments
* Built with Python, PySimpleGUI, and OpenCV

**Code:** [github.com/keniel123/multi-sensor-data-collection](https://github.com/keniel123/multi-sensor-data-collection)
