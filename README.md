# Domain-modeling
## a
### 阅读 Asg_RH 文档，按用例构建领域模型。
* 按 Task2 要求，请使用工具 UMLet，截图格式务必是 png 并控制尺寸
* 说明：请不要受 PCMEF 层次结构影响。你需要识别实体（E）和 中介实体（M，也称状态实体）
   * 在单页面应用（如 vue）中，E 一般与数据库构建有关， M 一般与 store 模式 有关
   * 在 java web 应用中，E 一般与数据库构建有关， M 一般与 session 有关

![image](https://github.com/lqAsuna/Domain-modeling/blob/master/image/result1.png)

## b
### 数据库建模(E-R 模型)
- 按Task3要求，给出系统的E-R模型（数据逻辑模型）
- 建模工具PowerDesigner（简称PD）或开源工具OpenSystemArchitect

![image](https://github.com/lqAsuna/Domain-modeling/blob/master/image/result2.png)

- 导出Mysql物理数据库的脚本

![image](https://github.com/lqAsuna/Domain-modeling/blob/master/image/result3.png)

![image](https://github.com/lqAsuna/Domain-modeling/blob/master/image/result4.png)

- 简单叙说数据库逻辑模型与领域模型的异同

相同点：

数据库逻辑模型和领域模型二者都共同关注用例和用户的参与。都展现了各个概念类的名字、属性以及彼此之间的关系

不同点：

数据库逻辑模型需要考虑一些更加细节的东西，比如每个实体的属性，主键是什么，某个实体跟其他实体是什么关系等等，同时中间态的实体也不再出现，更偏向于实际，而不是概念。

领域模型更多地只是概念模型上的设计，并没有涉及到底层的具体实现
