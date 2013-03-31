[AlloyImage](http://alloyteam.github.com/AlloyPhoto/) - 基于HTML5技术的专业图像处理库
===========================

### 功能特性

####强大功能
1. 基于多图层操作             -- 一个图层的处理不影响其他图层
2. 与PS对应的17种图层混合模式 -- 便于PS处理教程的无缝迁移
3. 多种基本滤镜处理效果       -- 基本滤镜不断丰富、可扩展
4. 基本的图像调节功能         -- 色相、饱和度、对比度、亮度、曲线等


####便捷开发
1. 简单快捷的API              -- 链式处理、API简洁易用、传参灵活
2. 多种组合效果封装           -- 一句代码轻松实现一种风格
3. 友好参数支持               -- 中、英文参数双向支持，降低专业词汇记忆门槛
4. 接口一致的单、多线程支持   -- 单、多线程切换无需更改一行代码，多线程保持快捷API特性
5. 可预见的错误友好提醒       -- 对一些可能出现错误的地方提醒，方便开发与调试


####丰富扩展
1. 方便的添加功能扩展         -- 轻松添加滤镜插件
2. 为扩展提供数学封装         -- 封装了一些数学模块供扩展调用

### 如何构建源码？

首先使用git clone复制一份AlloyPhoto的代码到本地：
```sh
 git clone git://github.com/AlloyTeam/AlloyPhoto.git
```
然后使用npm安装[modjs](https://github.com/modulejs/modjs)：
```sh
 npm install -g modjs
```
安装成功后:
```sh
cd AlloyPhoto && mod dist
```
构建成功后会在 `./js/combined`目录下生成`alloyimage.js`文件

### 变更历史

#### AlloyImage 1.1
1. 优化代码，组合效果处理性能提升80%
2. 添加木雕组合效果

#### AlloyImage 1.0
