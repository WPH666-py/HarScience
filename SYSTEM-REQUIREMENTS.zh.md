# HarScience 运行环境

## 操作系统
- Windows 10 / Windows 11，64 位（x64）
- 依赖 WebView2（Windows 11 默认包含；Windows 10 缺失时安装程序会提示）

## 硬件建议
- CPU：x64 双核以上
- 内存：最低 4 GB，建议 8 GB 以上
- 磁盘：建议预留 3–4 GB
- 显卡：无独立显卡要求，CAD 3D 预览使用 WebGL

## 运行时
安装包已内置 Node.js、pnpm、Python 及科学计算依赖，无需用户单独安装开发环境。

## 网络
- 安装与首次启动可离线，直接使用内置 seed
- 调用云端大模型、插件市场、检查更新需要网络
- 移动端访问需要电脑与手机在同一局域网

## 模型凭证
可在应用设置中配置，或使用 `%USERPROFILE%\.dsh\.credentials.yaml`，也支持 `DEEPSEEK_API_KEY` 环境变量。

## 移动端
电脑打开“移动访问”后，手机浏览器访问显示的局域网链接；防火墙需放行对应端口。应用重启后密钥会变化，以当前链接为准。

## 可选专业软件
SolidWorks、AutoCAD、FreeCAD、Fusion 360、Onshape 为可选能力，未安装不影响主程序启动。
