# ArmComplier5.06

MDK 5.36 之后不再支持 AC5（ARM Compiler version 5）编译器，想继续用需要自己装。这里提供 AC5 的备份与安装步骤。

## 安装步骤

1. 将两个压缩包解压后的四个文件夹，组成名为 `ARMCC` 的文件夹
2. 将其移动到 Keil 5 安装目录下的 `ARM` 文件夹内
3. 打开 Keil 5，选择 `Manage Project Items`
4. 选择 `Folders/Extensions`
5. 在 `Use ARM Compiler` 一栏选择 `ARMCC` 文件夹路径
6. 之后便可在魔法棒里选择 `Target` → `ARM Compiler` → `v5.06`

## 版权说明

本仓库仅作 ARM Compiler 5.06 的转载与备份，压缩包内所有内容的版权归 **Arm Limited** 所有。
本仓库不对其主张任何开源许可，下载与使用请遵守 Arm 的许可协议。
