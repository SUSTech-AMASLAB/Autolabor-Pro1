# Autolabor Pro1

> @Brief：该仓库是AMAS-LAB移动机器人设备**Autolabor Pro1 机器人底盘**的介绍和使用文档。
>
> @Author：[Li Dong](https://github.com/DoongLi)
>
> @Date：2023-2-9

![2](Notes/IMG/2.jpg)

## Autolabor Pro1基本配置介绍

| 项目名称       | 内容                      | 项目名称     | 内容                     |
| -------------- | ------------------------- | ------------ | ------------------------ |
| 设备名称       | Autolabor Pro1 机器人底盘 | 设备厂商     | 北京华清智能科技有限公司 |
| 尺寸           | 726\*617\*273mm           | 净重         | 40kg                     |
| 通信接口       | 串口                      | 负载         | 50kg                     |
| 驱动及转向方式 | 四驱，差速                | 电池         | 24v 磷酸铁锂电池，4h续航 |
| 手柄通讯       | 2.4Ghz                    | 手柄控制距离 | 20m                      |

## File Description

- Notes：存放设备的调试文档
  - 1.Device-List-and-Basic-Control.md：设备清单及基本控制
- Doc-and-Drive：存放设备的**官方**文档及代码
  - 1.STM32_RevB1.rar：Autolabor Pro1 机器人底盘下位机STM32源码。

## Reference

- 1.Autolabor官网**Autolabor Pro1机器人底盘**产品介绍：http://www.autolabor.com.cn/pro/detail/4
- 2.**Autolabor Pro1机器人底盘**使用文档：http://www.autolabor.com.cn/usedoc/ap1/receipt

## FAQ

| Index | 问题                                         | 解决方法                                                     | 备注 |
| ----- | -------------------------------------------- | ------------------------------------------------------------ | ---- |
| 1     | 购买的Autolabor Pro1到货时出现较大的漂移状况 | 已联系厂商进行退换                                           |      |
| 2     | 官方售后咨询方式                             | 微信公众号“Autolabor”，输入 “人工”进行咨询                   |      |
| 3     | 底盘测试出现轻微漂移情况                     | Reference：http://www.autolabor.com.cn/usedoc/ap1/odomCalibration 进行重新标定 |      |

## Update

| Index | Date      | Context                                                      | Todo list                    |
| ----- | --------- | ------------------------------------------------------------ | ---------------------------- |
| 1     | 2023-2-9  | 设备到货开箱，基本资料整理，手柄控制方式调试；测试出现严重的漂移问题，已联系厂商进行退换 | 上位机测试平台搭建测试       |
| 2     | 2023-2-13 | 退换的新底盘到货，测试完成，联系厂家发货3D激光雷达3D打印安装架 | 上位机安装以及3D激光SLAM测试 |
|       |           |                                                              |                              |

