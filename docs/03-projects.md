# 03｜值得关注的开源科研项目

这里的目标不是让新手立刻去给大型项目提 PR，而是告诉你：**哪些项目值得学、应该先学到哪一步、以后怎么把它变成真正的科研/开源经历。**

## 新手层：先学会“使用”

### MATPOWER

- https://github.com/MATPOWER/matpower
- 适合：潮流、OPF、标准算例
- 先做：跑示例、改参数、记录结果
- 暂时不要做：一上来研究源代码内部结构

### pandapower

- https://github.com/e2nIEE/pandapower
- 适合：Python 电网建模、配电网、时序仿真
- 先做：复现一个网络案例，自己新增负荷/PV/储能
- 下一步：用 SimBench 等公开数据做完整 case study

### SimBench

- https://github.com/e2nIEE/simbench
- 适合：公开电网 benchmark 数据
- 先做：理解数据结构，配合 pandapower 使用

## 中等层：开始做“研究型修改”

### PyPSA

- https://github.com/PyPSA/PyPSA
- 适合：新能源、储能、容量扩张、能源系统优化
- 研究型练习：修改新能源渗透率、储能容量、成本假设、时间尺度，比较系统最优结果。

### ANDES

- https://github.com/CURENT/andes
- 适合：电力系统动态与稳定性研究
- 研究型练习：改变控制器/系统参数，比较特征值、动态响应或稳定裕度。

### OpenDSSDirect.py

- https://github.com/dss-extensions/OpenDSSDirect.py
- 适合：配电网、光伏、EV、储能、电压问题
- 研究型练习：做时序场景、多渗透率比较、异常工况测试。

## 高阶层：完成一次完整项目后再碰

### PowerModels.jl

- https://github.com/lanl-ansi/PowerModels.jl
- 适合：OPF、优化建模、算法研究
- 进入方式：先理解现有 OPF formulation，再考虑扩展约束或比较求解方法。

### Grid2Op

- https://github.com/Grid2op/grid2op
- 适合：电网运行决策、拓扑控制、智能体方法
- 进入方式：先理解环境的 observation/action/reward 和电网约束，再考虑智能算法。

## 什么才算有意义的 GitHub 成果

从弱到强，大致可以这样看：

1. Fork/收藏项目 —— 仅代表关注
2. 跑通示例 —— 学习记录
3. 自己做完整 case study —— 项目成果
4. 提交 issue —— 参与社区讨论
5. 提交 PR —— 有实际代码贡献
6. PR 被 review 并 merge —— 有外部验证的贡献
7. 多次 merge / 进入 release —— 稳定贡献者
8. maintainer/core contributor —— 很强的开源履历
9. 基于项目形成软件论文/研究论文 —— 学术成果

对第一次科研来说，**第 3 级已经足够好**。不要为了“GitHub有记录”而强行越级。

## 一个推荐顺序

MATPOWER / pandapower
→ 做一个小复现
→ PyPSA / ANDES（按方向选）
→ 自己完成一个扩展 case
→ 再考虑 issue / PR / 开源协作

科研入门的第一目标不是“让别人看见你”，而是**先让自己真正知道自己在做什么**。
