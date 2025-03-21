# Gesture.js

## 项目介绍
本项目是一个基于手势识别的虚拟鼠标控制系统。通过摄像头捕捉用户的手部动作，利用 TensorFlow.js 和 Handpose 模型 实时检测手部关键点，并根据关键点的位置和距离判断手势，最终控制虚拟鼠标的移动和点击。该项目结合了前端开发、机器学习和数学算法，提供了一种无需物理鼠标的交互方式。
<
### 技术栈
* [Webcam API]()
* [Tensorflow]()

## 功能
1. 手势识别：
* 支持多种手势识别，包括点击、V字手势、张开手掌、OK手势、拇指向上等。
* 使用归一化的手部尺寸进行手势判断，确保识别的鲁棒性。
2. 虚拟鼠标控制：
* 根据手势识别结果，控制虚拟鼠标的移动和点击。
* 使用卡尔曼滤波器平滑鼠标移动，避免抖动。
3. 状态机管理：
* 通过状态机管理手势状态，确保手势识别的稳定性。
* 支持手势状态的平滑过渡，避免误判。
4. 自定义参数：
* 提供可配置的参数，如手势判断阈值、卡尔曼滤波器参数等。

-详情请运行demo.index查看-
## 许可证

根据 MIT 许可证分发。打开 [LICENSE.md](LICENSE.md) 查看更多内容。

## 参考资料

* [MoonShot AI开放平台 文档](https://platform.moonshot.cn/docs/intro#%E6%96%87%E6%9C%AC%E7%94%9F%E6%88%90%E6%A8%A1%E5%9E%8B)
* [OpenAI Platform](https://platform.openai.com/docs/overview)
* [DeepSeek+Chatbox+Prompt：搭建AI搭档记录](https://zhuanlan.zhihu.com/p/17651541211)
* [Chatbox AI官网：办公学习的AI好助手，全平台AI客户端，官方免费下载](https://chatboxai.app/zh)


## 开发日志

* [ai-chatbox标签的模拟实现-开发日志](https://blog.csdn.net/2401_87362551/article/details/146168935?spm=1001.2014.3001.5502)
