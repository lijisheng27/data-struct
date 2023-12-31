# 基础知识

## 一、时间复杂度

### 1、时间复杂度比较

保留高阶的
$$
O(1)<O(\log_{2}n)<O(n)<O(n\log_{2}n)<O(n^{2})<O(n^{3})<O(2^{n})<O(n!)<O(n^{n})
$$

### 2、加法规则和乘法规则

$$
T(n)=T_{1}(n)+T_{2}(n) = O(f(n)) + O(g(n)) = O(\max(f(n),g(n)))\\
T(n)=T_{1}(n)\times T_{2}(n) = O(f(n)) \times O(g(n)) = O(f(n)\times g(n)) 
$$

## 二、时间复杂度

- 忽视常数项
- 关注随循环变化的变量（如数组）
- 递归调用



## 三、数据结构的要素

- **逻辑结构**
  - **线性结构**
    - 一般线性表
    - 栈和队列
    - 串
    - 数组
  - **非线性结构**
    - 集合
    - 树
    - 图
- **存储结构**
  - 顺序存储
  - 链式存储
  - 索引存储
  - 散列存储
- **数据的运算**

