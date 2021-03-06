##优化图片

当PageSpeed Insights检测到网页上的图片可通过优化来减小其尺寸，且不会显著影响其视觉效果时，就会触发此规则。

**概览**

尽量减小图片尺寸，以缩减用户等待资源加载的时间。适当地设置图片的格式并进行压缩可以节省大量的数据字节空间。这样可以为那些网络连接较慢的用户节约时间，还可以为有流量套餐限制的用户节省成本。

**建议**

您应对所有图片进行基本优化和高级优化。基本优化包括裁剪不必要的区域，将颜色深度降至可接受的最低水平，移除图片评论以及将图片保存为恰当的格式。您可以使用任意图片编辑程序（例如，GIMP）执行基本优化。高级优化包括对JPEG和PNG文件执行进一步的压缩（无损压缩）。

**使用图片压缩工具**

市面上有许多工具可用来对JPEG和PNG文件执行进一步的无损压缩，且不会对图片质量造成任何影响。对于JPEG文件，我们建议您使用jpegtran或jpegoptim（仅适用于Linux；使用--strip-all选项运行）。对于PNG文件，我们建议使用OptiPNG或PNGOUT。

**选择恰当的图片文件格式**

您应测试一下哪种格式最适合您的图片，尽管我们在下面推荐了一些较高级别的格式：

* PNG格式几乎一直优于GIF格式，尽管某些旧版浏览器只能为PNG格式提供部分支持。
* 为较小或简单的图形（例如，小于10x10像素的图形或调色板小于3色的图形）以及包含动画的图片使用GIF格式。
* 为所有摄影风格的图片使用JPG格式。
* 请勿使用BMP格式或TIFF格式。