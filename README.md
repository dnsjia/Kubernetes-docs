# Kubernetes 中文安装指南

#### 文档版本定期与官网版本同时更新
  本项目致力于提供kubernetes集群二进制高可用部署文档，帮助运维/企业/快速落地k8s应用。同时讲解主要参数配置和生产环境注意事项；
虽然kubernetes部署方式多种多样，但是我们建议您使用二进制方式部署、这将更有利于您理解系统各组件交互原理和熟悉组件启动参数。有利用于查解决实际问题。
 


Note:
1. **个人/企业用户新购阿里云产品ECS RDS，除aliyun官网有新购优惠外
另可返部分现金到个人账户，如有需要请联系群主。**
2. **为了避免包冲突，请使用纯净的CentOS Minimal安装出来的OS来部署集群**

常见排错说明在此：
https://www.ziji.work/kubernetes/kubernetes-question-answer-special.html



文档基于:
  - Ubuntu 16.04
  - CentOS 7
  - Suse Linux

其他系统需要读者自行替换部分命令;


## 组件版本

- kubernetes
- etcd		
- docker	
- calico/node	
- flannel
- coredns
- haproxy
- keepalived	
  - 附：集群用到的所有二进制文件已打包好供下载 [https://k8s.ziji.work](https://k8s.ziji.work)



## 快速部署
你可以使用Luban快速搭建kubernetes测试环境/开发环境/生产环境； https://github.com/dnsjia/LuBan




## 推荐阅读

- [kubeadm快速安装kubernetes v1.14.3](https://www.ziji.work/kubernetes/kubeadm-installtion-kubernetes1-14-3.html) 原理和实践指南。
- [生产环境kubernetes1.13.6部署指南](https://www.ziji.work/kubernetes/production-kubernetes1-13-6-deployment-guide.html) 原理和部署章节。
- [kubernetes v1.11.4集群部署-安装教程](https://www.ziji.work/kubernetes/kubernetes-1-11-cluster-deployment.html) 二进制手工部署。





## 沟通交流

- QQ交流群：548246072，微信公众号`自记小屋`，请备注（城市-github用户名），验证通过会加入群聊。

Copyright 2019 micheng (safemonitor@outlook.com)

Apache License 2.0，详情见 [LICENSE](LICENSE) 文件。
