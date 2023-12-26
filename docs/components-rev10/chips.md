---
sidebar_position: 20
sidebar_label: 'Chips'
---

# Chips

![](./img/chips2.jpg)

## Microcontroller RP2040 QFN-56

|**Reference**|**Package**|**Value**|**Quantity**|**Rating**|**Note**|
|-|-|-|-|-|-|
|U103|QFN-56|RP2040 | 1  ||

Raspberry Pi RP2040 microcontroller in QFN-56 package.

## Flash 128Mbit SPI SOIC8-208mil

|**Reference**|**Package**|**Value**|**Quantity**|**Rating**|**Note**|
|-|-|-|-|-|-|
|U102  |SOIC8-208mil|128Mbit SPI/QSPI flash (W25Q128JVSIQ)  |1  ||

128Mbit SPI flash in SOIC8-208mil package, QSPI support required.

*   [W25Q128JVSIQ](https://item.szlcsc.com/98729.html)
*   [XM25QH128A](https://item.szlcsc.com/308377.html)

## NAND Flash 1Gbit SPI UPDFN-8

|**Reference**|**Package**|**Value**|**Quantity**|**Rating**|**Note**|
|-|-|-|-|-|-|
| | UPDFN-8 | 1Gbit SPI NAND flash (MT29F1G01ABAFDWB-IT:F)  |1  ||

1Gbit SPI NAND flash with EEC in UPDFN-8 package. Larger sizes (up to 8Gbit) are available, but are not currently supported.

* [MT29F1G01ABAFDWB-IT:F](https://item.szlcsc.com/3176239.html)


## 74LVC1T45 bi-directional buffer SC70-6/SOT363

|**Reference**|**Package**|**Value**|**Quantity**|**Rating**|**Note**|
|-|-|-|-|-|-|
|U301 U302 U303 U304 U305 U306 U307 U308|SC70-6/SOT363|74LVC1T45  |8  ||

74LVC1T45 is available from TI, Nexperia and Diodes INC. The TI version (SN74LVC1T45DCK) seems to be the most common in the Chinese market.

We are currently using logic chips from WuXi I-Core due to price and availability.

*   [74LVC1T45DW-7](https://item.szlcsc.com/180239.html) (Diodes INC)
*   [74LVC1T45GW,125](https://item.szlcsc.com/485235.html) (Nexperia)
*   [SN74LVC1T45DCK](https://item.szlcsc.com/9911.html) (TI) 

## CD4067 analog mux TSSOP-24

|**Reference**|**Package**|**Value**|**Quantity**|**Rating**|**Note**|
|-|-|-|-|-|-|
|U402|TSSOP-24|CD4067 |1  ||tPHL ~30ns (60ns max) @ 5V |

Multiple manufacturers make an updated CD4067 that is much faster than old CD logic, and even faster than 74HC/74HCT. The high to low (and low to high) propagation delay should be in the neighborhood of 30ns (60ns max) at 5 volts.

We are currently using logic chips from WuXi I-Core due to price and availability.

:::tip
74HC4067 or 74HCT4067 can be used, but CD4067 is much cheaper and more available. Just be sure that the CD4067 is an updated version, not an original 1970-1990 vintage part.
:::

Example:

*   [CD4067](https://item.szlcsc.com/8436782.html) (HG Semi)
*   [CD4067](https://item.szlcsc.com/8414592.html) (I-Core)

## 74HC595 shift register TSSOP-16

|**Reference**|**Package**|**Value**|**Quantity**|**Rating**|**Note**|
|-|-|-|-|-|-|
|U501, U502|TSSOP-16|74HC595  |2  ||

**Must** be the "**HC**" version. The "HCT" version will **NOT** work. Any manufacturer.

We are currently using logic chips from WuXi I-Core due to price and availability.

:::warning
Must use "HC" version  
:::

Example:

*   [74HC595T16-13](https://item.szlcsc.com/159448.html) (Diodes INC)
*   [74HC595PW,118](https://item.szlcsc.com/6414.html) (Nexperia)

## 74HCT245 bus transceiver TSSOP-20

|**Reference**|**Package**|**Value**|**Quantity**|**Rating**|**Note**|
|-|-|-|-|-|-|
|U503|TSSOP-20|74HCT245  |1  ||

**Must** be the "**HCT**" version. The "HC" version will **NOT** work. Any manufacturer.

We are currently using logic chips from WuXi I-Core due to price and availability.

:::warning
Must use "HCT" version  
:::

Example:

*   [SN74HCT245PWR](https://item.szlcsc.com/7251.html "SN74HCT245PWR ") (TI)
*   [74HCT245PW,118](https://item.szlcsc.com/6446.html "74HCT245PW,118 ") (Nexperia)
