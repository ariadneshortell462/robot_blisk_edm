# 双机器人整体叶盘电火花切割项目

该项目用于双机器人协同完成发动机整体叶盘（Blisk）电火花切割（EDM）任务的流程建模与控制。通过 Python 实现任务规划、轨迹生成与设备接口管理，提升加工一致性与自动化水平。

## 项目目标

- 双机器人协同作业，保证切割路径覆盖与稳定性。
- 支持任务规划、轨迹生成与执行监控。
- 便于后续接入仿真或真实控制器。

## 目录结构（规划）

> 当前仓库为初始化版本，后续可按需扩展。

```
robot_blisk_edm/
├─ README.md
├─ .gitignore
└─ src/
   ├─ planning/        # 任务规划与路径生成
   ├─ control/         # 设备/机器人控制接口
   └─ simulation/      # 仿真与验证
```

## 环境要求

- Python 3.10+（建议使用虚拟环境）
- 依赖管理工具：pip / poetry / conda 均可

## 快速开始（占位）

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python -m src.main
```

## 开发约定

- 提交前通过格式化与静态检查（如 black / ruff）。
- 新增模块请补充说明文档与必要的示例。

## 许可证

如需开源许可证，请补充 LICENSE 文件。
