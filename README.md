esp32_can
==========

一个新的统一库，包含使其运行所需的代码。实现 ESP32 上内置 CAN 硬件的 CAN 驱动程序。还实现了一个驱动程序 用于 MCP2517FD SPI 连接的 CAN 模块。内置的 CAN 称为 CAN0， MCP2517FD称为 CAN1。此库专门用于 EVTV ESP32-Due 板。但是，通过小的修改，两个驱动程序都找到了 可以在其他板卡上使用。

此库需要 can_common 库。该库是一个公共基础 可以构建其他库以允许更通用的 CAN API。

所需的 can_common 库位于： https://github.com/collin80/can_common
