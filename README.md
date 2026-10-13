# 文字刺绣小工具

仓库根目录会进入 `stitch/`，这里是从原项目整理进来的完整刺绣工作台。

原项目入口：<https://hijessie.space/stitch/>

原作者：**hi.Jessie** · <https://hijessie.space/>

## 功能

- 中文、英文、数字逐字手写绣线
- 即时输入和逐针动画，带针、引线和收针效果
- 多种绣线、混色线、布料、桌面和边框样式
- 字体大小、对齐、垂直位置、图案、照片贴布、手绘和剪刀工具
- 撤销、历史页、PNG/JPG、GIF、视频和 DST 导出
- 支持移动端触摸操作
- 字体和 GIF 编码器资源随项目本地提供，离线运行不依赖原站

## 本地运行

```bash
python -m http.server 5173
```

然后打开 <http://127.0.0.1:5173/>。

直接双击 `index.html` 也可进入 `stitch/`，但本地服务器更适合测试字体资源和导出功能。

## 来源与授权

迁移来源、作者署名与核验范围见 [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)。原站 `hijessie.space/stitch/` 页面没有显示可核实的代码许可证；本仓库根目录的 MIT `LICENSE` 不适用于该原站内容，也不表示原站代码已获再分发授权。

随项目分发的 Xiaolai 和 LXGW WenKai 字体按 SIL Open Font License 1.1 授权。完整许可正文、各字体版权声明及 WenKai 附加许可见 [`stitch/fonts/`](stitch/fonts/)。随附的 `gifenc.js` 采用 MIT License，完整文本见 [`stitch/vendor/LICENSE.gifenc.txt`](stitch/vendor/LICENSE.gifenc.txt)。

网页中的字形和材质是浏览器刺绣视觉模拟，不是实体绣花机控制程序。
