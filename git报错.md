> LibreSSL SSL_read: SSL_ERROR_SYSCALL, errno 54

1. 打开[站长工具](https://tool.chinaz.com/dns/)
2. 找到`github.com`对应的ip地址
3. 修改/etc/host文件

> fatal: 无法访问 'https://github.com/littleroot-town/token-test/'：HTTP/2 stream 1 was not closed cleanly before end of the underlying stream

git默认使用通信协议出现问题，修改默认协议

```zsh
git config --global http.version HTTP/1.1
```
