## WeOpsWay自动化管理平台-序篇

### 开发架构

架构采用： Python+Django,Mysql+Redis

基本功能： CMDB + Ansible/Shell管理 + 任务调度 + 应用发布 + 多云管理 + 多k8s集群管理 等

目前正在开发过程中，仅完成了一些基本的功能，刚完成了deployment的弹性收缩，版本回滚，在线通过yaml修改配置。

### 诗和远方
从运维的角度思考开发，从开发的角度思考运维。

关于IT自动化和智能化，这个话题一直都在讨论，个人觉得自动化更注重于将多云(包含容器云)，devops, os/mw/database日常运维, 多任务批量调度，工单系统，多维可视化，多平台全链路安全监控日志告警等融合集成一体化，目标应该就是AllInOne的一体化运维平台，全链路监控，流程审批，安全审计以及开发、运维、项目管理等。既能适用于运维人员，也适用于开发和项目管理人员等。

IT智能化应该更偏向于单个具体产品的使用，比如数据库智能平台，能够将数据库运维的经验以及数据库监控指标相结合，通过多维度多场景实时监控数据库，发现异常能及时告警，常见的问题能够做到故障自愈，复杂的问题能给出具体判断点做到精准定位，而我们作为使用者只需要看看告警内容然后按下流程确定键，下一步后台就可以进行自动修复了。目标很明确，实现起来却是很难，需要有相关产品运维经验丰富的专家团队，运维开发团队以及大数据量、各种应用场景支撑测试验证等等。

待续……
