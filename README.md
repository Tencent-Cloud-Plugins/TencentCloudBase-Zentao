<p align="center">
  <img height="100px" src="./logo.jpeg" />
</p>

# [Zentao](https://github.com/idoop/zentao)

禅道是第一款国产的开源项目管理软件，可以支持研发项目进行测试管理、计划管理、文档管理、事和事务管理。

## 部署

本项目基于开源项目 [CloudBase Framework](https://github.com/Tencent/cloudbase-framework) 开发部署，支持一键云端部署

[![](https://main.qcloudimg.com/raw/67f5a389f1ac6f3b4d04c7256438e44f.svg)](https://console.cloud.tencent.com/tcb/env/index?action=CreateAndDeployCloudBaseProject&appUrl=https%3A%2F%2Fgithub.com%2FTencent-Cloud-Plugins%2FTencentCloudBase-Zentao&branch=master)
### 配置
- `ADMINER_USER`：zentao 管理员账号
- `ADMINER_PASSWD`：zentao 管理员密码


### 依赖
- CFS：使用 CFS 持久化存储数据

## 注意事项

1. 部署时，需要将服务路径设置为根路径 `/`
