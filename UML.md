## 基本构造块

### 事物
事物是对模型中具有代表性的成分的抽象

#### 结构事物
结构事物是模型中静态部分，如类Class、接口Interface、协作Collaboration、用例UseCase、主动类ActiveClass、组件Component、节点Node
#### 行为事物
行为事物是模型中动态部分，交互Interaction、状态机Statemachine、分组事物(包，package)、注释事物(注解，Note)，活动
#### 分组事物
可以把分组事物看成是一个盒子，模型可以在其中被分解。目前只有一种分组事物，即包 Package。结构事物，动作事物都有可能放在一个包中
#### 注释事物
注释事物是UML模型的解释部分

### 关系
关系用来把事物结合在一起

- 依赖Dependency -------->
- 关联Association ——————————
- 泛化Generalization ————————|>
- 实现Realization --------|>
- 聚合Aggregation —————————◇
- 合Composition —————————<>

### 图
#### 类图
展现了一组对象、接口、协作和它们之间的关系。
#### 定时图
强调消息跨域不同对象或参与者的实际时间，而不仅仅是关心消息的相对顺序
#### 部署图
软件和硬件组件之间的物理关系以及处理节点的组件分布情况
#### 包图
描述由模型本身分解而成的组织单位，以及它们之间的依赖关系

### 建模系统动态
#### 序列图
序列图描述以时间顺序组织的对象之间的交互动态视图
#### 通信图
通信图强调收发消息的的对象的结构组织。
#### 交互概览图
描述交互(特别是关注控制流)，但是抽象掉了消息和生命线

**序列图、通信图、交互概览图都是交互图**
#### 活动图
活动图是一种特殊的状态图，他展现了在系统内从一个活动到另一个活动的流程
