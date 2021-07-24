# embeddedToyBox

- This project is designed for every embedded developer.test,trans,verify...anything you want.
- 给嵌入式开发测试要用到的小工具合集...

## 场景

1. 芯片执行测试功能和数据输出功能,所有数据由上位机处理
   - 例如:DSP,ADC,CAMERA.
   - 当数据量较大时,芯片通过DMA缓存分段发送,则PC端流程不变
2. 在裸机上开发非对称加密,需要对二进制签名而没有FileSystem
3. 需要程序化控制仪器而不是手工操作.

## 功能

已实现的功能,点击链接即可跳转

- 文本数据类
  - [x] [文本转二进制文件](https://github.com/idk500/ASCII2BIN) (Perl from ZhuXW)
  - [ ] 二进制文件转文本
  - [ ] 文本格式化
  - [ ] 文本转excel
  - [ ] excel转文本
  - [ ] 文本/excel数据分析和图表汇报(跳差,方差,均值,拟合曲线和校正参数)
- 代码转换类
  - [ ] 根据手册自动生成CMSIS-PACK 芯片支持包
  - [ ] 根据手册快速生成符合CMSIS标准的底层驱动代码
  - [ ] 根据手册快速生成符合CMSIS标准的HAL驱动代码

- 虚拟仪器类
  - [ ] 通过RaspberryPi/Arduino/Nuclero等标准开发板 快速制造TTL测试波形
  - [ ] 快速读取波形数据并提供分析报表
 
 - 框架类
  - [ ] 通过一个脱机面板调取上面所有功能
