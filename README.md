# xhs_shield 
小红书shield python纯算

# 生成过程
device_id→AES 密钥扩展→加密HMAC→MD5 签名加密url→RC4 加密→Base64 包装→"XY" 前缀
# 加密字符串
get请求：
url + params + xy-common-params + xy-direction + xy-platform-info

post请求：
url + xy-common-params + xy-direction + xy-platform-info + data
<img width="939" alt="截屏2025-06-03 14 53 45" src="https://github.com/user-attachments/assets/2c1d4d01-f4d0-4548-b0e3-0f7a10e46813" />
q:1164953899
