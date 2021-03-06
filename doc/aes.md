# AES (Advanced Encryption Standard，AES）

密码学中的高级加密标准（Advanced Encryption Standard，AES），又称Rijndael加密法，是美国联邦政府采用的一种区块加密标准。

对称/分组密码一般分为流加密(如OFB、CFB等)和块加密(如ECB、CBC等)。对于流加密，需要将分组密码转化为流模式工作。对于块加密(或称分组加密)，如果要加密超过块大小的数据，就需要涉及填充和链加密模式。

## DES (Data Encryption Standard)

 DES算法全称Data Encryption Standard，即数据加密标准，是一种对称加密算法。

 也许你更早接触到的是RSA算法——非对称加密算法的代表，它的一个典型应用是在ssh无密码登录中生成一对公钥、私钥。但是，RSA算法有一个致命缺点：处理速度很慢，因此只适合加密安全性要求极高而又较短的信息。相比之下，DES处理速度则快多了，可用于加密信息比较长的场合。

DES算法的入口参数有三个：Key、Data、Mode。  
其中Key为8个字节共64位，是DES算法的工作密钥；Data也为8个字节64位，是要被加密或被解密的数据；Mode为DES的工作方式，有两种：加密或解密。  
DES算法把64位的明文输入块转变为64位的密文输出块，它所使用的密钥也是64位。

## 3DES

DES 的常见变体是三重 DES（3DES）, 使用 168 (56*3)位的密钥对资料进行三次加密(3次使用DES)的一种机制；它通常（但非始终）提供极其强大的安全性。

## Reference

- [常用加密算法概述](https://www.cnblogs.com/colife/p/5566789.html)
- [PKCS#5填充方式](http://blog.csdn.net/test1280/article/details/75268255)
