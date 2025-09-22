---
title: "Powershell: WebView2Runner"
---

Sometimes you want to start a WebApp as a desktop application. Fortunately, Chromium/Edge is available as a browser engine for this - called WebView2. To keep the use as simple and universal as possible, here is this Powershell script and the necessary information.

Today you can start a WebApp as a BowserApp with a manifest file. With this script you are able to start your application in foreground and full screen mode and intercept certain key combinations. This enables you to start your WebApp in kiosk mode. 

At the moment this script is only useful for Windows. But if WebView2 is also available for other OS, it should not be a problem to transfer the implementation to other OS.

Example usage und more information [on the github project page](https://github.com/cieszynski/WebView2Runner.ps1).