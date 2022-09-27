# SCM-chapter4 proteus仿真平台简介

Proteus是英国Labcenter Electronics公司推出用于对单片机应用系统进行虚拟仿真的软件开发平台。

在单片机系统的设计开发中，一般是先在Proteus环境下绘出系统的硬件原理图，在Keil C51环境下书写并编译程序，然后在Proteus环境下仿真调试通过,**仿真结果只能用于参考**。

本章内容对Proteus软件中涉及到系统仿真的常见操作作简要介绍

## 4.1软件安装

## 4.2 新建工程

1. 点击工具栏中新建按钮![image](https://user-images.githubusercontent.com/113764572/192434372-96079098-6da1-4a21-838d-aa94d6e998c0.png)，弹出新建工程向导对话框

	![image](https://user-images.githubusercontent.com/113764572/192434565-7013203b-9d7a-4d12-baa0-63120e26e0fc.png)
	
	设置工程名和保存路径。点击下一步。
	
2. 选择采用默认模板，不制作PCB。不关联固件。
	
	![image](https://user-images.githubusercontent.com/113764572/192434999-ef6d0b22-3f70-4eab-bdf0-75c01ade3b13.png)
	
	![image](https://user-images.githubusercontent.com/113764572/192435074-a198e2e2-9954-46f6-b50d-362e60dd9b7f.png)
	
	![image](https://user-images.githubusercontent.com/113764572/192435158-e41d7318-3951-4d50-91e3-052f48abeb25.png)
	
3. 点击finish结束。

	![image](https://user-images.githubusercontent.com/113764572/192435217-a2ea3cf5-05b2-471e-a4b1-4450c8506a8d.png)
	
## 4.3 向原理图编辑窗口中放置元件

1. 点击界面左侧工具箱中的元件模式按钮![image](https://user-images.githubusercontent.com/113764572/192439171-336997cc-bbfa-4133-8768-4bd66ace11ab.png)切换到元件放置模式。
	![image](https://user-images.githubusercontent.com/113764572/192439931-628c4039-016f-424f-91a0-908e14b0788d.png)
	
	点击元件列表区顶部的P按钮。![image](https://user-images.githubusercontent.com/113764572/192440069-aeb629be-398b-44db-919f-4a8f25cd134b.png)
即可打开拾取元件对话框。
	![image](https://user-images.githubusercontent.com/113764572/192443357-aa3a1d48-fe8e-45c5-8d91-db3752403ec4.png)

2. 拾取元件对话框中常用元件的搜索，将元件添加到元件列表窗口。

| 元件 | 关键词     |
|:--------:| -------------:|
| 51单片机 | At89C51 |
| 电阻 |RESISTOR 10K |
| 电容 | CAP |
| 按钮| BUTTON |
| 晶振 | CRY |
| 数码管 |RED 4 DIGIT |
| 发光二级管 | LED-RED |

在搜索结果框中双击对应的元件。将元件添加到。元件列表窗口中。
![image](https://user-images.githubusercontent.com/113764572/192444632-1cc1d3f8-67e2-420e-b980-4bfb1488f818.png)

3. 放置元件

放置元件时，先选定元件列表窗口中的元件，再将鼠标移动到合适位置，单击左键即可放置元件。

## 4.4 放置电源

1. 点击左侧工具栏中终端模式按钮。![image](https://user-images.githubusercontent.com/113764572/192445411-3c5827e7-2ea1-44ee-a173-81975442b323.png)

进入终端放置模式。

![image](https://user-images.githubusercontent.com/113764572/192445565-73438419-4451-4b43-b813-c76aa8f2e828.png)

2. 放置电源和地。

终端列表中的POWER和GROUND即为电源和地。

## 4.5 放置信号源。
点击左侧工具栏中的。发生器模式按钮。![image](https://user-images.githubusercontent.com/113764572/192446196-4a2fdcac-c5e6-473c-aad0-6057608ba337.png)
即可选择正弦波，脉冲波等多种信号发生器。
## 4.6 放置测试设备。
点击左侧工具栏中的虚拟仪器模式按钮。![image](https://user-images.githubusercontent.com/113764572/192446385-9f81b984-f398-4fb9-8118-9494d9b69fe5.png)
即可选择示波器电压表等测试设备。

## 4.7 元件的移动、属性修改、电路的连线。

点击左侧工具栏中的选择模式按钮。![image](https://user-images.githubusercontent.com/113764572/192447207-512a14dd-09a8-4131-aa1a-3343dfb35387.png)
切换到选择模式。

- 移动元件---拖动。

- 属性修改---双击元件。

- 电路连线---用左键，在连线起始处单击，在连线结束处单击。

## 4.8 加载目标代码文件

双机单片机元件，在弹出的编辑软件对话框中的program file项，输入框中浏览选定对应的可执行文件。
![image](https://user-images.githubusercontent.com/113764572/192448508-7200493a-ef6a-49f7-8812-49897acd6ad2.png)

## 4.9 仿真运行。
点击界面左下角的仿真运行命令按钮。

![image](https://user-images.githubusercontent.com/113764572/192451022-c2c23f8e-49a7-49a4-98bc-6ba65bdc5327.png)

	



