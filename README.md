# github_user_guide

## 参考资料
- https://226yzy.com/2021/122151725.html
- https://www.bilibili.com/video/BV1Vh41187ik
- https://blog.csdn.net/wsmrzx/article/details/115793236
- https://blog.csdn.net/qq_39098813/article/details/82315159

## 0 手册目标
- 从GitHub上下载资源
- 本地资源上传至GitHub
- 项目更新

## 1 从GitHub上下载资源
### 0） 将资源下载至本地
- 下载zip压缩包（Windows下建议使用）
![Image text](https://github.com/dazhuang17/doc_img/blob/main/github_user_guide/1.jpg)

- 利用命令行下载资源（Linux下建议使用）
在命令行中输入`git clone ziyuan_address`，ziyuan_address参考以下
![Image text](https://github.com/dazhuang17/doc_img/blob/main/github_user_guide/2.jpg)

### 1） 将资源fork自己的项目中
![Image text](https://github.com/dazhuang17/doc_img/blob/main/github_user_guide/3.jpg)

## 2 本地资源上传至GitHub
### 0） 在GitHub上创建相关项目


### 1) 安装git及配置

### 2) 上传资源

## 3 项目更新


## 4 常见错误
### 0） 连接超时
遇到`Failed to connect to github.com port 443 after 21102 ms: Timed out`时，  
建议取消代理
```
git config --global --unset http.proxy   
git config --global --unset https.proxy
```

### 1） OpenSSL连接失败
遇到`OpenSSL SSL_read: Connection was reset, errno 10054`时，  
建议取消验证
```
git config --global http.sslVerify "false"
```

### 2） 云端资源改变对本地更新的影响
在云端资源改变的前提下，作者更新本地资源，然后上传更新，更新失败。  
一般来讲，解决办法是重新将云端资源pull到本地，然后再更新本地资源，然后上传更新。  
由于你之前上传失败，你pull资源的时候会出现：  
`error: cannot pull with rebase: Your index contains uncommitted changes.`  

处理方法  
```
git stash  
git pull --rebase
```  
问题解决，后续正常操作。



