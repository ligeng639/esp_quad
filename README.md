# esp_quad


四轴飞行器
quadcopter
.
. 
可能有些地方可能不专业，请指出和包涵。
不知道要写什么，需要什么信息评论。
.
.
.
支持遥控直接调PID!!!

建议用我开源的esp_trans, 可以直接调pid，还可以连接电脑模拟器!!!

(esp_trans 还没开源， 等我整理好就发)
.
.
.
lib used

https://github.com/ElectronicCats/mpu6050

https://github.com/denyssene/SimpleKalmanFilter

https://github.com/nRF24/RF24

https://github.com/madhephaestus/ESP32Servo

	   
(currently i am using 3d printed foldable frame with same pid settings)

F450 frame

2212 1000kv

9047 propeller

Blhelis 30A ESC

2200mAh 30C lipo

ESP32 dev v1

MPU6050

NRF24l01 (dip)
.
.
.
（这个原理图是我在刚学会画图的时候画的，那时候只知道用线。。。）

如果你的电调没有bec，那个5v就没用

我没有给nrf加电容。

pcb 大小:50*70mm

pcb 洞直径4mm， 圆心距离板子边缘是也是4mm

esp32，mpu 和 nrf 都是在一个平面上的，要用到排母。具体看视频:https://www.bilibili.com/video/BV1Rq4y1k74o/

![Snipaste_2022-01-23_21-15-34](https://user-images.githubusercontent.com/93729382/150698246-78d3da66-8087-4fe0-b6a5-2e3735c33d64.png)
.

你可能需要给你的桨叶动平衡。可以用一些胶带。




