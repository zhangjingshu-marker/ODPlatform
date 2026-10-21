# tests/ — 跨端集成与端到端(E2E)测试

> 🚧 **状态**: 占位

本目录用于存放**跨越多个端**的测试代码（如：platform 产生模型 -> web-backend 提供接口 -> desktop 展示，整个链路的测试）。

**注意**：
- 单个模块或单端的单元测试，请放在各自的 `apps/xxx/tests/` 下。
- 本目录只在根 `pyproject.toml` 的 pytest 配置中被指定为全局测试发现路径。