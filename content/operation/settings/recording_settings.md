---
title: "Recording Settings"
date: 2020-07-11T23:44:31-07:00
draft: false
weight: 364
tags: ["features", "UI", "interface", "recording"]
categories: ["intra-op", "software"]
---

To access Recording options, click **Recording**.

{{< panel status="notice" title="NOTICE" >}}Recording settings cannot be changed while recording video.{{< /panel >}}

## Basic and Advanced

To set basic settings, click **Basic**. To set advanced settings, click **Advanced**.

![Recording Dialog Box (Basic Features Left, Advanced Features Right)](/images/sw_recording.svg)

{{< callout num="1" term="Movies Format buttons" desc="Saves video files as .avi or .mov files." >}}  
{{< callout num="2" term="Show Logo toggle switch" desc="Displays the system logo in the bottom-left corner during operation if Record DataFusion is disabled." >}}  
{{< callout num="3" term="Auto-Record toggle switch" desc="Automatically starts recording when a case starts." >}}  
{{< callout num="4" term="Record DataFusion toggle switch" desc="Includes overlay information from a connected device." >}}  
{{< callout num="5" term="Duration (min) toggle switch" desc="Sets a maximum time limit (in minutes) for individual recordings. NOTE: Recordings are not interrupted if the maximum duration is reached during a recording. Instead, the system creates a separate video file for additional video." >}}  
{{< callout num="6" term="Snapshots buttons" desc="Saves snapshots as either .jpg or .png files." >}}  
{{< callout num="7" term="Frame Rate slider" desc="Sets the frames per second for recorded video. Higher frame rates increase file size." >}}  
{{< callout num="8" term="Quality slider" desc="Sets the recorded video quality. Raise the slider to improve quality and increase the file size or lower the slider to decrease quality and decrease file size." >}}  
{{< callout num="9" term="Limit to 1080p toggle switch" desc="Saves video in 1920x1080 resolution." >}}  
{{< callout num="10" term="Raw Capture button" desc="Opens the Raw Capture dialog box." >}}  

## Raw Capture

This panel is intended for users conducting research projects. Capturing raw data from the system affects visualization. Utilize this function only with doctor approval.

{{< figure src="/images/sw_recording_raw_capture.svg" width="300px" >}}

{{< callout num="1" term="Microscope information" desc="Defines the microscope model, illumination percentage, and camera iris open percentage." >}}  
{{< callout num="2" term="Additional method information" desc="Enable the toggle switch for each method used in operation. If necessary, define the device model used and any additional requested information." >}}  
{{< callout num="3" term="Notes field" desc="Saves notes for the recording." >}}  
