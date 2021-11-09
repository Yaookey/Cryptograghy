# Cryptograghy
The study route of Cryptograghy

## Introduction

**现代密码学加密类型**
|              加密类型                 |                  代表                |
|                ----                  |                  ----                |
|  对称加密（Symmetric Cryptography）   |       DES，AES，RC4 ...              |
|  非对称加密（Asymmetric Cryptography）|       RSA，ElGamal ...               |
|  哈希函数（Hash Function）            |       MD5，SHA-1，SHA-512 ...        |
|  数字签名（Digital Signature）        |       RSA ，ElGamal ，DSA ...        |


**对称加密体制分类方式**

--分组密码（Block Cipher），又称为块密码。  
--序列密码（Stream Cipher），又称为流密码。


密码设计者的根本目标是保障信息及信息系统的：
机密性（Confidentiality），完整性（Integrity），可用性（Availability），认证性（Authentication），不可否认性（Non-repudiation）。
其中，前三者被称为信息安全的 CIA 三要素。

而对于密码破解者来说，一般是要想办法识别出密码算法，然后进行暴力破解，或者利用密码体制的漏洞进行破解。
当然，也有可能通过构造虚假的哈希值或者数字签名来绕过相应的检测。

**攻击类型分类**
一般来说，我们都会假设攻击者已知待破解的密码体制，而攻击类型通常分为以下四种：
|  攻击类型   |                  说明                |
|    ----    |                  ----                |
|唯密文攻击	 |              只拥有密文               |
|已知明文攻击	|          拥有密文与对应的明文          |
|选择明文攻击	|拥有加密权限，能够对明文加密后获得相应密文|
|选择密文攻击	|拥有解密权限，能够对密文解密后获得相应明文|
