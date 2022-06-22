* 设置全局代理

```
git config --global https.proxy socks5://127.0.0.1:1087
git config --global http.proxy socks5://127.0.0.1:1087
```

* 取消全局代理

```zsh
git config --global --unset https.proxy
git config --global --unset http.proxy
```

