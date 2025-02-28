<h1 style="text-align: center;">
    复习
</h1>



### 大纲

- **密码学基本思想**
- 分类
- 基本概念
- 对称密码
  - **分组密码和序列密码的区别**
  - 分组密码
    - DES
      - S盒
        - 查表
    - AES
      - 有限域上的运算
    - SM4
      - 中国第一个商用密码标准
  - 序列密码
    - ZUC
- 非对称密码
  - **对称密码和非对称密码的优缺点**
  - 解决密钥传输问题
  - 整数分解
    - RSA
      - 求逆
  - 离散对数
    - Elgamal
    - **ECC**
  - 签名

- 密码协议
- 认证
  - **和签名的区别**



### 一

- 国家密码政策
  - 密码法
  - 网络系统分级
  - 等保
- 密码学的基本思想
  - 对数据进行伪装以隐蔽信息，使未授权者不能理解它的真实含义
- 密码学的基本概念
  - 基本思想
  - 体制模型
  - 体制分类
  - 密码学的组成
  - 密码分析
    - 理论上不可破译
      - 一次一密
      - 量子密码
    - **没有绝对安全**
      - 三分技术，七分管理
    - 攻击方法
      - 穷举攻击
      - 基于数学的分析
      - 侧信道攻击
    - 根据占有的资源分类
      - 基本假设
        - 攻击者总能获得密文
        - 知道密码算法，不知道密钥
        - 有足够的计算资源
      - 仅知密文攻击
      - 已知明文攻击
      - 选择明文攻击
      - 选择密文攻击
        - 密码算法应在该攻击下安全
  - 密码学的理论基础
    - 信息论
    - 计算复杂性理论
    - 数学
  - 密码设计的基本方法
    - 公开设计原则
    - 扩散和混淆
    - 迭代与乘积
      - 3DES



### 古典密码

- 凯撒密码



### DES

- feitel结构

- S盒
  - 6进4出
  - $b_1b_2b_3b_4b_5b_6$
    - $b_1b_6$：行
    - $b_2b_3b_4b_5$：列



### AES

- 列混淆
- spn结构



### 工作模式





### 序列密码

- 模仿一次一密
- **线性移位寄存器**
  - 反馈函数
  - 逻辑图



### Hash 函数

- 安全性



### 公钥密码

- 公钥密码基本思想
- 公钥密码的基本条件
  - 保密、安全、实用、保真
- 公钥密码的理论模型
  - 单向陷门函数
    - 基于多个数学困难问题
      - 例如RSA基于整数分解+RSA问题
    - 数学困难问题
      - **最坏的情况**
      - 整数分解
        - 强素数
      - 背包问题
        - [超递增背包问题](https://www.anquanke.com/post/id/207798)

- 基本工作方式
  - Elgamal
    - 能够抵抗选择密文攻击
    - 需要好的随机源



### RSA

- 求逆
- 求公私钥
- 大整数模幂运算



### 椭圆曲线

- 点加