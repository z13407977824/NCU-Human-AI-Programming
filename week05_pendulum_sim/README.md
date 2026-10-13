# 第 5 周 · 单摆运动数值模拟（Pendulum Simulation）

<div align="center">

**无菌子模块工作区 · Sterile Sub-module Workspace**

实验者：**张美君**　|　学号：**7902126153**　|　专业：**食品科学与工程**

课程：南昌大学 · 人工智能编程（Human–AI Programming）

</div>

---

## 一、无菌工作区就绪状态：✅ 已就绪（STERILE / READY）

| 核验项 | 状态 | 说明 |
| --- | --- | --- |
| 目录独立性 | ✅ 纯净独立 | 仓库根目录下顶层专属目录 `week05_pendulum_sim/`，不挂载于 `experiments/week-05/`，不与其它周次共享文件 |
| 初始洁净度 | ✅ 零污染 | 本目录当前**仅含** `README.md`，无任何缓存、临时文件、虚拟环境、日志或历史残留 |
| 密钥与数据 | ✅ 零携带 | 无 API Key / `.env` / 证书；无大体积原始数据、压缩包、模型权重 |
| 依赖隔离 | ✅ 自封闭 | 后续依赖仅记录于本目录内的 `requirements.txt`，不修改仓库全局环境 |
| 编码与换行 | ✅ 统一 | 文件统一 **UTF-8**，换行符交由 Git 自动处理 |
| 版本基线 | ✅ 已锁定 | 基线提交：`feat(week05): init pendulum experiment workspace` |

> 本工作区已通过无菌核验，可安全投入实验开发。

## 二、实验主题

- **周次**：第 5 周（NumPy 数值计算）
- **题目**：单摆运动数值模拟（Pendulum Simulation）
- **目标**：用 NumPy 对单摆运动方程进行数值求解与向量化计算，输出角度—时间曲线，并与小角度解析解做误差对比，体会数值方法的精度与稳定性。

## 三、目录结构（规划）

```
week05_pendulum_sim/
├── README.md           # 本说明（无菌工作区声明）
├── code/               # 实验代码（单摆求解脚本）
├── report/             # 实验报告
├── data_sample/        # 样例小数据（体积受控）
└── notes/              # 学习记录与 AI 协作声明
```

> Git 本身不追踪空目录，各子目录在创建首个文件时自动纳入版本管理。

## 四、无菌工作区公约

1. **只进该进的**：代码、报告、样例小数据、笔记；禁止提交 `__pycache__/`、`.venv/`、`*.log`、临时文件。
2. **密钥零容忍**：任何 API Key、`.env`、证书一律不得进入本目录（已由仓库根 `.gitignore` 拦截）。
3. **依赖可复现**：新增第三方库须同步写入本目录 `requirements.txt`。
4. **结果可追溯**：每次提交前执行 `git status` 自检，确认仅包含本目录预期改动。
5. **AI 协作留痕**：由 AI 辅助生成或改写的部分，在 `notes/AI_USAGE.md` 中说明提示词要点与人工校验过程。

## 五、环境与复现

```bash
python -m venv .venv
.venv\Scripts\activate          # Windows
pip install -r week05_pendulum_sim/requirements.txt
```

- Python ≥ 3.10（推荐 3.11+）
- 主要依赖：`numpy`、`matplotlib`

## 六、基线信息

| 项目 | 内容 |
| --- | --- |
| 基线提交 | `feat(week05): init pendulum experiment workspace` |
| 分支 | `main` |
| 状态 | 工作区无菌、基线已锁定 |

---

<div align="center">

**南昌大学 · 食品科学与工程 · 张美君（7902126153）**

Week 05 · Pendulum Simulation · Sterile Workspace

</div>
