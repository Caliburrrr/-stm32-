# 基于stm32F4的示波器与信号发生器
# 使用stm32f411ceu6最小系统板和8位R2R-DAC，在OLED上显示波形
# 可生成正弦波，方波，三角波，直流信号，按键切换
# 频率范围为10hz-1000hz，步进100hzk；幅度为0-3.3V，步进0.3V，使用编码器调节
# 使用DSP库进行fft测量频率
# 采样率可调
