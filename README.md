# Bilibili AI 视频总结机器人

自动提取和总结B站视频内容的AI工具。

## 安装指南
### 安装步骤

1. 克隆仓库
```bash
git clone https://github.com/uwakeme/bilibili_robot.git
cd bilibili_robot
```

2. 安装依赖
```bash
pip install -r requirements.txt
```

3. 配置环境变量
```bash
cp .env.example .env
```
然后编辑`.env`文件，添加必要的API密钥和配置信息。

## 项目结构

请查看 [项目规划文档](docs/bilibili_ai_summary_bot_规划文档.md) 获取更详细的项目结构和技术细节。

## 贡献指南

1. Fork 本仓库
2. 创建您的特性分支 (`git checkout -b feature/amazing-feature`)
3. 提交您的改动 (`git commit -m 'Add some amazing feature'`)
4. 推送到分支 (`git push origin feature/amazing-feature`)
5. 创建一个 Pull Request
