#综合的学习https

1.SSL和TLS 
  TLS：传输层安全性协议，
  SSL：安全套接层，是TLS前身
2.位于协议哪一层：在tcp传输层之后，在http应用层之前
3.https = http + TLS/SSL
4.TLS/SSL实现依赖于三类基本算法
  散列函数 散列函数验证信息的完整性：MD5 SHA
  完整校验

  对称加密 对称加密算法采用协商的密钥对数据加密：AES DES
  信息加密

  非对称加密 非对称加密实现身份认证和密钥协商：RSA ECC DH
  身份验证  和   密钥协商
5.