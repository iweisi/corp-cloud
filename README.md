# corp-cloud


## 简介
  corp-cloud是基于SpringCloud和SpringBoot实现的微服务框架。目标是打造成一套为企业搭建微服务框架的Demo和开发规范。阅读后即可参考此框架为样例和规范搭建企业级的微服务框架。


## 说明
> * 此框架使用的所有组件都为开源组件，后期有想法开发一些微服务组件</br>
> * 以SpringCloud和SpringBoot为基础，目标为打造一套企业级的微服务的开发Demo和开发规范</br>
> * 根据框架的构建情况会陆续更新博客，写出自己在搭建框架时遇到的各种坑。博客地址：`http://www.cnblogs.com/Caucasian/`，欢迎持续关注</br>
> * 欢迎大家一起完善项目,提出缺陷，提供架构思路，编码规范和更好的架构项目规范，让此项目完成目标</br>


## 项目架构
> ### 请求流程
> 客户端 -> 网关（集群，可实现客户端负载） -> 应用服务器 -> 数据库
  ![]()
