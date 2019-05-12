# Regression（回归）

## 回归可以用来做什么？
 - 股票预测：Input 股票历史数据，Output 明日股票数据
 - 自动驾驶：Input 周围障碍物情况，Output 方向盘角度
 - 推荐系统：Input 使用者A，商品B，Output 购买商品的可能性

## 用Regression来预测Pokemon进化后的CP值
### Step1: Model
 - Input 10只Pokemon的相关数值（当前CP值，体重，种类等），Ouput它进化后的Pokemon的CP值
 - $ y=b+\sum w_i x_i $ 
### Step2: Goodness of Function
 - 需要有一个function来评估之前的functions的好坏，把这个function叫做 Loss Function $L$ （损失函数）
 - $L(f)=L(w,b)=\sum\limits_{n=1}^{10}(y^n-(b+w\times x^n_{cp}))^2$
 - 数值越大表示function越不好
### Step3: Best Functon
- $f^*=arg\min\limits_f L(f) $
- ${w^*,b^*}=arg\min\limits_{w,b} L(w,b) $
- ${w^*,b^*}=arg\min\limits_{w,b} \sum\limits_{n=1}^{10}(y^n-(b+w\times x^n_{cp}))^2 $ $
- 找到使得损失函数最小的w和b，如何找到呢，运用 Gradient Descent，梯度下降
- 梯度下降，对参数w求导，求出来损失函数的斜率，再乘上参数n，把值加在参数w上，得到w0
- $ x=y $ 
- 1223
- 
