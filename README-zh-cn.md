# florr.io 自动刷 sszone 脚本

[English Version](./README.md)

## 部署 (python3.9.15)

运行

```bash
pip install -r py39-requirements.txt
python ./main.py
```

项目依靠 yolov10(ultralytics)运行。如果你遇到关于其安装问题，请参考 https://github.com/ultralytics/ultralytics。

使用 pytorch-gpu 获得更好的性能。（需要CUDA及cuDNN)

运行

1. 打开你的 florr 页面 https://florr.io/
2. 确保你的 florr 浏览器页面全屏 (F11)
3. 请一直保持浏览器页面置顶
4. 最大化你的 florr 地图 (M)
5. 运行此脚本
6. 将鼠标移至屏幕边缘停止脚本

## 配置

```
config.json
```

其中你可以设置 `ShowLogger`为true来查看状态

将 `Builds`设为你要刷 sandstorm 时的 build 号(0~9)

若无法攻击到 sandstorm，请适当调小 `SafeDistanceK`的数值(>0)

如果你不喜欢打 mythic sandstorm，你可以降低 `Weights`中 `Mythic`的值

## 效率 (持续运行1周)

gg
![img1](./images/d24908a3674099ce689e4590b91194a.png)
![img2](./images/d659c6445517a172bb1f89b25015adc.png)

| Rarity   | Sand | Stick | Glass |
| :------- | ---- | ----- | ----- |
| Epic     | 22k  | 12k   | 19k   |
| Lgendary | 6k   | 5k    | 6k    |
| Mythic   | 26   | 13    | 31    |
