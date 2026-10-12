# PICO-Humanoid 机械设计

本仓库是 [PICO-Humanoid](https://github.com/pico-humanoid/pico-humanoid.github.io) 负责机械设计部分的子项目，主要涵盖关节电机模型、机身结构设计等内容。

- 关节电机模型：[Motor](Motor/)
- 机械零件模型：[Part](Part/) *Continuously updated...*
- 机身结构模型：*Coming soon...*
- 其他器件模型：*Coming soon...*
- 整机装配体：*Coming soon...*

> 建议使用 SolidWorks 进行机械设计，可参考[工具栈指南](https://github.com/pico-humanoid/pico-humanoid.github.io/tool-tutorial.md)

## 关节电机

- 采用 **灵足时代(RobStride)** 一体化关节模组
    - [RS-10P](https://www.robstride.com/products/robStride10P) `.stp`：主电机，提供约 $14\mathrm{N\cdot m}$ 的额定扭矩

        <img src="images/RS-10P.png" alt="RS-10P 关节电机" height="250">

    - [RS-00](https://www.robstride.com/products/robStride00) `.step`：副电机，提供约 $5\mathrm{N\cdot m}$ 的额定扭矩

        <img src="images/RS-00.png" alt="RS-00 关节电机" height="200">

- 接口规格：xt30(2+2)公口（供电通讯一体化）

- GitHub 开源社区：
    - [RobStride 产品资料](https://github.com/RobStride/Product_Information)：电机 3D 模型、规格参数、使用手册等
    - [RobStride 电机控制库](https://github.com/RobStride/RobStrideSPC)：基于 STM32 HAL 的电机 CAN 通讯控制库

## 机械零件

*例如螺丝、螺母、六角柱等。*

- 六角杯头螺丝 `.SLDPRT`
    - M3x6/8/10/12
    - M4x6/8/10/12

*Continuously updated...*

## 机身结构

*例如躯干、臂、腿、头部等。*

*Coming soon...*

## 其他器件

*例如电池外壳、Jetson板、PCB模型等。*

*Coming soon...*

## 整机装配

*所有基本部件设计完成后进行整机装配。*

*Coming soon...*