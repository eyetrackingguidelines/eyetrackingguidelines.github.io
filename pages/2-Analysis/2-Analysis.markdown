---
layout: page
title: Analysis
permalink: /analysis/
author: Removed for blind review
nav_order: 5
has_children: true
---

## ANALYSIS
<br>
<p align="justify">

To use eye tracking in interactive systems to its fullest potential, we need to do pre-processing beyond the abilities of the current parsers. Even when included parsers mark blinks, certain artifacts remain in the data. Removing windows/trials/instances where blinks are present will significantly decrease available data and introduce a delay in interactive systems. As such, we recommend the following processing steps for eye-tracking data.
</p>

### Our analysis are applied on the following datasets
|      |                        |      |                 | Eye Tracker |           |            | Screen |              |               |
| ---- | ---------------------- | ---- | --------------- | :---------- | --------- | ---------: | :----: | ------------ | ------------- |
|      | Author(s)              | Year | Venue           | Company     | Device    | Freq. [Hz] |  Inch  | Aspect Ratio | Distance [cm] |
| S01  | Foster et al.          | 2017 | Psychol Sci.    | EyeLink     | 1000 Plus |       1000 |   17   | 16:9         | 100           |
| S02  | Marzecová et al.       | 2017 | Biolo. Psychol  | EyeLink     | 1000      |        500 |   19   | 4:3          | 57            |
| S03  | Krstić et al.          | 2018 | EJPE            | SMI         | RED-m     |         60 |  15.6  | 16:9         | 60            |
| S04  | Marzecová et al.       | 2018 | Scientific Rep. | EyeLink     | 1000      |        500 |   19   | 4:3          | 57            |
| S05  | Schuetz et al.         | 2019 | ACM CHI         | EyeLink     | 1000 Plus |       1000 |  113   | 8:5          | 180           |
| S06  | Annerer-Walcher et al. | 2021 | Cogn. Sci.      | SMI         | RED250    |        250 |   24   | 16:9         | 70            |
| S07  | Felßberg and Dombrowe  | 2022 | Vision Res.     | EyeLink     | 1000 Plus |       1000 |   27   | 16:9         | 85            |
| S08  | Hollenstein et al.     | 2022 | LREC            | EyeLink     | 1000 Plus |       1000 |   27   | 16:9         | 85            |
| VR01 | Stein et al.           | 2022 | IEEE VR         | Tobii       | Pro       |         90 |  3.5   | 9:10         | -             |
| VR02 | Steil et al.           | 2019 | ACM ETRA        | Pupil Labs  | Add-on    |         30 |  5.7   | 8:9          | -             |
| M01  | Steil et al.           | 2018 | ACM ETRA        | Pupil Labs  | Pro       |         30 |   -    | -            | -             |


<br>
<p>
Our recommentations apply independently of sampling frequency and type of eye tracker.
</p>
