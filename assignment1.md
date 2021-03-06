 [Back](./)

# 系统分析与设计 HW 1

{:.no_toc}

* 目录
{:toc}

## 一、简答题
### Q1. 软件工程的定义

1. 将系统化、规范化、可度量的方法应用与软件的开发、运行和维护的过程，即将工程化应用于软件中。
2. 对（1）中所述方法的研究。 

 –– IEEE Standard 610.12

### Q2. 解释导致 software crisis 本质原因、表现，述说克服软件危机的方法
- #### software crisis（软件危机）：

  软件危机表现为计算机的发展导致软件危机，计算能力越强大，编程越是大问题，计算能力按摩尔定律发展，软件处理的问题也越来越广、越来约复杂。
  软件的本质决定了软件开发的困难，Brook 总结其本质特性为四个：
  * complexity 复杂性
  * conformity 一致性
  * changeability 可变性
  * invisibility 不可视性

- #### 软件危机的主要表现有：
  1. 进行了超预算的项目
  1. 项目长期无法完成
  1. 软件非常低效
  1. 软件质量低下
  1. 软件经常与用户的需求不匹配
  1. 项目难以管理
  1. 程序代码的后期维护存在困难
  1. 软件无法完成并交付

- #### 克服的方法：

  构建软件生产的最佳实践与相关知识的框架，指导软件工程人才的培养与学科建设。
  研究软件生产的客观规律性，建立与系统化软件生产有关的概念、原则、方法、技术和工具，指导和支持软件系统的生产活动，以期达到降低软件生产成本 、改进软件产品质量、提高软件生产率水平的目标。

### Q3. 软件生命周期。

在时间维度，对软件项目任务进行划分，又成为软件开发过程。常见有瀑布模型、螺旋模型、敏捷的模型等。
软件开发过程是软件开发的开发生命周期（software development life cycle），其各个阶段实现了软件的需求定义与分析、设计、实现、测试、交付和维护


### Q4.SWEBoK 的 15 个知识域（[An Overview of the SWEBOK Guide](https://www.sebokwiki.org/wiki/An_Overview_of_the_SWEBOK_Guide) 请中文翻译其名称与简短说明）？

15 个知识域分别是软件需求、软件设计、软件构造、软件测试、软件维护、软件配置管理、软件工程管理、软件工程过程、软件工程模型和方法、软件质量、软件工程职业实践；以及4个软件工程教育基础知识域――软件工程经济学、计算基础、数学基础和工程基础
软件需求：需求获取、需求分析、需求描述、需求确认、需求跟踪、需求验证、需求澄清、需求变更、需求控制等；

1. 软件需求：即软件需求 
1. 软件设计：概要设计（体系结构、组件、接口、特征过程）、详细设计等； 
1. 软件构造：程序编码等；
1. 软件测试：单元测试、集成测试等；
1. 软件维护：问题响应、问题分析、问题处理等；
1. 软件配置管理：配置过程、配置控制、版本管理等；
1. 软件工程管理：启动、规划、实施、监控、结束等；
1. 软件工程过程：过程定义、过程改进等；
1. 软件工程模型和方法：常用的模型如瀑布模型、快速原型模型、增量模型、螺旋模型、迭代模型、统一过程模型、敏捷模型等；
1. 软件质量：目标、评审、总结报告等；
1. 软件工程职业实践：选择性知识、经验积累。
1. 12 13 14 15为4个教育基础知识域：即教育需掌握基本的知识

### Q5. 解释 CMMI 的五个级别。例如：Level 1 - Initial：无序，自发生产模式。

* Maturity Level1 - Initial初始级：无序，自发生产模式。软件过程是无序的，有时甚至是混乱的，对过程几乎没有定义，管理是反应式的。
* Maturity Level 2 - Managed可管理级：建立了基本的项目管理过程来跟踪费用、进度和功能特性。制定了必要的过程纪律，能重复早先类似应用项目取得的成功经验。
* Maturity Level 3 - Defined 已定义级：已将软件管理和工程两方面的过程文档化、标准化，并综合成该组织的标准软件过程。所有项目均使用经批准、剪裁的标准软件过程来开发和维护软件，软件产品的生产在整个软件过程是可见的。
* Maturity Level 4 - Quantitatively Managed量化管理级：分析对软件过程和产品质量的详细度量数据，对软件过程和产品都有定量的理解与控制。管理有一个作出结论的客观依据，管理能够在定量的范围内预测性能。
* Maturity Level 5 - Optimizing优化管理级：过程的量化反馈和先进的新思想、新技术促使过程持续不断改进

### Q6. 用自己语言简述 SWEBok 或 CMMI （约200字）
SWEBok即软件工程知识体系指南（Guide to the Software Engineering Body of Knowledge)，是一个得到普遍认可的共识性软件工程本体知识结构。
该指南的发布使人们达成了共识：建立科学有效的软件工程本体知识结构，以解决软件工程工程师的资格认证、设置并检验软件工程项目难题等问题，为软件工程学科的学习范畴提供统一的认知。一言以蔽之：SWEBok交待了什么是软件工程，软件工程需要学什么和需要做什么。因此，SWEBOK全面描述了软件工程实践所需的知识，为开发本科软件工程教育计划打下了基础，为计算机科学的发展做出了非常大的贡献。


二、解释 PSP 各项指标及技能要求：
阅读《现代软件工程》的 PSP: [Personal Software Process 章节](http://www.cnblogs.com/xinz/archive/2011/11/27/2265425.html) 。按表格 PSP 2.1

|PSP2.1||
|:--------:| ----------- |
|Planning|计划
| Estimate| 明确需求和其他因素，估计以下的各个任务需要多少时间
| Development|开发
| Analysis| 分析需求
| Design Spec|生成设计文档 
| Design Review|设计复审 (和同事审核设计文档) 
| Coding Standard|代码规范 (为目前的开发制定合适的规范)
| Design|设计
| Coding|具体编码
| Code Review|代码复审
| Test|测试（包括自我测试，修改代码，提交修改）
| Record Time Spent|记录时间花费
| Test Report|测试报告
| Size Measurement|计算工作量
| Postmortem|事后总结
| Process Improvement Plan|提出过程改进计划

