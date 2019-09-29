# AnimationToPNG
3D model animation translates to frame animation.
将场景中的模型及其动画，特效粒子，透明贴图背景等组合成特殊效果，转变为帧动画，在表现力允许的情况下可大幅降低set pass call,batches等。

![Image text](https://raw.github.com/nongzhang/AnimationToPNG/master/Picture/animation.png)
![Image text](https://raw.github.com/nongzhang/AnimationToPNG/master/Picture/hierarchy.png)

场景中unitychan是模型及其动画，可以替换成实际需要的模型，特效粒子等组合，运行后会在工程根目录创建一个名为PNG_Animations的文件夹，FrameRate是帧率，一般取60比较流畅，FrameToCapture是捕获的帧，当前动画是5.17s左右，故此值取60*5.17≈310，脚本中会创建两个相机，设置好其位置，让模型可以正确渲染。

![Image text](https://raw.github.com/nongzhang/AnimationToPNG/master/Picture/show1.jpg)
![Image text](https://raw.github.com/nongzhang/AnimationToPNG/master/Picture/show2.jpg)
