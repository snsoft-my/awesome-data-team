# Awesome Data Team
A collection of various awesome resources for data team. Welcome more resources and any updates.

- Note: To add resource file, please upload it [here](https://drive.google.com/drive/folders/190dsPqzMrcMD0_-Sjwr9FE2s0ZMC5QEi?usp=drive_link).

## Contents
- [Business Knowledge](#business-knowledge)
- [Data Analysis/Science](#data-analysis)
- [Machine Learning](#machine-learning)
- [Data Engineering](#data-engineering)

## Business Knowledge

### Guide
- [General Game Information](#general-game-information)
- [Game BI System](#game-bi-system)
- [Game Operation](#game-operation)
- [Game Data Analysis](#game-data-analysis)
- [back to top](#awesome-data-team)

### General Game Information
- [游戏葡萄](https://youxiputao.com/). 关于游戏的综合资料平台网站。

### Game BI System
- [Thinking data](https://www.thinkingdata.cn/). 一家中国游戏大数据服务商，为游戏打造一体化数据驱动解决方案，满足游戏企业全品类、全场景、全生命周期的数据需求。[A BI example by thinkingdata](https://drive.google.com/file/d/1-ULNzW6Kchtf3FPjohJ12sUuLzmxuCx7/view?usp=drive_link).


### Game Operation
- [游戏运营：高手进阶之路](https://drive.google.com/file/d/1IboLlCVc28SsOVJG4mTRFqhSlDA596fM/view?usp=drive_link). 本书完整覆盖了一个游戏运营人员日常工作中的方方面面，并从工作中具体的业务场景出发，归纳整理出各种解决问题的方法论。


### Game Data Analysis
- [游戏数据分析实战](https://drive.google.com/file/d/16EZHs9ByD_ho4NSqCuwALsez4tytcQIW/view?usp=drive_link). 本书针对游戏策划、游戏运营、游戏数据分析、产品数据分析挖掘、数据平台开发维护人员及对数据分析感兴趣的读者，介绍怎样利用数据分析游戏生命周期中各阶段遇到的问题。
- [游戏数据分析的艺术](https://drive.google.com/file/d/1bOdtfZdScjmSDeb0sK0RNtZ8gmi1w8nv/view?usp=drive_link). 本书详细剖析了游戏数据分析相关的指标、方法论、内容挖掘、数据挖掘、软件使用、游戏设计、运营策划、渠道推广、收入解读、用户分析和留存分析等。


## Data Engineering

### Guide
- [Fundmentals of Data Engineering](#fundmentals-of-data-engineering)
- [Analytics Engineering](#analytics-engineering)
- [Data Warehouse Design](#data-warehouse-design)
- [Messaging Queue](#message-queue)
- [back to top](#awesome-data-team)

### Fundmentals of Data Engineering
- [Data Engineering Wiki](https://dataengineering.wiki/Index).
- [Designing data-intensive applications: the big ideas behind reliable, scalable, and maintainable systems](https://drive.google.com/file/d/1JLTM-09WZ87EkXOA6-BIbbJkbtFU9IcH/view?usp=drive_link). A must read book for any serious data engineer.[(Chinese Version)](https://drive.google.com/file/d/1XOijYZhanKmrCSbF1ZpWENlbt6Mhiye9/view?usp=drive_link)
- [Fundamentals of Data Engineering](https://drive.google.com/file/d/1F2y11_rpKPUW_953Swylsl5eVzUtl16g/view?usp=drive_link). Learn the data engineering lifecycle and  how to apply basic critical ideas in any data environment regardless of the underlying technology.

### Analytics Engineering
- [What is analytics engineering?](https://www.getdbt.com/what-is-analytics-engineering) Explain the rational why dbt or other similar tools is introduced and how they reduce the complexity of SQL management.
- [A comparison between dbt and sqlmesh](https://sqlmesh.readthedocs.io/en/stable/comparisons/). Sqlmesh seems to be a better option than dbt core.
 - [Building a Kimball dimensional model with dbt](https://docs.getdbt.com/blog/kimball-dimensional-model). 

### Data Warehouse Design
- [数据仓库设计](https://drive.google.com/file/d/1iW9jIlwGMBl4dthQpUUnb49Y8s8IhuK3/view?usp=drive_link)，节选自《Doris实时数仓实战》，较为全面地介绍了数据建模、数仓分层、离线与实时数仓设计。
- The architecture of layers, i.e. ODS/DWD/DWM/DWS/ADS, within a data warehouse.
    - [详解数仓中的数据分层：ODS、DWD、DWM、DWS、ADS](https://juejin.cn/post/6969874734355841031). 综合介绍了数仓中的分层。
    - [通用的数据仓库分层方法](https://www.cnblogs.com/itboys/p/10592871.html). 综合介绍了数仓中的分层，互为佐证。
    - [Maxcompute 中的数仓分层](https://help.aliyun.com/zh/maxcompute/getting-started/divide-a-data-warehouse-into-layers?spm=a2c4g.11186623.0.0.54ae1617P4nOjO). 除了该“数仓分层”，还有相关资料也值得一看，包括“数据模型”，用样例表介绍了该层的作用。
- [Kimball dimension modeling](https://docs.getdbt.com/terms/dimensional-modeling). A widely adopted data modelling method in data warehouse, which is suitable for quick evolving business. (In contrast, Inmon modelling is for stable business, e.g. banking)
    - [Kimball Dimensional Data Modeling](https://www.holistics.io/books/setup-analytics/kimball-s-dimensional-data-modeling/). A summary of what is kimball dimensional modeling.
    - [Kimball Dimensional Modeling Techniques](https://www.kimballgroup.com/wp-content/uploads/2013/08/2013.09-Kimball-Dimensional-Modeling-Techniques11.pdf). Techniques of applying kimball dimensional modeling.
    - [可视化的逻辑](https://drive.google.com/file/d/1AM4m5zXpGNbtQc4UB4vPdddvSjX1g8Ti/view?usp=drive_link)。Kimball 中的维度与事实，与可视化中的维度与度量，概念是一致的，从而使建模与可视化一致。
    - [Building a Kimball dimensional model with dbt](https://docs.getdbt.com/blog/kimball-dimensional-model). Implementation with dbt.


### Message Queue

- [Apache Pulsar in Action](https://drive.google.com/file/d/146c3kVbgcrwyXwUlDBtA9F7yiHVvQi5N/view?usp=drive_link). A comprehensive and practical guide to building high-traffic applications with Pulsar.



## Data Analysis

### Guide
- [Visualization](#visualization)
- [Application in Game](#applications-in-game)
- [back to top](#awesome-data-team)

### Visualization
- [可视化的逻辑](https://drive.google.com/file/d/1AM4m5zXpGNbtQc4UB4vPdddvSjX1g8Ti/view?usp=drive_link). 节选自《数据可视化分析：tableau原理与实战》，介绍了从维度与度量出发的数据可视化思想，这也与 Kimball 维度建模的基本概念一致，参见 [Data Warehouse Design](#data-warehouse-design)。


### Applications in Game
- [游戏数据分析实战](https://drive.google.com/file/d/16EZHs9ByD_ho4NSqCuwALsez4tytcQIW/view?usp=drive_link). 本书针对游戏策划、游戏运营、游戏数据分析、产品数据分析挖掘、数据平台开发维护人员及对数据分析感兴趣的读者，介绍怎样利用数据分析游戏生命周期中各阶段遇到的问题。
- [游戏数据分析的艺术](https://drive.google.com/file/d/1bOdtfZdScjmSDeb0sK0RNtZ8gmi1w8nv/view?usp=drive_link). 本书详细剖析了游戏数据分析相关的指标、方法论、内容挖掘、数据挖掘、软件使用、游戏设计、运营策划、渠道推广、收入解读、用户分析和留存分析等。

## Machine Learning

### Guide
- [back to top](#awesome-data-team)


