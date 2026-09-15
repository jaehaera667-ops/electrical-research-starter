# 02｜电气科研工具箱

只列适合科研、值得长期认识的工具。第一次不要全学，**选一个跑通即可**。

## 第一梯队：最适合新手

### MATPOWER

- 官方仓库：https://github.com/MATPOWER/matpower
- 语言：MATLAB / Octave
- 用途：潮流、最优潮流（OPF）、标准电力系统算例
- 难度：★☆☆☆☆
- 第一个任务：跑通一个标准算例，修改负荷后比较节点电压和线路潮流。

为什么推荐：资料多、概念直观、非常适合把本科电力系统知识和科研计算接起来。

### pandapower

- 官方仓库：https://github.com/e2nIEE/pandapower
- 语言：Python
- 用途：配电网/输电网建模、潮流、OPF、短路、时序计算
- 难度：★★☆☆☆
- 第一个任务：创建或载入一个简单网络，修改负荷/PV出力并比较电压变化。

为什么推荐：如果你未来更想用 Python，它是很好的第一站。

## 第二梯队：完成第一次复现后再学

### PyPSA

- 官方仓库：https://github.com/PyPSA/PyPSA
- 语言：Python
- 用途：电力/能源系统优化、容量扩张、储能、多能源耦合
- 难度：★★★☆☆
- 第一个任务：跑官方示例，理解 snapshots、generators、loads、storage units。

适合：新能源规划、储能、能源系统优化。

### OpenDSS / OpenDSSDirect.py

- Python 接口：https://github.com/dss-extensions/OpenDSSDirect.py
- 用途：配电系统时序仿真、分布式电源、电压分析
- 难度：★★★☆☆
- 第一个任务：载入一个配电网算例，做 24h 负荷/PV 时序计算。

适合：配电网、光伏、EV、储能、电压问题。

### SimBench

- 官方仓库：https://github.com/e2nIEE/simbench
- 用途：标准化电网测试数据集，可配合 pandapower
- 难度：★★☆☆☆
- 第一个任务：载入一个公开测试网，查看其规模和元件类型。

## 第三梯队：有明确研究问题后再学

### PowerModels.jl

- 官方仓库：https://github.com/lanl-ansi/PowerModels.jl
- 语言：Julia
- 用途：电力系统优化、OPF 研究
- 难度：★★★★☆
- 适合：优化算法、数学建模更深入的项目。

### ANDES

- 官方仓库：https://github.com/CURENT/andes
- 语言：Python
- 用途：电力系统动态仿真、稳定性分析
- 难度：★★★★☆
- 适合：小扰动、暂态、动态模型。

### Grid2Op

- 官方仓库：https://github.com/Grid2op/grid2op
- 语言：Python
- 用途：电网运行、智能体/强化学习环境、拓扑控制
- 难度：★★★★☆
- 适合：已经完成基础电力系统仿真后，再探索智能化运行。

## 第一次怎么选

- MATLAB 比较熟 → **MATPOWER**
- Python 更顺手 → **pandapower**
- 想做新能源/储能规划 → 完成前两者后再上 **PyPSA**
- 想回到稳定性方向 → 后续看 **ANDES**

**不要把“安装很多工具”当成科研进展。跑通一个、解释一个、改动一个，比收藏十个更有用。**
