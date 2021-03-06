# Amazing_Face_Detection
CPU Real-time Amazing Face Detection
# FIND CODE  
https://blog.csdn.net/samylee/article/details/103396893  
# Test steps
## step1
Download opencv_dll and put it to current directory [BaiDu Cloud](https://pan.baidu.com/s/14VIsF6PD6ktU7ctUh301wA)
## step2
Set parameters:
`Amazing_Face_Detection.exe test_type img_path`
```cpp
like:  Amazing_Face_Detection.exe image test.jpg  (for image)
or:    Amazing_Face_Detection.exe imgdir /img/path/test_imgs  (for imgdir)
or:    Amazing_Face_Detection.exe video test.avi  (for video)
or:    Amazing_Face_Detection.exe video 0  (for usbcam)
```
# Algorithm efficiency
| Image Size | min_size | CPU(i7-9700K) Speed/FPS | CPU(ARMv7 @1.4GHz) Speed/FPS |
|:------:|:------:|:------:|:------:|
| 320x240  | 12x12 | 6ms/166.7 |35ms/28.6|
| 640x480  | 12x12 | 23ms/43.5 |190ms/5.3|
| 800x600  | 12x12 | 42ms/23.8 |    -     |
# Test experience
If the image size is larger than `720p`, it is recommended to scale the image `below 720p`!
# Example result
![](result.jpg)
# Reference
https://blog.csdn.net/samylee
