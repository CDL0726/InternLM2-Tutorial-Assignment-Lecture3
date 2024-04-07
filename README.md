# InternLM2-Tutorial-Assignment-Lecture3   

# Lecture3    
# 第3课 【茴香豆：搭建你的 RAG 智能助理】   
[第3课视频](https://www.bilibili.com/video/BV1QA4m1F7t4/)   
[第3课文档](https://github.com/InternLM/Tutorial/blob/camp2/huixiangdou/readme.md)  
2024.4.6  书生·浦语社区贡献者【北辰】   

## 第3课 笔记   

### RAG概述   

![](./RAG1.png)  

RAG（Retrieval Augmented Generation）技术，通过检索与用户输入相关的信息片段，并结合外部知识库来生成更准确、更丰富的回答。解决 LLMs 在处理知识密集型任务时可能遇到的挑战, 如幻觉、知识过时和缺乏透明、可追溯的推理过程等。提供更准确的回答、降低推理成本、实现外部记忆。  
RAG 能够让基础模型实现非参数知识更新，无需训练就可以掌握新领域的知识。本次课程选用的茴香豆应用，就应用了 RAG 技术，可以快速、高效的搭建自己的知识领域助手。  






## 第3课 作业  
### 基础作业 - 完成下面两个作业

#### 1. 在[茴香豆 Web 版](https://openxlab.org.cn/apps/detail/tpoisonooo/huixiangdou-web)中创建自己领域的知识问答助手

- 参考视频[零编程玩转大模型，学习茴香豆部署群聊助手](https://www.bilibili.com/video/BV1S2421N7mn)
- 完成不少于 400 字的笔记 + 线上茴香豆助手对话截图(不少于5轮)
- （可选）参考 [代码](https://github.com/InternLM/HuixiangDou/tree/main/web) 在自己的服务器部署茴香豆 Web 版

#### 2.在 `InternLM Studio` 上部署茴香豆技术助手

- 根据教程文档搭建 `茴香豆技术助手`，针对问题"茴香豆怎么部署到微信群？"进行提问
- 完成不少于 400 字的笔记 + 截图


### 进阶作业 - 二选一 

#### A.【应用方向】 结合自己擅长的领域知识（游戏、法律、电子等）、专业背景，搭建个人工作助手或者垂直领域问答助手，参考茴香豆官方文档，部署到下列任一平台。
  - 飞书、微信
  - 可以使用 茴香豆 Web 版 或 InternLM Studio 云端服务器部署
  - 涵盖部署全过程的作业报告和个人助手问答截图

#### B.【算法方向】尝试修改 `good_questions.json`、调试 prompt 或应用其他 NLP 技术，如其他 chunk 方法，提高个人工作助手的表现。
  - 完成不少于 400 字的笔记 ，记录自己的尝试和调试思路，涵盖全过程和改进效果截图

### 大作业项目选题

#### A.【工程方向】 参与贡献茴香豆前端，将茴香豆助手部署到下列平台
  - Github issue、Discord、钉钉、X
#### B.【应用方向】 茴香豆RAG-Agent
  - 应用茴香豆建立一个 ROS2 的机器人Agent
#### C.【算法方向】 茴香豆多模态
  - 参与茴香豆多模态的工作
 


