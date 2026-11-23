# media-share

公开素材仓库，用于给成品（视频/图片）提供长期可用的直链。

## jellyfish / 水母发光 配音版

规格：1280×720 / 30fps / 61.0s / H.264 + AAC 192k，画面与原片码流一致（`-c:v copy`，视频流 md5 `401ed8874f1950966e70f9a232b8eb71`）。
人声按脚本秒数落点，16 句全部落在各自时间窗内；原背景音乐保留，只在人声处自动压低。

### 男声版（云健）

- MD5：`b9ee502e3fb8237608dccbf51d63d005`
- Release 资源（永久）：https://github.com/uskyu/media-share/releases/download/jellyfish-v1/shuimu-faguang-peiyin.mp4
- 仓库原始文件：https://raw.githubusercontent.com/uskyu/media-share/main/jellyfish/shuimu-faguang-peiyin.mp4
- jsDelivr CDN：https://cdn.jsdelivr.net/gh/uskyu/media-share@main/jellyfish/shuimu-faguang-peiyin.mp4

### 女声版（晓晓）

- MD5：`cab1ba3e64f0b38a7771d9f9bc624e30`
- Release 资源（永久）：https://github.com/uskyu/media-share/releases/download/jellyfish-female-v1/shuimu-faguang-peiyin-female.mp4
- 仓库原始文件：https://raw.githubusercontent.com/uskyu/media-share/main/jellyfish/shuimu-faguang-peiyin-female.mp4
- jsDelivr CDN：https://cdn.jsdelivr.net/gh/uskyu/media-share@main/jellyfish/shuimu-faguang-peiyin-female.mp4

### 网页

https://uskyu.github.io/media-share/

## tuantuan / 团团 · 烦恼其实很好打发（15s 手绘小样）

规格：1920×1080 / 24fps / 15.0s / H.264 yuv420p bt709 + AAC 192k。
画面全部由单个 HTML 的 Canvas2D `renderFrame(t)` 逐帧绘制（无任何图像/视频生成模型），线条抖动按 8fps boil 重绘，模拟手绘。

- MD5：`a3575d2773b9e8f1eac967f585953dab`
- Release 资源（永久）：https://github.com/uskyu/media-share/releases/download/tuantuan-v1/tuantuan-fannao-15s.mp4
- 仓库原始文件：https://raw.githubusercontent.com/uskyu/media-share/main/tuantuan/tuantuan-fannao-15s.mp4
- jsDelivr CDN：https://cdn.jsdelivr.net/gh/uskyu/media-share@main/tuantuan/tuantuan-fannao-15s.mp4
- 源码（单文件）：https://raw.githubusercontent.com/uskyu/media-share/main/tuantuan/tuantuan.html
