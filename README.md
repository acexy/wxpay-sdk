﻿微信支付 Java SDK
------

基于官方微信SDK 3.0.9 进行了再次处理

- 版本变更

    - 3.0.12
  
        - 移除自动上报的模块

    - 3.0.11

        - 调整WXPay在未显示声明是否设置上报时，不默认为true而是从WXPayConfig获取shouldReport参数 
        - 安照JDK1.8标准调整部分代码
      
    - 3.0.10
  
      - 修复一个官方服务端升级SSL证书验证版本导致SDK以默认TLSV1进行请求被拒绝访问的问题