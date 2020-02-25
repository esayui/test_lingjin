工程项目基本描述：

工程描述文件：
SeriProject.xml文件，该文件记录了工程的基本布局和所有文件的相关属性。

整个工程分为三个部分：
GeneralDesign:  总计设计，即我们的需求分析

TaskSet：任务集合，即我们在需求分析中提炼出来的所有任务集，设计人员对每一个任务进行独立的分析和设计

SystemIntegration: 系统集成，即我们每个任务都设计好了（isFinished标志位为完成），则将TaskSet中的内容拷贝
到系统集成中


