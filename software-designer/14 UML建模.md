# 14 UML建模

![image-20220504145109020](http://cdn.huangxindi.com/img/image-20220504145109020.png)

重点：用例图、类图

## 用例图

![image-20220504145201608](http://cdn.huangxindi.com/img/image-20220504145201608.png)

- 包含关系 include

  如每次登记外接信息**都要**【用户登录】，故是包含关系

- 扩展关系 extend

  如每次查询书籍信息**不是都要**【修改书籍信息】，故是扩展关系

- 泛化关系

## 类图与对象图

![image-20220504145705519](http://cdn.huangxindi.com/img/image-20220504145705519.png)

多重度：

![image-20220504145738270](http://cdn.huangxindi.com/img/image-20220504145738270.png)

关系：

![image-20220504145829116](http://cdn.huangxindi.com/img/image-20220504145829116.png)

## 顺序图

![image-20220504150046150](http://cdn.huangxindi.com/img/image-20220504150046150.png)

主要考察：

- 消息：箭头来传递
- 对象名

## 活动图

![image-20220504150211187](http://cdn.huangxindi.com/img/image-20220504150211187.png)

粗横线：产生分支，即并行的线程

还有带泳道的活动图（划分对应的主体）：

![image-20220504150234062](http://cdn.huangxindi.com/img/image-20220504150234062.png)

## 状态图

![image-20220504150305885](http://cdn.huangxindi.com/img/image-20220504150305885.png)

以状态为结点，箭头为触发事件

考点：

- 填充状态
- 填充触发事件

## 通信图

![image-20220504150437794](http://cdn.huangxindi.com/img/image-20220504150437794.png)

对象：结点；消息：箭头

与顺序图类似，但时间顺序先后不明晰。与顺序图统称为交互图。

## 例题

### 例题1

![image-20220504150620591](http://cdn.huangxindi.com/img/image-20220504150620591.png)

![image-20220504150734605](http://cdn.huangxindi.com/img/image-20220504150734605.png)

![image-20220504150712937](http://cdn.huangxindi.com/img/image-20220504150712937.png)

答案：

问题3：类都是音轨，多重度0..1

问题4：

![image-20220504151737151](http://cdn.huangxindi.com/img/image-20220504151737151.png)

### 例题2

![image-20220504151821144](http://cdn.huangxindi.com/img/image-20220504151821144.png)

![image-20220504173316383](http://cdn.huangxindi.com/img/image-20220504173316383.png)

![image-20220504173331371](http://cdn.huangxindi.com/img/image-20220504173331371.png)

![image-20220504173733815](http://cdn.huangxindi.com/img/image-20220504173733815.png)

【问题3】：状态图；属性：clevel；功能：计算里程数