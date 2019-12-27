# README
## 说明：
根据微软支持页面得知，windows 10 自动代理**不支持** ftp://   file:// 方法获取配置文件。 [详情可见](https://support.microsoft.com/en-gb/help/4025058/windows-10-does-not-read-a-pac-file-referenced-by-a-file-protocol)


###  测试环境
1.  windows 10 版本1803+ （OS 内部版本 17134.345）
2.  获取 proxy.pac 的方法支持 http://    https:// 协议。
3. 其他平台 IOS 12+、Android 7.0+、Mac OS X。


### 注意事项
```
var proxy = HTTP_PROXY;     # HTTP_PROXY。
```
请配置 HTTP_PROXY，如果配置 SOCKS_PROXY 个别平台不支持自动代理。
