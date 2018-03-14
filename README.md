## IFarm 简介

分布式架构电商系统 `Denan 17.05`

- [ifarm-parent](https://github.com/DeNan-Kong/ifarm-parent)
- [ifarm-order](https://github.com/DeNan-Kong/ifarm-order)
- [ifarm-sso](https://github.com/DeNan-Kong/ifarm-sso)
- [ifarm-rest](https://github.com/DeNan-Kong/ifarm-rest)
- [ifarm-static-web](https://github.com/DeNan-Kong/ifarm-static-web)

## Maven 目录结构
    ifarm
      ├── ifarm-parent  为父类工程，所有工程都继承这个工程，用来管理依赖jar包的版本，全局
      ├── ifarm- manager 后台系统（pom聚合工程）
      │     ├── ifarm- manager-pojo后台系统实体类，模型层
      │     ├── ifarm- manager-mapper 后台系统Mybatis映射接口与xml文件，数据访问层
      │     ├── ifarm- manager-servicer 后台系统业务逻辑层
      │     └── ifarm- manager-web后台系统web交互界面
      ├── ifarm-order 订单系统(https://github.com/DeNan-Kong/Ifarm-web)
      ├── ifarm-sso 单点登入系统
      ├── ifarm-rest Rest接口服务      
      └── ifarm-static-web 前台系统，门户界面       
