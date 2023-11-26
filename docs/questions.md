---
title: Q&A
permalink: /questions
---

# Q&A
{:.no_toc}

Please post your question on the [discussions](https://github.com/dsoutw/dWidgets-Android/discussions) page if it is not answered here.

* Table of contents
{:toc}

## Widget

### Floating window

Q: How to move the expansion button?

A: After long pressing the expansion button, you can move the button by dragging it.

Q: Can I show the floating window on the lock screen?

A: No, this feature is not supported at this moment.

### Notification

Q: Which devices can show the widgets on the lock screen?
{: #widget-notification-lockScreen}

A: This feature is supported on devices that can display notifications on the lock screen. Known supported devices:
* Google Pixel 4a (5G)

Please report [here](https://github.com/dsoutw/dWidgets-Android/discussions/35) if your device is not on the list.

## Rule

Q: If I apply two or multiple rules to one widget, when will the app display the widget?

A: Multiple rules are manipulated according to the **"or"** logic. This means that
* the app will **show** the widget when the conditions in **one** of the rules are **fulfilled**, and
* the app will **hide** the widget when the conditions in **all** of the rules are **not satisfied**.

### WiFi rule

Q: Why does enabling a WiFi rule requires to grant the application the location permission?

A: Knowing the names of your srounding WiFi hotsopts gives the app a clue of your current location. Thus, the permission is required by the system to scan your WiFi. Please visit "[Wi-Fi scanning overview](https://developer.android.com/develop/connectivity/wifi/wifi-scan#wifi-scan-permissions)" for details.