# Chapter1 The Essential Software Requirement —— aim

## 1. 基本概念

- 常见误区

  需求=功能？——No，需求具有很多层次。（购买商、制造商、使用者、……）



- stackholder：

  Nowhere more than in the requirements process do the interests of all the stackholders in a software or system project.

  - Customers（出钱）
  - Users（直接或间接使用产品）
  - Requirements analysts（记录并分析需求，与开发团队沟通）
  - Developers
  - Testers
  - Documentation writers
  - Project managers
  - Legal staff
  - Manufacturing people
  - Sales, marketing, field support, help desk, and other people



- IEEE对Requirement的定义：
  1. （User View）用户需要的、能解决问题或实现目标的，条件或能力
  2. （Developer View）为了满足一定的规约而生产的
  3. 所有满足1和2的条件或能力

- Sommerville的定义：

  是what不是how



## 2. 需求的层次

![2ACEED0EAAF347B250C01F4A95C14976](C:\Users\lyc\Documents\Tencent Files\1404614828\FileRecv\MobileFile\2ACEED0EAAF347B250C01F4A95C14976.png)

- 上述箭头表示的是什么关系？—— 满足 or derivation

- Business requirements：高层次的需求
- User requirements：

- Functional requirements：
- System requirements：
- Business Rules：业务规则本身不是需求，是外界强加的。
- Nonfunctional requirements：软件的质量性质的性能、描述等。（关于软件质量的描述：易维护性、可扩展性、可靠性（依靠冗余备份等技术）、……）（关于功能的描述：方便、易用、……）
- Software requirements specification**（SRS）**：功能需求、非功能需求
- Feature特征：一组逻辑上相关的功能需求（比如一个spell checker，其功能需求包括：为拼写检查器选择语言、发现拼写错误、将词添加到词典、高亮拼写错误的单词、自动纠错等）

![F4EB2FF10956BEC3999A0FEAB256E2F6](C:\Users\lyc\Documents\Tencent Files\1404614828\FileRecv\MobileFile\F4EB2FF10956BEC3999A0FEAB256E2F6.png)



## 3. 什么不是需求

设计细节 Design detail

实现细节 Implementation detail

项目规划细节 Project planning information

测试信息 Testing information



## 题外

将变化的和不变的区分开

将变化频率不同的区分开

  