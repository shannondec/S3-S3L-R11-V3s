# S3-S3L-R11-V3s-Peripheral-different




#### 1: package
note:-
|  S3 | S3L | R11 | v3s |
| ---- | ---- | ---- | ---- |
|  FBGA234  | FBGA234 | TQFP128 | TQFP128 |


#### 2: ram
note: ：only S3 sip DDR3
|  S3 | S3L | R11 | v3s |
| ---- | ---- | ---- | ---- |
| DDR3 128MB | DDR2 64MB |DDR2 64MB|DDR2 64MB|

#### 3: ephy
note: only R11 is none
|  S3 | S3L | R11 | v3s |
| ---- | ---- | ---- | ---- |
| 100M | 100M | none | 100M |

#### 4: PortB
AF: UART2，PWM0-1，TWI0-1
note: R11 and V3S lost the high bit of PortB, Alternate function did not change
|  S3 | S3L | R11 | v3s |
| ---- | ---- | ---- | ---- |
| 14pin  | 14pin | 11pin | 10pin |

#### 5: PortC
Alternate: SDC2(8Bit)，SPI0
note: R11 and V3S lost the high server bit of SDC2
|  S3 | S3L | R11 | v3s |
| ---- | ---- | ---- | ---- |
| 11pin | 11pin | 4pin | 4pin | 

#### 6: PortD
AF: RGB LVDS RGMII or RMII
Note: only v3s lost PortD
|  S3 | S3L | R11 | v3s |
| ---- | ---- | ---- | ---- |
| 22pin | 22pin | 22pin | none | 

#### 7: PortE
AF: CSI RGB TWI1 or UART1
Note:only R11 lost RGB
|  S3 | S3L | R11 | v3s |
| ---- | ---- | ---- | ---- |
| 25pin | 25pin | 18pin | 25pin | 

#### 8: PortF
AF: SDC0 or JTAG or UART0
Note: only R11 lost PF6（GPIO）
|  S3 | S3L | R11 | v3s |
| ---- | ---- | ---- | ---- |
| 7pin | 7pin | 6pin | 7pin | 

#### 9: PortG
AF: SDC1、UART1、PCM
Note: R11 lost SDC1 ,v3s lost UART1 and PCM
|  S3 | S3L | R11 | v3s |
| ---- | ---- | ---- | ---- |
| 14pin | 14pin | 8pin | 6pin | 

#### 10: LRADC
Note: channel
|  S3 | S3L | R11 | v3s |
| ---- | ---- | ---- | ---- |
| 2 | 2 | 2 | 1 | 

#### 11: Built-in codec
Note: codec
|  S3 | S3L | R11 | v3s |
| ---- | ---- | ---- | ---- |
| Li Lo HP MICin | Li Lo HP MICin |  Lo MICin | HP MICin | 

#### 12: MIPI-CSI
Note: MIPI CAMERE
|  S3 | S3L | R11 | v3s |
| ---- | ---- | ---- | ---- |
| 1 | 1 |  1 | 1 |
