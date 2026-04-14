# openclaw-keys

RobotQu OpenClaw Key Authorization System

## 用途

用于存储 OpenClaw 授权 Key 列表，客户端验证脚本会从这个仓库获取有效 Key 进行验证。

## 文件结构

- server/valid_keys.json - 有效 Key 列表（由管理员管理）
- client/verify-key.ps1 - 客户端验证脚本

## 使用方法

详见：[docs/使用说明.md](docs/使用说明.md)