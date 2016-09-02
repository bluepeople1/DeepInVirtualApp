# DeepInVirtualApp

VirtualApp的技术文档和各个技术点拆解demo

VirtualApp 是一个 App 虚拟引擎的开源实现。 VirtualApp 在你的 App 进程内创建一个虚拟空间，你可以在虚拟空间内任意的安装、启动和卸载 APK， 这一切都与外部隔离，就如同一个沙盒。VirtualApp 亦是一个插件化框架，运行在 VirtualApp 的插件不需要任何的约束。

VirtualApp 项目地址：https://github.com/asLody/VirtualApp

这个项目可以作为VirtualApp的技术文档，严格意义上不算技术文档，是分析VirtualApp所使用的各个技术点，以及系统各个组件的启动过程和寻找hook点的过程，并从最初始踩坑的状态到完成一个低配版的双开框架，酱紫。


## 进度 
1. 第一部分demo已经提交，将VirtualApp的启动Activity部分拆解出来，重要的地方加入了注释。文档还在写中，内容较多。
注：该Demo暂时避开了ClassLoader部分的逻辑。

回归，加班了一个多月，项目终于要完啦
