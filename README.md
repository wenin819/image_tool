# image_tool

python3 实现的图像处理工具

## replace_color.py

替换png或jpg中图片的颜色，支持两种替换方式：
1. 模糊替换，按RBG中红色大于150的进行替换，用于单颜色的icon；
2. 精确替换。

具体见配置部分。

说明：
1. 此工具会自动备份源文件到当前目录下的backup目录；
2. 此工具会直接改变源文件。