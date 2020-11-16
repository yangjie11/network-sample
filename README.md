# network samples package

[中文页](README_ZH.md) | English

## 1 Introduction

This package contains some network operation routines.

### 1.1 Routine Description

| File | Description |
| ---------------- | ------------------------------- |
| httpclient_sample.c | Create an http client to get weather data |
| tcpclient_sample.c | Create a TCP client |
| tcpserver_sample.c | Create a TCP server |
| udpclient_sample.c | Create a UDP client |
| udpserver_sample.c | Create a UDP server |
| tcpclient_select_sample.c | Use select interface to implement TCP client |

### 1.2 License

The network samples package complies with the Apache license v2.0, see the `LICENSE` file for details.

### 1.3 Dependency

Rely on network components.

## 2. How to open the network samples package

To use the network samples package, you need to select it in the RT-Thread package manager. The specific path is as follows:

```
RT-Thread online packages
    miscellaneous packages --->
        samples: kernel and components samples --->
            a network_samples package for rt-thread --->

```

Then let the RT-Thread package manager automatically update, or use the `pkgs --update` command to update the package to the BSP.

## 3. Use network samples package

After opening the network samples package, when the BSP is compiled, the relevant source code of the selected software package will be added to the BSP project for compilation.

## 4. Matters needing attention

Nothing.

## 5. Contact & Thanks

* Maintenance: [misonyo](https://github.com/misonyo)
* Homepage: https://github.com/RT-Thread-packages/network-sample
