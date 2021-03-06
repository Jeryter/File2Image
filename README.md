# File2Image
Convert any binary file into an image (using Python 3.8 on Windows 10). 

把任意二进制文件转换为一张图片（测试环境为 Python 3.8 和 Windows 10）。

## file2img_demo.py
This is a demo for converting files into RGB PNG images. Users should customise the code to meet their needs.

In this demo, he input is defined by variable `original_file`, with the output image defined by `end_file`. The size of the output image is 256 * x, where `x` is the height and is determined by the size of original file.

此代码仅为将文件转换为 PNG 格式的 RGB 图像的示例。使用者需要根据各自不同的需求来重新定制代码。

在本示例中，变量 `original_file` 是待转换的文件路径，变量 `end_file` 是转换后的图片路径。输出的图片大小为 256 * x，其中 `x` 是图片的高度，并由输入文件的大小决定。

## img2file_demo.py
In this demo, images are recovered to the original files. Also, further developments are needed to meet different needs.

`recovery_img` is the image converted from a file, and `recovery_file` is the output. SHA256 is calculated to check the result.

在本示例中，图片将被恢复为原始文件。同样，使用者需要对代码进行修改，以满足使用需要。

`recovery_img` 是由文件转换的图片，`recovery_file` 是从图片中恢复的文件。这里使用 SHA256 来检验恢复是否成功。

## dcx.pdf
Demo. The file to be converted into an image. (Photos in pdf are [Ding Chengxin](https://www.weibo.com/u/5781292544).)

样例。将转换为图片的文件。（文中的照片是[丁程鑫](https://www.weibo.com/u/5781292544) 。）

## dcx2.png
Demo. The output of `file2img_demo.py` and input of `image2file_demo.py`.

样例。`file2img_demo.py` 的输出和 `image2file_demo.py` 的输入。
