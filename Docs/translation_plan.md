## 一、HAL库

### 1. 第一优先级系列

| 系列      | 代表型号                                | 官方系列页                                                                      | 官方固件包名      | GitHub 仓库                                         | 推荐翻译内容           | 优先级 |
| ------- | ----------------------------------- | -------------------------------------------------------------------------- | ----------- | ------------------------------------------------- | ---------------- | --- |
| STM32F1 | STM32F103C8T6 / F103RCT6            | https://www.st.com/en/microcontrollers-microprocessors/stm32f1-series.html | STM32CubeF1 | https://github.com/STMicroelectronics/STM32CubeF1 | StdPeriph、HAL、LL | 最高  |
| STM32F4 | STM32F407VGT6 / F429IGT6 / F411CEU6 | https://www.st.com/en/microcontrollers-microprocessors/stm32f4-series.html | STM32CubeF4 | https://github.com/STMicroelectronics/STM32CubeF4 | HAL、LL           | 最高  |
| STM32G0 | STM32G030 / G070 / G071             | https://www.st.com/en/microcontrollers-microprocessors/stm32g0-series.html | STM32CubeG0 | https://github.com/STMicroelectronics/STM32CubeG0 | HAL、LL           | 高   |
| STM32L4 | STM32L431 / L476                    | https://www.st.com/en/microcontrollers-microprocessors/stm32l4-series.html | STM32CubeL4 | https://github.com/STMicroelectronics/STM32CubeL4 | HAL、LL           | 高   |
| STM32H7 | STM32H743 / H750                    | https://www.st.com/en/microcontrollers-microprocessors/stm32h7-series.html | STM32CubeH7 | https://github.com/STMicroelectronics/STM32CubeH7 | HAL、LL           | 高   |

---

### 2. 第二优先级系列

| 系列      | 代表型号                   | 官方系列页                                                                      | 官方固件包名      | GitHub 仓库                                         | 推荐翻译内容         | 优先级 |
| ------- | ---------------------- | -------------------------------------------------------------------------- | ----------- | ------------------------------------------------- | -------------- | --- |
| STM32F0 | STM32F030F4P6 / F051R8 | https://www.st.com/en/microcontrollers-microprocessors/stm32f0-series.html | STM32CubeF0 | https://github.com/STMicroelectronics/STM32CubeF0 | HAL、LL         | 中高  |
| STM32F3 | STM32F303              | https://www.st.com/en/microcontrollers-microprocessors/stm32f3-series.html | STM32CubeF3 | https://github.com/STMicroelectronics/STM32CubeF3 | HAL、LL、部分标准库资料 | 中   |
| STM32F7 | STM32F746 / F767       | https://www.st.com/en/microcontrollers-microprocessors/stm32f7-series.html | STM32CubeF7 | https://github.com/STMicroelectronics/STM32CubeF7 | HAL、LL         | 中高  |
| STM32G4 | STM32G431 / G474       | https://www.st.com/en/microcontrollers-microprocessors/stm32g4-series.html | STM32CubeG4 | https://github.com/STMicroelectronics/STM32CubeG4 | HAL、LL         | 中高  |
| STM32L0 | STM32L051              | https://www.st.com/en/microcontrollers-microprocessors/stm32l0-series.html | STM32CubeL0 | https://github.com/STMicroelectronics/STM32CubeL0 | HAL、LL         | 中   |
| STM32L1 | STM32L152              | https://www.st.com/en/microcontrollers-microprocessors/stm32l1-series.html | STM32CubeL1 | https://github.com/STMicroelectronics/STM32CubeL1 | HAL、LL         | 中   |
| STM32L5 | STM32L552              | https://www.st.com/en/microcontrollers-microprocessors/stm32l5-series.html | STM32CubeL5 | https://github.com/STMicroelectronics/STM32CubeL5 | HAL、LL         | 中   |
| STM32U5 | STM32U585              | https://www.st.com/en/microcontrollers-microprocessors/stm32u5-series.html | STM32CubeU5 | https://github.com/STMicroelectronics/STM32CubeU5 | HAL、LL         | 中   |

---

### 3. 无线/专用系列

| 系列      | 代表型号      | 官方系列页                                                                      | 官方固件包名      | GitHub 仓库                                         | 推荐翻译内容           | 优先级 |
| ------- | --------- | -------------------------------------------------------------------------- | ----------- | ------------------------------------------------- | ---------------- | --- |
| STM32WB | STM32WB55 | https://www.st.com/en/microcontrollers-microprocessors/stm32wb-series.html | STM32CubeWB | https://github.com/STMicroelectronics/STM32CubeWB | HAL、LL、无线协议相关说明  | 按需  |
| STM32WL | STM32WL55 | https://www.st.com/en/microcontrollers-microprocessors/stm32wl-series.html | STM32CubeWL | https://github.com/STMicroelectronics/STM32CubeWL | HAL、LL、LoRa/无线说明 | 按需  |

---

## 二、标准外设库

> 说明：
> 
> - 标准库属于 ST 历史方案
> - 建议通过 **ST 官网搜索** 获取，并将压缩包、本地版本号、发布日期单独归档
> - 对翻译而言，**F1 标准库最值得优先做**

| 系列      | 建议搜索关键词                                          | 官方搜索入口                                           | 推荐程度 | 备注         |
| ------- | ------------------------------------------------ | ------------------------------------------------ | ---- | ---------- |
| STM32F1 | `STM32F10x Standard Peripheral Library`          | https://www.st.com/content/st_com/en/search.html | 最高   | 标准库翻译首选    |
| STM32F4 | `STM32F4xx DSP and Standard Peripherals Library` | https://www.st.com/content/st_com/en/search.html | 高    | 有历史价值      |
| STM32F4 | `STM32F4xx_DSP_StdPeriph_Lib`                    | https://www.st.com/content/st_com/en/search.html | 高    | 常见包名关键词    |
| STM32F0 | `STM32F0xx Standard Peripheral Library`          | https://www.st.com/content/st_com/en/search.html | 中    | 如需要再归档     |
| STM32F3 | `STM32F30x Standard Peripheral Library`          | https://www.st.com/content/st_com/en/search.html | 中    | 模拟/控制方向可考虑 |

---