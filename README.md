# DewHeater-TM

This project aims to develop an open source, simple and reliable controller for a telescope dew heater.

## Self-proposed timeline

```mermaid

gantt
dateFormat  YYYY-MM-DD
%%title       TIMELINE
excludes    weekends
%% (`excludes` accepts specific dates in YYYY-MM-DD format, days of the week ("sunday") or "weekends", but not the word "weekdays".)

section HW Design
    Schematic                           :active, des1, 2024-08-01, 2024-08-15
    PCB Layout                          :des2, 2024-08-10, 2024-08-25
    Enclosure design                    :des3, 2024-08-16, 2024-08-25
    
section SW Design
    FW Design                           :des5, 2024-08-25, 2024-09-10
    Driver design                       :des6, 2024-09-05, 2024-09-20

section LAB Tests
    HW Tests                            :des7, 2024-09-20, 2024-10-10
    Enclosure Tests                     :des4, 2024-09-25, 2024-10-10
    SW Tests                            :des8, 2024-09-30, 2024-10-15

section Integration
    Final integration                   :crit, dest10, 2024-10-05, 2024-10-20

section Documentation
    Documentation                       :2024-10-20, 2024-11-05

section Production?

```

> [!NOTE]
> This timeline is a draft, it should not be considered realistic or reliable.

The files in this repository are provided "as is", without warranty of any kind.



