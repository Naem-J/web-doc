---
title: "Monitor"
date: 2020-07-11T23:47:47-07:00
draft: false
weight: 3683
tags: ["features", "UI", "interface", "primary", "camera", "displays"]
categories: ["intra-op", "software"]
---

The monitor system settings have adjustable settings for displays connected to the system. To access Monitor options, click **Monitor**.

### Basic Monitor Settings

{{< panel status="warning" title="WARNING" >}}Only the provided monitor should be used as the Primary Monitor.{{< /panel >}}


![Monitor Dialog Box (3D Format Locked)](/images/sw_system_settings_monitor_locked.svg)

{{< callout num="1" term="Monitor drop-down menu" desc="Selects a display." >}}  
{{< callout num="2" term="Primary Monitor toggle switch" desc="Sets the selected display to the primary display." >}}  
{{< callout num="3" term="View drop-down menu" desc="Sets the content on the screen. Select one of the following:" >}}  
  * **Control** - Displays the user interface and system camera image.  
  * **Surgery** - Displays a limited subset of the user interface and system camera image.  
  * **Camera Only** - Displays the system camera image only.  


{{< callout num="4" term="3D Format lock button" desc="Unlocks the 3D format options." >}}  

To edit 3D formatting, click the **Unlock** button.

![3D Format Options](/images/sw_system_settings_monitor_unlocked.svg)

{{< callout num="1" term="Format drop-down menu" desc="Sets the monitor 3D format. Select Monoscopic for 2D displays, Top-Bottom for LG displays, or Row-Interleaved for 55″ FSN displays." >}}
{{< callout num="2" term="Swap 3D button" desc="Swaps the stereoscopic polarity of the display. Display information displays on the left side of the screen. The information helps identify the display and evaluate if the display is working properly." >}}

### Add Monitor

The Add Monitor panel displays after connecting a new monitor to the system.

![Add Monitor Dialog Box](/images/sw_system_settings_add_monitor.svg)

To add a monitor, perform the following:

1. In the **3D Format** drop-down menu, select a format (see 3D Format Options on page 52).
2. In the Polarity panel, select one of the following:
  * **Normal** – Renders left and then right stereoscopic images.
  * **Swap** – Renders right and then left stereoscopic images.

### 3D Polarity

To determine if the 3D monitor has the correct polarity, perform the following:

1. Put on the 3D glasses.
2. Close your right eye.
3. Verify you can only see the “Left” on-screen text.
4. Repeat the process with the other eye and verify that you only see the “Right” on-screen text.
