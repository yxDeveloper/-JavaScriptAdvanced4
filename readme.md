# JavaScript高级第四天

## 原型相关知识复习
### 原型链
### 函数的原型链
    可以把Funciton当做一个构造函数，其他构造函数都是这个Function构造函数的实例
    再用对象原型链的方式，去分析这个原型关系
### instansof
    判断一个构造函数的原型是不是存在于该对象的原型链上

    javascript中所有的对象 都会有  Object.prototype
    所以 所有的对象 instanceof Object 都是true
## 歌曲列表管理案例
## 递归
    自己调用自己
### 化归思想
    化繁为简，化未知为已知
### 递归的两个要素
    1.自己调用自己
    2.有递归结束条件