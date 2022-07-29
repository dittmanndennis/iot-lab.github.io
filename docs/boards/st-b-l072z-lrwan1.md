---
board: ST B-L072Z-LRWAN1
group: boards
---

The [B-L072Z-LRWAN1](https://www.st.com/en/evaluation-tools/b-l072z-lrwan1.html)
board is LoRa capable board running on ab ARM CortexM0+ STM32L072CZ
microcontroller.

<div style="text-align:center">
<img src="{{ '/assets/images/docs/boards/lrwan1/' | relative_url}}lrwan1.jpg" style="width:50%;"/>
</div>

It is possible to reset, debug and program the ARM Cortex M0 through the
embedded debugger (ST-LINK) connected to the gateway USB port. This component
also allows a UART connection to the M0.

## IoT-LAB special configuration

The serial connection baudrate should be configured at **115200 bauds** in the
firmware and use `USART2` on pins `PA3` (RX) and `PA2` (TX).

## Schematics and Datasheets

The board datasheet is available [<i class="far fa-file-pdf"/>&nbsp;here](https://www.st.com/resource/en/user_manual/dm00329995.pdf).

The cpu datasheet is available [<i class="far fa-file-pdf"/>&nbsp;here](https://www.st.com/resource/en/datasheet/stm32l072cz.pdf).

## Sensors extension

Nodes are deployed with Sensor Expansion Board for STM32 Nucleo Board: [ST X-NUCLEO-IKS01A2](https://www.st.com/en/ecosystems/x-nucleo-iks01a2.html) & [ST X-NUCLEO-IKS01A3](https://www.st.com/en/ecosystems/x-nucleo-iks01a3.html)

Nodes equipped with the **ST X-NUCLEO-IKS01A2**:
* Saclay site (st-lrwan1-1 to st-lrwan1-25)
* Lille site (st-lrwan1-1 to st-lrwan1-2)

Nodes equipped with the **ST X-NUCLEO-IKS01A3**:
* Lille site (st-lrwan1-3 to st-lrwan1-5)

The **ST X-NUCLEO-IKS01A2** shield gives access to external sensors to the nodes:
  * a temperature and humidity sensor
    [<i class="far fa-file-pdf"/>&nbsp;HTS221](https://www.st.com/resource/en/datasheet/hts221.pdf)
  * an atmospheric pressure sensor
    [<i class="far fa-file-pdf"/>&nbsp;LPS22HB](https://www.st.com/resource/en/datasheet/dm00140895.pdf)
  * an accelerometer sensor
    [<i class="far fa-file-pdf"/>&nbsp;LSM6DSL](https://www.st.com/resource/en/datasheet/lsm6dsl.pdf)
  * an accelerometer sensor
    [<i class="far fa-file-pdf"/>&nbsp;LSM303AGR](https://www.st.com/resource/en/datasheet/lsm303agr.pdf)

The **ST X-NUCLEO-IKS01A3** shield gives access to external sensors to the nodes:
  * a temperature and humidity sensor
    [<i class="far fa-file-pdf"/>&nbsp;HTS221](https://www.st.com/resource/en/datasheet/hts221.pdf)
  * a temperature sensor
    [<i class="far fa-file-pdf"/>&nbsp;STTS751](https://www.st.com/resource/en/datasheet/stts751.pdf)
  * an atmospheric pressure sensor
    [<i class="far fa-file-pdf"/>&nbsp;LPS22HH](https://www.st.com/resource/en/datasheet/lps22hh.pdf)
  * a 3-axis accelerometer + 3-axis gyroscop sensor
    [<i class="far fa-file-pdf"/>&nbsp;LSM6DSO](https://www.st.com/resource/en/datasheet/lsm6dso.pdf)
  * a 3-axis magnetometer sensor
    [<i class="far fa-file-pdf"/>&nbsp;LIS2MDL](https://www.st.com/resource/en/datasheet/lis2mdl.pdf)
  * a 3-axis accelerometer sensor
    [<i class="far fa-file-pdf"/>&nbsp;LIS2DW12](https://www.st.com/resource/en/datasheet/lis2dw12.pdf)
