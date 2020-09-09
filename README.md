git config --global http.proxy 代理地址

git config --global https.proxy 代理地址

```
git config --global http.proxy http://127.0.0.1:12333
git config --global https.proxy http://127.0.0.1:12333
```



查看代理

```
git config --global --get http.proxy
git config --global --get https.proxy

```

```
git config --global --unset http.proxy   

git config --global --unset https.proxy
```

# [git设置、查看、取消代理](https://www.cnblogs.com/yongy1030/p/11699086.html)

设置代理：

```
git config --global http.proxy 'socks5://127.0.0.1:1080' 
git config --global https.proxy 'socks5://127.0.0.1:1080'
```

 

查看代理：

```
git config --global --get http.proxy
git config --global --get https.proxy
```

 

取消代理：

```
git config --global --unset http.proxy
git config --global --unset https.proxy
```