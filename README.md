# 关于本人 👯

## 个人信息 📫

|||||
|:----|:----: |:---|:---:|
|  姓名：|aojdong| 性别： | 男|
| 出生日期：| 1999.10|籍贯：|贵州省|
| 手机：| 1****2 |电子邮箱：|132****986@qq.com|
|工作年限：|3.5年|岗位：|研发工程师|
|||||

## 教育经历 🌱
2016.9~2020.7 &emsp; 贵州大学 &emsp;&emsp; 计算机科学与技术专业&emsp;&emsp;本科

## 工作经历 🔭
2020.7~至今 &emsp; 成都鼎桥通信技术有限公司 &emsp;&emsp; 软件开发工程师

## 专业技能 😄
*	语言层面熟悉go、python，了解C/C++，java等，前端了解js、c#、vue等
*	熟悉pytorch框架，理解深度学习进行模型训练，熟悉昇腾NPU应用业务。
*	熟悉k8s、docker使用、问题定位和web微服务开发调试。
*	熟悉Linux环境下进行开发，编写使用shell脚本
*	熟悉nginx网关、prometheus/grafana资源监控等常用开源组件服务。



## 项目经历 👋

* 2020.07~2021.7 &emsp;&emsp; **pytorch框架适配项目** ✨
    * 项目介绍：
      昇腾NPU芯片需要适配pytorch框架加以完善昇腾AI生态， pytorch框架需要进行算子适配和模型适配。
    * 项目特性：
    1. 算子适配 ⚡
        - 特性描述： 当前pytorch仅支持CPU和GPU进行计算，要求新增NPU支持，pytorch的计算实际上是由大量的算子支撑的，算子就是指加减乘除或者组合的公式，当前pytorch下的NPU支撑算子框架已经搭建完成了，但是需要对每一个算子一一去适配和验证功能和精度。
        - 项目职责/成果：
            1. 担任MDE角色，对算子适配进行设计、开发、验证。
            2. 参与算子API自动化泛化测试开发。
            3. 累计输出适配算子50+，输出相关经验文档20+
    2. 模型迁移适配 ⚡
        - 特性描述：尽管pytorch对于NPU已经完成了大多数的算子支持, 但是实际使用和客户交付上是一个个的模型，而模型里用到的算子往往容易漏掉，而且算子之前可以会影响导致模型精度性能存在问题。       
        - 项目职责/成果：
            1. 担任模型适配FO角色，对模型适配进行设计、开发、验证。
            2. 成功交付一个模型，并输出相关经验文档，为后续其他同事承接模型需求做了好的开端。



* 2021.07~至今 &emsp;&emsp; **MindX DL项目** ✨
    * 项目介绍：
      为了昇腾NPU芯片在云原生k8s上方便使用，完善昇腾AI生态，MindX DL项目成立，基础组件包括ascend-device-plugin、hccl-controller、volcano等。基于基础组件，后续成立了一站式AI模型训推一体平台，主要面向科研院校、实验室，帮客户快速搭建基于NPU服务器的深度学习环境，平台组件包含10多项。
    * 项目特性：
    1. 平台组件开发 ⚡
        - 特性描述： DL平台项目设计组件从前端到后端，包括API-gateway、用户管理、集群管理、数据管理、数据集管理、镜像管理、模型管理、开发环境、训练推理、模型转换任务管理、监控运维等。基于k8s集群，以微服务方式提供restful接口交互，主要使用go进行开发。
        - 项目职责/成果：
            1. 担任MDE，完成相关需求开发。
            2. 主要负责API-gateway和监控运维两个组件迭代需求的设计、开发和维护。
            3. 处理平台问题单50+，基本涉及平台所有组件。
    2. 基础组件开发 ⚡
        - 特性描述：DL基础组件是NPU能在K8S上使用的基础，提供了设备发现、设备调度、芯片监控等功能。
        - 项目职责/成果：
            1. 担任MDE，完成相关需求开发。
            2. 主要负责npu-exporter和device-plugin两个组件的迭代需求的设计、开发和维护。包括监控指标处理、算力切分场景适配等。
            3. 处理问题单50+，支撑解决多处现场问题。
            4. 输出相关经验/知识总结文档20+

## 个人博客 💬
* [GitHub Pages](https://aojdong.github.io/)
* [CSDN](https://blog.csdn.net/m0_66978024?type=blog)

<!--
**aojdong/aojdong** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
