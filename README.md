# How to Convert HDF5 Dataset to TIFF Images in Batch?

Now we face an annoyed and time-comsumping routine: we need to convert HDF5 datasets (collected from `Dectris Eiger Detectors`) to TIFF images one-picture-by-one-picture with `ALBULA` software, is any method much more convenient and faster?

<br />

## Here Comes the Savior: `DPDAK`

`DPDAK` is an open source software developed for analysis of large sequences of small angle scattering data (but thereotically, you can use for other datasets as well). It support Windows and Linux operation system, and other detail about it you can refer this website: [DPDAK - Directly Programmable Data Analysis Kit](https://confluence.desy.de/display/DPDAK/DPDAK+-+Directly+Programmable+Data+Analysis+Kit)

*Nowaday the latest-stable version is v1.4.0, its user manual is available here: [User Manual v1.4.0](https://confluence.desy.de/display/DPDAK/User+Manual+v1.4.0) (on June 16, 2020)

<br />

## Step 1: Download and Install Dependencies of `DPDAK`

You can refer this article then download the latest-stable version `DPDAK` software: [Most Recent Stable Version: DPDAK 1.4.1](https://confluence.desy.de/display/DPDAK/Downloads)

> Notice system requirements mentioned in above link, you should install and check every dependencies before you run `DPDAK`.

<br />

## Step 2: Download and Run `DPDAK` Software

Download then extract the zip file to any location you want, then execute the batch file named `dpdak.bat` in the folder.

<br />

## Step 3: Add the Plugin Helps Us Convert HDF5 Dataset to TIFF Images in Batch

There are many plugins built in `DPDAK` software, also it allows software developers create their custom plugins for other tasks. The plugin we need is named `DectrisEigerHdf5ToTiff`, detail infomation here: [https://confluence.desy.de/display/DPDAK/DectrisEigerHdf5ToTiff](https://confluence.desy.de/display/DPDAK/DectrisEigerHdf5ToTiff)

> Refer this article to learn how to add a plugin: [Quick Start: Add a plugin](https://confluence.desy.de/display/DPDAK/Quick+Start)

<br />

## Reference
1. DPDAK User Manual v1.4.0: https://confluence.desy.de/display/DPDAK/User+Manual+v1.4.0
2. DectrisEigerHdf5ToTiff Plugin: https://confluence.desy.de/display/DPDAK/User+Manual+v1.4.0