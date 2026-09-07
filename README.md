# XCZU67DR-FSVE1156-2-I 资料库

本仓库收集 AMD/Xilinx **Zynq™ UltraScale+™ RFSoC DFE** 芯片 **XCZU67DR-FSVE1156-2-I** 的官方文档、封装资料，以及配套评估板 **ZCU670** 的板级设计文件，用于 LLRF（低电平射频）等相关开发参考。

## 器件简介

XCZU67DR-FSVE1156-2-I 是 Zynq UltraScale+ RFSoC DFE 系列的工业级器件：

- **PS**：四核 Arm Cortex-A53（64 位应用处理）+ 双核 Cortex-R5F（实时处理）
- **PL**：UltraScale+ 架构可编程逻辑
- **RF**：直接射频采样 RF-ADC / RF-DAC，硬化数字前端（DFE），模拟带宽至 7.125 GHz
- **封装**：FSVE1156（1156 球 BGA，lidless）
- **速度等级 / 温度**：-2，工业级（I）
- **官方评估板**：ZCU670（板上器件即 XCZU67DR-2FSVE1156I）

## 目录结构

### 芯片官方文档（`xczu67dr-docs/`）

| 文件 | 说明 |
|---|---|
| ds889-zynq-usp-rfsoc-overview.pdf | RFSoC 数据手册：概述 |
| ds883-zynq-rfsoc-dfe-overview.pdf | RFSoC DFE 数据手册：概述 |
| ds926-zynq-ultrascale-plus-rfsoc.pdf | DC/AC 开关特性（电气与性能规格） |
| xmp105-zynq-usp-rfsoc-product-selection-guide.pdf | 产品选型指南 |
| pg269-rf-data-converter.pdf | RF Data Converter IP 产品指南 |
| ug1085-zynq-ultrascale-trm.pdf | 器件技术参考手册（TRM） |
| ug1075-zynq-ultrascale-pkg-pinout.pdf | 封装与引脚 |
| ug583-ultrascale-pcb-design.pdf | UltraScale PCB 设计指南 |
| ug1099-bga-device-design-rules.pdf | BGA 器件设计规则 |
| ug1037-vivado-axi-reference-guide.pdf | Vivado AXI 参考指南 |
| xczu67drfsve1156pkg.txt | FSVE1156 封装 ASCII 引脚文件 |

### ZCU670 评估板资料（`xczu67dr-docs/`）

| 文件 | 说明 |
|---|---|
| ug1532-zcu670-eval-bd.pdf | ZCU670 评估板用户指南 |
| zcu670-product-brief.pdf / zcu670-kit-flyer.pdf | 产品简介 / 套件宣传单 |
| xtp690-zcu670-schematics.zip | 原理图 |
| xtp691-zcu670-allegro-board.zip | Allegro 版图文件 |
| xtp692-zcu670-board-interface-test.zip | 板级接口测试工程（BIT） |
| xtp693-zcu670-ibert-example-design.zip | GT 收发器 IBERT 示例 |
| xtp695-zcu670-mig-example-design.zip | DDR MIG 示例设计 |
| xtp698-zcu670-system-controller-tutorial.zip | 系统控制器 GUI 教程 |
| xtp699-zcu670-setup.pdf | 软件安装与板卡设置指南 |
| xtp689-zcu670-ce-doc.zip | CE 合规声明 |
| xtp731-xm755-schematics.zip | 配套 XM755 射频子卡原理图 |

### 本地工程与教程（仓库根目录）

| 文件 | 说明 |
|---|---|
| 67DR_DDRTEST.rar | DDR 测试工程 |
| XCZU67DR(1).rar | 器件相关工程压缩包 |
| 3-2-01米联客2022版Zynq MPSOC SDK入门篇-202201151.pdf | 米联客 Zynq MPSOC SDK 入门教程 |

## 资料来源

- 芯片文档 / XTP 设计文件：AMD 官方文档库 [docs.amd.com](https://docs.amd.com)
- 封装引脚文件：AMD 官方下载中心 [download.amd.com](https://download.amd.com)
- ZCU670 产品页：[AMD ZCU670 Evaluation Kit](https://www.amd.com/en/products/adaptive-socs-and-fpgas/evaluation-boards/zcu670.html)

## 克隆说明

仓库中 3 个超过 100 MB 的文件使用 **Git LFS** 存储，克隆前请先安装 LFS：

```bash
git lfs install
git clone https://github.com/oxygen0827/xczu67dr-fsve1156-2-i.git
```

> 所有文档版权归 AMD/Xilinx 及相关作者所有，本仓库仅作学习参考整理。
