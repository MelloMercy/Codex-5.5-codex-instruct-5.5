# Codex 5.5 / codex-instruct-5.5


[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Python 3.8+](https://img.shields.io/badge/Python-3.8%2B-blue)](https://python.org)

---




## 快速开始 / Quick Start

```bash
# 部署 GPT-5.5 指令
python codex-instruct.py

# 重启 Codex 生效
```

## 参数 / Options

| 参数 | 说明 |
|------|------|
| `--file`, `-f` | 使用外部 `.md` 指令文件 |
| `--name`, `-n` | 输出文件名不含 `.md`（默认 `gpt5.5-unrestricted`） |
| `--dry-run` | 预览，不实际修改 |
| `--codex-dir` | 手动指定 `.codex` 目录 |


## 还原 / Undo

```bash
# 删除 config.toml 中的 model_instructions_file 行
# 删除 ~/.codex/gpt5.5-unrestricted.md
# 重启 Codex
```

## 项目结构 / Layout

```
codex-instruct-5.5/
├── codex-instruct.py                    # 主脚本
├── examples/
│   └── gpt5.5-unrestricted.md           # 指令独立副本
├── .gitignore
├── README.md
└── LICENSE                              # MIT
```

## 声明 / Disclaimer

利用官方配置机制，不修改二进制、不劫持网络、不篡改进程。风险自负。

Exploits official config mechanism. No binary mod, no MITM, no process tampering. Use at your own risk.

## License

MIT
