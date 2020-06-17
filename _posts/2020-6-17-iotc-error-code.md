---
layout: post
title: Azure IoT Central publish device error code
categories: azure iot central error
date: 2020-06-17
---

Error Code: 400.470.006.319

#### Cause
This error occurs when an attempt to publish an interface in IoT Central that has no capabilities configured. More information can be found by using the Edge browser developer tools (F12) console.

![_config.yml]({{ site.baseurl }}/images/error_code_400_470_006_319.png)

#### Resolution
Add capabilities to the interface before publishing.
