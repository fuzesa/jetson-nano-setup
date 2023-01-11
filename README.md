# Jetson Nano Boot from USB Setup Guide

---

## Overview
This is guide is meant for the _Jetson Nano **A02**_ (additional info: [Nvidia Jetson Nano Developer Kit A02 vs B01 vs 2GB](https://tutorial.cytron.io/2020/10/14/nvidia-jetson-nano-developer-kit-a02-vs-b01-vs-2gb)) and assumes that the user has previously installed at least version **4.5.1** JetPack with the previously more common SD Card method (Link: [Getting Started with Jetson Nano Developer Kit](https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit)).  
The idea here is that the Jetson's operating system will be installed to a USB flash drive instead of a SD card.  

### Source Material
The instructions here are mainly based off of information from

| Title                                 | Link                                                                                              |
|---------------------------------------|---------------------------------------------------------------------------------------------------|
| NVIDIA Official Developer Forum Topic | [Boot from external drive](https://forums.developer.nvidia.com/t/boot-from-external-drive/182883) |
| JetsonHacks Blog                      | [Jetson Nano – Boot from USB](https://jetsonhacks.com/2021/03/10/jetson-nano-boot-from-usb)       |

## Download and Extract Image
The link for the SD card image that will be used with the flash drive can be found on NVIDIA's Developer Downloads section at https://developer.nvidia.com/jetson-nano-sd-card-image.  
Please be aware that as of this writing the OS image file in the above link is for JetPack version **4.6.1** which is _not the latest_, therefore the user will have to manually upgrade via changing the APT source file.
