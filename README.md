# COVID-19 Application Tracker
## 项目介绍
- `coronavirus-tracker`是一个`COVID-19`疫情追踪系统，
- 本系统采用后端`SpringBoot`构建，前端采用`Thymeleaf`编写，供`SpringBoot`学习者参考。

## 系统结构图
```
com
    └── stephen 
        └── coronavirustracker 
                ├── CoronavirusTrackerApplication.java 
                ├── controllers
                    └── HomeController.java
                ├── models 
                    └── LocationStats.java 
                └── service 
                    └── CoronaVirusDataService.java
```
## 技术介绍
- 后端主要是用`SpringBoot`的定时任务去定时解析数据集
- 本项目采用的数据集是John Hopkins大学的实时疫情数据集，但是，不包括美国的疫情数据。
- 前台采用`BootStrap`+`Thymeleaf`编写。