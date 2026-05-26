# 计算机网络课程设计——某学院校园网规划与设计

同济大学 计算机科学与技术学院 计算机网络课程设计（题目三）。

## 项目简介

针对某学院 1900 台个人计算机和 50 台服务器的网络接入需求，综合运用 VLAN 划分、三层路由交换、静态路由（兼顾 RIP 方案）等核心技术，完成从 IP 地址规划、拓扑设计到设备配置的全流程网络规划，并借助 Cisco Packet Tracer 7.3.0 进行仿真验证。同时设计了学院网站原型（HTML/CSS）。

## 项目结构

```
├── 计算机网络课程设计报告.md          # 课程设计报告（Markdown）
├── 计算机网络课程设计报告.tex         # 课程设计报告（LaTeX 源码）
├── 计算机网络课程设计报告.pdf         # 课程设计报告（PDF）
├── 计算机网络课程设计_题目3.pkt       # Packet Tracer 仿真文件
├── figures/                           # 图片资源
│   ├── fig1-topology.png              # 网络拓扑图
│   ├── fig2-test1.png ~ fig6-test5.png# 测试截图
│   └── tongji.png                     # 学院统计信息图
├── webpage/                           # 学院网站原型
│   ├── index.html                     # 首页
│   ├── teaching.html                  # 教学平台
│   ├── research.html                  # 科研成果
│   ├── news.html                      # 新闻动态
│   └── contact.html                   # 联系我们
```

## 指导教师

田春岐

## 技术栈

- **仿真平台**：Cisco Packet Tracer 7.3.0
- **设备**：Cisco Catalyst 3560 三层交换机、Cisco 2960 二层交换机
- **核心协议**：VLAN、Inter-VLAN Routing、静态路由、RIP
- **报告**：LaTeX / Markdown
- **网站**：HTML + CSS

## 许可证

[MIT](LICENSE)
