# SSD-MobileNet-ncnn
SSD-MobileNet with Tencent ncnn framework
 - Train on [caffe](https://github.com/chuanqi305/MobileNet-SSD) and convert model to the ncnn version. You can download model from [here](https://drive.google.com/open?id=0ByaKLD9QaPtucWk0Y0dha1VVY0U). 

## Before compile
 - Copy model  to the 
```sh
(PROJECT_ROOT)/model
```
 
## Require Dependency Library
  - OpenCV 3.3.1 (For displaying demo video)
  - ncnn 2017.12.25 (In the package folder)

### Compile in Windows 
```sh
$ ./build_vs2017_x64.bat
```

### Compile in Ubuntu 
```sh
$ sh build_ubuntu.sh
```

### Compile in Raspberry Pi 
```sh
$ sh build_raspberry.sh
```