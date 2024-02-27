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
|      |                                    |                |                 | Eye Tracker                                                                                                         | Screen                                                                                      |
|------|------------------------------------|--------------- |-----------------|:-----------------------------------------|-------------------------------------|-----------------------------------:|:-------------------------------------------------------------------------------------------:|
|      | \textbf{Author(s)}                 | Year           | Venue           | Company                                  | Device                              | Freq. [Hz]                         | Inch                              | Aspect Ratio    | Distance [cm]                         |
| S01  | \citet{foster2017alpha}            | 2017           | Psychol Sci.    | EyeLink                                  | 1000 Plus                           | 1000                               | 17                                | 16:9            | 100                                   |
| S02  | \citet{marzecova2017interrelation} | 2017           | Biolo. Psychol  | EyeLink                                  | 1000                                | 500                                | 19                                | 4:3             | 57                                    |
| S03  | \citet{krstic2018all}              | 2018           | EJPE            | SMI                                      | RED-m                               | 60                                 | 15.6                              | 16:9            | 60                                    |
| S04  | \citet{marzecova2018attentional}   | 2018           | Scientific Rep. | EyeLink                                  | 1000                                | 500                                | 19                                | 4:3             | 57                                    |
| S05  | \citet{schuetz2019explanation}     | 2019           | ACM CHI         | EyeLink                                  | 1000 Plus                           | 1000                               | 113                               | 8:5             | 180                                   |
| S06  | \citet{annerer2021reliably}        | 2021           | Cogn. Sci.      | SMI                                      | RED250                              | 250                                | 24                                | 16:9            | 70                                    |
| S07  | \citet{felssberg2018effect}        | 2022           | Vision Res.     | EyeLink                                  | 1000 Plus                           | 1000                               | 27                                | 16:9            | 85                                    |
| S08  | \citet{hollenstein2022the}         | 2022           | LREC            | EyeLink                                  | 1000 Plus                           | 1000                               | 27                                | 16:9            | 85                                    |
| VR01 | \citet{stein2022eye}               | 2022           | IEEE VR         | Tobii                                    | Pro                                 | 90                                 | 3.5                               | 9:10            | -                                     |
| VR02 | \citet{steil2019privacy}           | 2019           | ACM ETRA        | Pupil Labs                               | Add-on                              | 30                                 | 5.7                               | 8:9             | -                                     |
| M01  | \citet{steil2018fixation}          | 2018           | ACM ETRA        | Pupil Labs                               | Pro                                 | 30                                 | -                                 | -               | -                                     |


<br>
<p>
Our recommentations apply independently of sampling frequency and type of eye tracker.
</p>
