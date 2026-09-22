# OpenDuck-mini · 项目制作展示 🦆

开源仿生小鸭子机器人 **OpenDuck-mini** 的完整搭建记录。

- **制作周期**：2025.04.13 – 2025.05.12（约一个月）
- **内容**：36 张实拍照片 + 2 段演示视频
- **板块**：物料清点（BOM）→ 装配过程 → 最终成果 → 视频演示

## 在线访问

👉 https://torloy764.github.io/openduck-mini-photo/

## 本地预览

```bash
cd website
python -m http.server 8000
# 打开 http://localhost:8000
```

## 说明

- `index.html` 为纯静态单页，照片在 `images/`，视频在 `videos/`（已从 HEIC/HEVC 转为浏览器通用格式）
- 想增删照片：编辑 `index.html` 中的 `DATA` 数组，每张照片一行
