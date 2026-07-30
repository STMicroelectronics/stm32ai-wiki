# How to deploy your AI model on STM32N6 - assets

Assets for the **"How to deploy your AI model on STM32N6"** tutorial of the
STMicroelectronics Edge AI documentation:
<https://dev.st.com/edge-ai-docs/general/latest/en/docs/tutorials/how-to-deploy-ai-model-stm32n6-neural-art.html>

## Contents

- `STM32N6570-DK_AI_Application.ioc` - STM32CubeMX configuration file used in the
  tutorial. Open it directly in STM32CubeMX to reproduce the base firmware
  project (FSBL + Appli) without redoing the manual configuration steps.

## Target and tooling

| Item              | Value                                   |
|:------------------|:----------------------------------------|
| Reference board   | STM32N6570-DK                           |
| Device            | STM32N6 (Neural-ART NPU)               |
| Boot / exec mode  | Execute in Place (XIP)                  |
| STM32CubeMX       | 6.17.0 or later                         |
| STM32CubeN6       | 1.3.0 or later                          |
| STM32CubeIDE      | 2.0.0 or later                          |

## Usage

1. Download `Test_CubeAIStudio_Mobilenet_050526.ioc`.
2. Open it in STM32CubeMX and generate the code.
3. Follow the tutorial from Part 3 to integrate the AI model files.

The AI model itself is not included: obtain a compatible model from the
[STM32 Model Zoo](https://github.com/STMicroelectronics/stm32ai-modelzoo).

## License

Provided under the **BSD-3-Clause** license. See the repository-level
[License.md](../../License.md).
