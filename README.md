# SecAgent

安全代理系统框架

## 项目结构

```
SecAgent/
├── .github/           # GitHub相关配置
├── core/             # 核心代理模块
├── mcp/              # MCP工具管理
├── rag/              # RAG检索增强生成
├── skills/           # 技能模块
├── api/              # API接口
├── web/              # Web界面
├── config/           # 配置文件
├── docs/             # 文档
├── test/             # 测试
├── scripts/          # 脚本工具
└── data_example/     # 示例数据
```

## 快速开始

1. 安装依赖
```bash
pip install -r requirements.txt
```

2. 配置环境
```bash
cp config/config_template.yaml config/config.yaml
```

3. 启动服务
```bash
bash scripts/start.sh
```

## 许可证

MIT License