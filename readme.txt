1.解压darknet-master.zip

2.用cmd进入darknet-master\build\darknet\x64

3.图片识别：输入darknet_no_gpu.exe detect obj.cfg obj_21000.weights 0027.jpg  (0027.jpg可替换为x64目录下的其他图片)

4.视频识别：输入darknet_no_gpu.exe detector demo obj.data obj.cfg obj_21000.weights truck2.mp4(truck2.mp4可替换为x64目录下的其他视频)