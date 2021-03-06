# EDA-workflow
基于AI的EDA物理流程框架设计

陶东来

## 周报
### 2.27

已有进展：
完成了Detailed placement的模块剥离（opendp），对Global routing的模块（fastroute）接口进行了调整。修复了一处可能造成内存重复释放的bug。

尚在工作中：
对fastroute的剥离工作。

下周规划：
前半周进行对Detailed routing的剥离工作。之后进行全流程的接通调试工作。

### 3.6
已有进展：
完成了对fastroute和TritonRoute的模块剥离。进行了手工的测试。

下周规划：
使用Python脚本进行流程自动化，基于OpenROAD已有的测例进行测试。
