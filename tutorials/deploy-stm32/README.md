# How to deploy your AI model on mainstream STM32 - assets

Assets for the **"How to deploy your AI model on mainstream STM32"** tutorial of
the STMicroelectronics Edge AI documentation:
<https://dev.st.com/edge-ai-docs/general/latest/en/docs/tutorials/how-to-deploy-ai-model-stm32-mainstream.html>

## Contents

- `B-U585I-IOT02A_AI_Application.ioc` - STM32CubeMX configuration file used in
  the tutorial. Open it directly in STM32CubeMX to reproduce the base firmware
  project without redoing the manual configuration steps.

## Target and tooling

| Item              | Value                                   |
|:------------------|:----------------------------------------|
| Reference board   | B-U585I-IOT02A                          |
| Device            | STM32U5 (Cortex-M33, software inference)|
| STM32CubeMX       | 6.17.0 or later                         |
| STM32CubeU5       | 1.8.0 or later                          |
| STM32CubeIDE      | 2.0.0 or later                          |
| STM32Cube AI Studio | 1.2.0 or later                        |
| ST Edge AI Core   | 4.0.0 or later                          |

## Usage

1. Download `Arc_Fault_Detection_U5.ioc`.
2. Open it in STM32CubeMX and generate the code.
3. Follow the tutorial from Part 3 to integrate the AI model files.

The AI model itself is not included: obtain a compatible model from the
[STM32 Model Zoo](https://github.com/STMicroelectronics/stm32ai-modelzoo).

## License

Provided under the **BSD-3-Clause** license. See the repository-level
[License.md](../../License.md).
