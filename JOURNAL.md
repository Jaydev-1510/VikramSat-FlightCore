---
Title: "VikramnSat FlightCore"
Author: "@ErR0r151O"
Description: "🚀C&DH + OBC for VikramSat🛰️"
Created On: "3/09/2025"
---

## September 3rd: Started the project!
### Day-01

Today I spent my time making a beautiful footprint for RP2354B-A4. Yeah, I have chosen the new RP2350B as the microprocessor for this board. Also, ICM-20948 as an IMU is finalised. I will not be able to keep up regularly as my exams are approaching, however I will try to accomplish something everyday. Here an image of the schematic symbol that I made today- 

![RP2354B-A4 schematic symbol](https://github.com/user-attachments/assets/a033ed5c-6ef1-456e-9733-cec55a5d3120)

### Time Spent: 1h

---

## September 10th: Decoupling capacitors
### Day-02

Not much work done today. Exams are still going on... However, I have added decoupling capacitors to RP2354B-A4. Also, I have decided to change the model of RP2350B-A4 to RP2354B-A4. This is so because I have a new storage plan. Here is the new plan to this table:

|    **Type**    | **Size** |                          **Use**                          |
|:--------------:|:--------:|:---------------------------------------------------------:|
| Internal Flash | 2MB      | Bootloader and FreeRTOS                                   |
| External Flash | 16MB     | Main firmware, logs and other files                       |
| FRAM/MRAM      | 16MB     | Support for OTA update, image compression and other tasks |
| SD Card        | TBD      | Shared GoPro for image storage                            |

### Time Spent: 30m

---
