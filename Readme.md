# ECEN5713 Final Project (Fall 2023)

# Project Overview

[Project-Overview](https://github.com/cu-ecen-aeld/final-project-VisweshBaskaran/wiki/Project-Overview)

# Project Schedule

[Project-Schedule](https://github.com/users/VisweshBaskaran/projects/1)

# Project demonstration 

[Link to demo video](https://drive.google.com/file/d/1x8BvU9jXe1MMr_M3Rcei-SJP3ba_1Ley/view?usp=drive_link)

The video demonstrates:

Setup of Buildroot image for Raspberry Pi 3


Performed Buildroot Build-Time Config.txt Customization


Setup of I2C and SPI in device overlay


Demonstration of functionality of BME280 and MQ135

Challenges

Installing packages without pip and WiFi configuration.

The image got corrupted after booting up and loading some packages, and I had to start again. 

Lessons Learned

How to use make menuconfig more efficiently, to add communication protocols to device overlay, to add existing python packages

How to add custom Python packages

Attention to Naming Conventions; how the naming of variables, and file names can lead to issues in buildroot Linux environment

Dependency Management; Dealing with dependencies, both at the application and library level

Backup management; Having backups of images, and versioning ensured project continuity and facilitated rollback
