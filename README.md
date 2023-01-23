# 2023新年祝福
（这个标题貌似不能完整地上传……）

我是小遛，目前是大一学生。该程序有Android和Windows两个版本。
Android版写于2023.1.20。当时没有想太多，临时写了一个ver. 1.0出来，用了大量的复制粘贴、主要是为了做一个逐帧动画的效果。编译器是“C语言编译器(C compiler)” Version 10.2.10，图标是白底蓝字。Windows版是基于Android版改来的，写于2023.1.22，所以我从ver. 2.0开始编号。这里需要感谢 @ChaseOne1 的帮助，我在“祝福语”部分加入了彩色字体，使得程序的视觉效果更丰富了。编译器是Visual Studio 2022。展示视频请见 https://www.bilibili.com/video/BV1XG4y1D7qf/

**项目创意和逻辑、代码均为本人原创。**

# 关于Android版
由于我没能找到在Android端改变输出字体颜色的方法，所以Android版的视觉效果可能更差一些。Android端的C语言编译器并不多，且质量都不是很高。我试了“C语言编译器”和“C语言编译器IDE”，最后运行出来时编译器都会出BUG，最典型的就是“HAPPY NEW YEAR”部分，如果最后一行不加“\n”，最后一行就无法在sleep结束前显示出来，而这一段代码在Windows端是完全不会出问题的。另外，Android端的代码执行速度似乎比Windows端要快两三倍，主要体现在“2022-2023”和“祝福语”两个部分，我因此有对Android版的部分代码进行了调整。最后，我的手机屏幕分辨率是2400×1080，代码运行出来可能不会在屏幕正中间，我也暂时没能找到合适的解决办法。综上，我**建议大家去看看Windows版**，Android版的不确定因素实在是太多了[捂脸]。

# 使用方法
选择合适的源代码和编译器，在编译器中编译运行即可……Windows端建议 Visual Studio 2022 或 Dev-C++ ，Android端建议 C语言编译器

# 更新日志
2023.1.23 上传了Windows版，Android版还在修改

2023.1.23 更新Windows版到ver. 2.1。**如果您的控制台窗口大小为120×30、屏幕缓冲区大小为120×9001，那么现在所有的“定格动画”应该就都能居中显示了。**

2023.1.24 更新Windows版的一些小细节，上传了Android版。
