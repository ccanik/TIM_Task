# TIM_Task
An implementation of ADXL345 sensor using STM HAL Library with I2C interface


* sensor.h and sensor.c are sensor implementations
* HAL_TIM_PeriodElapsedCallback(TIM_HandleTypeDef *htim) function is callback function of timer interupt.
* HAL_PWR_EnterSLEEPMode( ... ) function automatically set mcu sleep mode and wake up when interrupt occurs.
