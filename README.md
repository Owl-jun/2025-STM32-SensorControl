# 2025-STM32-SensorControl
다기능 센서 데이터 로거 및 제어 시스템


## 프로젝트 목표

STM32F103 보드 두 개를 사용하여, 다양한 센서 데이터를 수집하고(I2C, SPI), 이를 PC로 전송하거나(UART), 다른 보드로 전달하며(UART, SPI), 
특정 조건에 따라 액추에이터(LED 등)를 제어하는 시스템을 구축합니다.

> 궁극적인 목표는 HAL , LL , RTOS를 실제 구현해보며 학습하는 것에 있습니다.


## 진행상황

### > [1. HAL 입문기1 . UART을 통한 PC 통신 (에코백)](https://velog.io/@owljun/06.-HAL-%EC%9E%85%EB%AC%B8-UART-%EC%86%A1%EC%8B%A0-%EA%B5%AC%ED%98%84%EA%B8%B0)
### > [2. HAL 입문기2 , I2C 통신 HW 구성부터 센서 데이터 수신까지](https://velog.io/@owljun/07.-HAL-%EC%9E%85%EB%AC%B8%EA%B8%B02-I2C-%ED%86%B5%EC%8B%A0-%EA%B5%AC%ED%98%84)
