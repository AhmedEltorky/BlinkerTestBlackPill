# BlinkerTestBlackPill
Blinker Test Project for STM32 Black Pill Evaluation Board

## Tools used for this project:
- [STM32CubeIDE](https://www.st.com/en/development-tools/stm32cubeide.html).
- STM32 [ST-LINK utility](https://www.st.com/en/development-tools/stsw-link004.html).
- STM32 [ST-LINK USB driver](https://www.st.com/en/development-tools/stsw-link009.html).


## HW used for this project:
- STM32 [Black Pill](https://stm32-base.org/boards/STM32F401CCU6-WeAct-Black-Pill-V1.2.html) board.
- [ST-LINK V2](https://stm32-base.org/guides/connecting-your-debugger.html) clone.

![image](https://github.com/AhmedEltorky/BlinkerTestBlackPill/assets/26473614/6b16e9eb-7538-4d8f-9cc6-7f7036cfa2db)
![st_link](https://github.com/AhmedEltorky/BlinkerTestBluePill/assets/26473614/ea0bb447-8ebf-40a2-b178-9174ab8812eb)


## Configuration steps for CubeMX:

- Open the configurations perspective.

- Enable crystal for the board.

![image](https://github.com/AhmedEltorky/BlinkerTestBlackPill/assets/26473614/0709d24b-960c-4ae8-a0ee-528f3a03ed06)

- Configure PC13 "user LED" as GPIO_OUT.

![image](https://github.com/AhmedEltorky/BlinkerTestBlackPill/assets/26473614/398bc7b1-8776-433b-829d-603a23f509b5)

- Save changes "Ctrl + C" to generate the required files.

## Build and flash the project:

- Use the default debug configurations and click Debug.

![image](https://github.com/AhmedEltorky/BlinkerTestBlackPill/assets/26473614/5023365a-910b-4895-888c-70a67ce936e1)

