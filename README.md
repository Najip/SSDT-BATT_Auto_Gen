**English** | [Original Readme : 中文](./README_cn.md)

# SSDT-BATT_Auto_Gen

A Python script to automatically generate an SSDT-BATT from your DSDT.

---

> **I continue this project since `ECEnabler` only supports Field Unit objects larger than 8 bit (1 byte) for `EmbeddedControl` regions but not in `SystemMemory` OperationRegions. This script still useful for `SystemMemory` based EC found on some Laptops. I reopen the scripts repo so anyone can contribute to improve it. I will archive this repo if [@eric_kwok](https://github.com/the-eric-kwok) re-open the main Repo.**

---

Copyright (c) 2020 Guo Yaoming. All Rights Reserved.

<u>Recommended to use `pypy3` for better performance</u>

## Installation

```bash
brew install pypy3
```
## Usage

```bash
python3 Auto_Gen.py <DSDT.dsl>
```
or
```bash
pypy3 Auto_Gen.py <DSDT.dsl>
```

