# 密碼學

### 柯克霍夫原則

> 密碼系統的安全性應該僅僅取決於所使用的密鑰,而不是對該方案本身的保密

### 同餘代換

> 任意一個成立的模同餘式中，將 任 意 子表達式替換成一个与其同余的子表达式，同余仍成立

### 判断四则运算 |  舍九法

> ![Imgur](https://i.imgur.com/mrNLUvM.png)

> 5+8+3+7 =23   2+3 =5							3+7+2+6+6 =10+8+6=24
>
> 4+8=12             1+2 =3							2+4 = 6
>
> 5*3=15			 1+5 =6
>
> 4+2+9=15		 1+5 =6
>
> 6+6=12			  1+2=3							3不等于6     等式不成立

### 代表元

> 当模为 n 时,0~n-1均为代表元
>
> 即负数 rem 正数 取得余数也是正的

### 凯撒密码

> 往后挪三位的旋转密码
>
> ![Imgur](https://i.imgur.com/3JsheiK.png)

---

### 完美保密的安全性要求

> 随机变量 X0 , X1 ... 的概率分布是相同的

### 乘法逆元

> a * b ≡ 1 (mod m)
>
> 乘法逆元不总是存在,如 3 * 2 ≡ 0 (mod 6) 

### 四种攻击方式

> 已知明文攻击 : 通过已知明文和密文计算 密钥
>
> ![Imgur](https://i.imgur.com/t6IVaVl.png)


>唯密文攻击     : 密钥相同
>
>
>
>![Imgur](https://i.imgur.com/eoeGUd0.png)


> 选择明文攻击: 
>
> ![Imgur](https://i.imgur.com/AQ3lOMu.png)

>选择密文攻击:
>
>![Imgur](https://i.imgur.com/AWjef6L.png)

### 分组密码

> ![Imgur](https://i.imgur.com/KG7AFjq.png)

### 欧拉函数

> ![Imgur](https://i.imgur.com/gb6MiwW.png)

### 欧拉定理

>![Imgur](https://i.imgur.com/hDwc1jX.png)

### 不安全信道通信的一种尝试

>![image-20220131002804100](https://imgur.com/u1ZKTRY.png)

### 素数定理

> ![image-20220131004405107](https://imgur.com/0FEEfye.png)

### 寻找大素数

> ![image-20220131004530914](https://imgur.com/nbcpUTQ.png)
>
> ![image-20220131004625570](https://imgur.com/rMp4My3.png)

### 陷门完成数字签名

> ![image-20220131011436352](https://imgur.com/uWLBS0B.png)

### 碰撞

> ![image-20220131011906487](https://imgur.com/cMoDNNu.png)
>
> ![image-20220131011931982](https://imgur.com/BErHo4w.png)
>
> ![image-20220131012104079](https://imgur.com/YWmX1B4.png)

###　ＲＳＡ加密

> 取两个大素数 ,p q , 使得 m = (p-1)*(q-1) 不能被 3 / (r) 整除
>
> 接下来公开公钥 m ,加密使得 明文^3|明文^r (mod m)
>
> 即取得密文
