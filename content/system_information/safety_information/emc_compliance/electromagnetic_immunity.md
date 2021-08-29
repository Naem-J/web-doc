---
title: "Guidance and Manufacturer Declaration - Electromagnetic Immunity"
date: 2021-07-25T22:38:19-07:00
draft: false
weight: 1334
tags: ["emc", "electromagnetic", "immunity", "iec 61000"]
categories: ["introduction", "safety"]
---

The NGENUITY&trade; system is intended for use in the electromagnetic environments specified below. The customer or the user of the NGENUITY&trade; system should assure it is used in such an environment.

| Immunity Test | IEC 60601 Test and Compliance Level | Electromagnetic Environment - Guidance |
| --- | --- | --- | --- |
| Electrostatic Discharge (IEC 61000-4-2) | +/-8 kV contact, +/-15 kV air | Floors should be wood, concrete, or ceramic tile. If floors are covered with synthetic material, the relative humidity should be at least 30%. |
| Electrical Fast Transient/Burst (IEC 61000-4-4) | +/-2 kV on power supply lines, +/- kV on input/output lines | Mains power quality should be that of a typical commercial or hospital environment. |
| Surge (IEC 61000-4-5) | +/- kV Differential Mode | Mains power quality should be that of a typical commercial or hospital environment. |
| Power Frequency (50/60 Hz) Magnetic Fields (IEC 61000-4-8) | 30 A/m, 50 or 60 Hz | Power frequency magnetic fields should be at levels characteristic of a typical location in a typical commercial or hospital environment. |
| Voltage Dips, Short Interrupts, and Variations on Power Supply Line (IEC 61000-4-11) | 0% U<sub>T</sub> for 0.5 cycle at 0&deg;, 45&deg;, 90&deg;, 135&deg;, 180&deg;, 225&deg;, 270&deg;, and 315&deg;. 0% U<sub>T</sub> for 1 cycle. 70% U<sub>T</sub> for 25/30 cycles. 0% U<sub>T</sub> for 250/300 cycles. | Mains power quality should be that of a typical commercial or hospital environment. If the user of the system requires continued operation during power mains interruptions, it is recommended that the system be powered from an uninterruptible power supply or a battery. |
| Conducted RF (IEC 61000-4-6) | 3 Vrms, 150 kHz to 80 MHz. 6 Vrms at ISM frequencies | The ISM (industrial, scientific and medical) bands between 150 kHz and 80 MHz are 6.765 MHz to 6.795 MHz; 13.553 MHz to 13.567 MHz; 26.957
MHz to 27.283 MHz; and 40.66 MHz to 40.70 MHz. |
| Radiated RF (IEC 61000-4-3), Proximity Fields from RF wireless communication equipment (IEC 61000-4-3) | 3 V/m, 80 MHz to 2.7 GHz (see following table) | Since IEC 60601-1-2 Edition 2.1 and Edition 3 were developed, new digital wireless technologies have been introduced not only to hospitals, but are also in widespread use by the general public. In addition, existing technologies are being used in ways that they were not used before. The IMMUNITY TEST LEVELS specified in the table were calculated using the following equation: E=(6√P)/d. Where P is the maximum power in W, d is the minimum separation distance in m, and E is the Immunity Test Level in V/m. The factor of 6 is a compromise for a range of antenna factors, to simplify the test. |

| Frequency (MHz) | Level (V/m) |
| --- | --- |
| 385 | 27 |
| 450 | 28 |
| 710, 745, 780 | 9 |
| 810, 870, 930 | 28 |
| 1720, 1845, 1970 | 28 |
| 2450 | 28 |
| 5240, 550, 5785 | 9 |

{{< panel status="notice" title="NOTICE" >}}U<sub>T</sub> is the AC mains voltage prior to application of the test level. The compliance levels in the ISM frequency range 150 kHz to 2.5 GHz are intended to decrease the likelihood that mobile or portable communications equipment could cause interference if it is inadvertently brought into the patient area. However, Emission limits, IEC 60601 Test Levels, and tests specified in IEC 60601-1-2:2001 do not address Electromagnetic Compatibility of electrical equipment at very close distances. Care should always be exercised when using any electrical or RF equipment in the immediate patient area.{{< /panel >}}

{{< panel status="warning" title="WARNING" >}}Portable RF communications equipment (including peripherals such as antenna cables and external antennas) should be used no closer than 30 cm (12 inches) to any part of the NGENUITY™ system including cables specified by the manufacturer. Otherwise, degradation of the performance of this equipment could result.{{< /panel >}}
