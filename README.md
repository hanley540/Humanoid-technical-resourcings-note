# Humanoid-resourcing-and-one-of-its-subjective-description. 類人主觀描述及相關資源筆記
開機時間
====
西元2044. <br>
開發進程: 慢. <br>

思想
====
配合自然環境, 啟動個人機器人取代食衣住行育樂"個人"需求.<br>
All-in-one with mode selection.<br>
單一產品, 盒裝.<br>
可升級維護可讀可重組模塊.<br>
1比1人身.<br>
平均工員能力.<br>
高效連束, 捨去螢幕成本.<br>
相對省電.<br>

生產
====
批量/限量

可回收
====
是.

軟硬體思維
====
軟: Agile Software Development by Martin.
硬: Upgradable modular design.

Sketch (Draw and CAD)
====


Site
====


硬件打樣預估成本(物料成本, 不含人事, 軟體)
====
2021年現鈔價值的新台幣3萬5千元.<br>
設計端(腦力)便宜化, 供應鏈均衡化導向.<br>

Brand, Retails, and Manufacturer
====
Digi-key.<br>
h.<br>
DFRobot.<br>
蝦皮.<br>

Books/References/Subjects
====
圖解馬達入門. <br>
機構學 版五. <br>

Terms
====
Cyber-Physical System. 虛擬網路實體物理系統 <br>
https://en.wikipedia.org/wiki/Cyber-physical_system

MPU (Mini Computer)
====
Nvidia Jetson series. (Ready-to-use OS) <br>
Raspberry series. (Ready-to-use OS) <br>
Banana series (Alternative to Raspberry. More Practical) <br>
STM32 series on Mbed. <br>
Customization with ARM core.<br>

MPU-OS
====
Family: Unix <br>
目的: 統一OS標準及協定.<br>

Sound Input/Output (內建音響)
====

電機/電控硬體 (*)
====
Motor Drive Control: <br>
PCB Layout of Motherboard of every single part: <br>

Transport layer
====
Websocket. 


Humanoid Firmware (The BIOS  Humanoid's motherboard)
====


Brain
====
Deep Learning to multiple features with Pytorch. <br>
Natural Language Processing: <br>
Conversional: Nvidia/NeMo. <br>


Power Supply (Battery)
====
太陽能板<br>
LiPo電池<br>
固態電池<br>
納

Middleware/Session Layer.
====
ROS.<br>
Protocol: lwm2m<br>
Websocket.<br>
lwm2m:<br>
C library: Anjay.<br>
Node.js search from NPM.<br>

Ad Hoc for p2p communication of robots
====

Mechanism
====
8 DoF

Components in common (電氣元件...)
====
Motors.<br>
Torque.<br>
Power Supply<br>
Low/High Volt WireHarness. <br>
ESP8266(Wifi).<br>
4G/LTE sim module. SIM7600X.<br>
Antenna for Radio.<br>
External Antenna.<br>
Ad Hoc module.<br>
High-voltage connector and motors.<br>
Motor Drivers.<br>
Interconnects.<br>
DC-DC boost converter.<br>
Step-up.<br>
三軸加速度傳感器.<br>
Transmission line.<br>

Actuator
====

3D Sensing
====


Sensors
====
Hardness detection.<br>
Surrounding Situation Detection: RPiLader, TF2.<br>

Computer Vision
====
OpenCV.

Arm Part.
====

Materials 材料
====
Hard:<br>
6061, 純鋁<br>

Soft:<br>

Cp semi
Components<br>

Bipedal Part.
====
Motors: <br>
Actuator: <br>
Sensor: <br>

Transformation 模式
====
Edge mode in default. (Better for Privacy Protection) <br>
Basic action and land mobile (Fast walk \ Slow walk) in default. <br>
Cloud mode for system upgrade and update. (C/S mode) <br>
Hygiene Career mode. (清潔事業模式) <br>
Worker mode.(搬運工模式) <br>
Cooker mode. (Normal \ Chief) <br>
Drone mode. 螺旋翼/網格 (飛行模式/Drone Mode) <br>
Industrial production/operation of components and 紡織製衣.<br>
Pharmacist Mode. (配藥建議模式) <br>
Temporal reside (臨時住屋模式)(雨水回收與儲水系統+太陽能電力) <br>
Farm Mode.<br>


Application layer (UXUI for User Terminal, All-Platfrom(iOS, Android...) App Control and Monitoring)
====
Godot Engine.<br>
Krita for original icon sketch.<br>

Metal Shaping 板金成形.  (手工(無須開模/過程慢)/模具/數控 <= 大小件區別)
====
Compound curve.<br>

Objective 目的.
====
依時間順序.<br>
In/Outdoor Hygiene (清潔) Services.<br>
Simple Cook Services.<br>
Street Walk.<br>
Accompany and Entertaining.<br>
高適性, 高彈性需求, 需要各層級訊息的低延遲配合.

Passed references
====
Asimo<br>
Documents:<br>

Legal Statement.
====

驗證 Testimony.
====
防水

測試地
====
農地/海邊.<br>
海景屋

