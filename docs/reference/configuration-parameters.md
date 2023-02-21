---
sidebar_position: 1
---

# 配置参数

`Conch 海螺` 主要使用两种配置参数：配置文件 和 环境变量。

## 配置文件

您可以在 [GitHub Docs](https://github.com/project-senjuko/conch/main/docs/Config.template.toml)
中取得一个配置文件模板。

## 环境变量

| 键                  | 值         | 可选  | 备注               |
|--------------------|-----------|:---:|------------------|
| SJKCONCH_CONFIG    | 指向配置文件的路径 |  √  | 默认：`Config.toml` |
| SJKCONCH_LOG_LEVEL | 日志输出等级    |  √  | 默认：`info`        |
| SJKCONCH_DATA_PATH | 指向数据目录的路径 |  √  | 默认：`goconch`     |
