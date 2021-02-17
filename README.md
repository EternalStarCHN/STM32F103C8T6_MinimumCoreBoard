# STM32F103C8T6最小系统核心板介绍
 本仓库用于存放STM32F103C8T6单片机最小系统核心板的PCB文件，
 硬件部分的原理图与PCB均使用[Altium Designer 19](https://www.altium.com.cn/)设计和绘制。  
 所需元件如下：
 | Comment       | Description             | Designator                 | Footprint       |
|---------------|-------------------------|----------------------------|-----------------|
| 1uF/0603      | 无极性电容                   | C1, C4, C11, C12, C13, C14 | 0603C           |
| 10uF/0603     | 无极性电容                   | C2                         | 0603C           |
| 0.1uF/0603    | 无极性电容                   | C3, C8                     | 0603C           |
| 22nF/0603     | 无极性电容                   | C5                         | 0603C           |
| 22pF/0603     | 无极性电容                   | C6, C7, C9, C10            | 0603C           |
| LEDR/0805     |                         | D1                         | LED-0805R       |
| LEDY/0805     |                         | D2                         | LED-0805Y       |
| Header 3X2    | Header, 3-Pin, Dual row | P1                         | HDR-3X2         |
| Header 20     | Header, 20-Pin          | P2, P3                     | HDR1X20         |
| SWD           | Header, 4-Pin           | P4                         | HDR-1X4_H       |
| 10K/0603      |                         | R1, R3, R4                 | 0603R           |
| 510R/0603     |                         | R2, R5                     | 0603R           |
| 1M/0603       |                         | R6                         | 0603R           |
| 20R/0603      |                         | R7, R8                     | 0603R           |
| 4.7K/0603     |                         | R9                         | 0603R           |
| SW-PB_V       | SWITCH                  | SW1                        | TSW SMD-3*6*2.5 |
| RT9193        |                         | U1                         | SOT23-5L        |
| STM32F103C8T6 |                         | U2                         | TQFP48 7x7_L    |
| Micro-USB     |                         | USB1                       | USB-micro_B     |
| 32.768K       | Crystal Oscillator      | Y1                         | MC-306          |
| 8M            | Crystal Oscillator      | Y2                         | XTAL-49S DIP    |  
# License
STM32F103C8T6_MinimumCoreBoard is Licensed under [BSD-3-Clause License](https://github.com/EternalStarCHN/STM32F103C8T6_MinimumCoreBoard/blob/main/LICENSE).
