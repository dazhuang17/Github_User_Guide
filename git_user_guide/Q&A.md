# Q&A

## 4 常见问题
- 连接超时
    <details>
    <summary>详情</summary>
      
    遇到`Failed to connect to github.com port 443 after 21102 ms: Timed out`时，  
    建议取消代理
    ```
    git config --global --unset http.proxy   
    git config --global --unset https.proxy
    ```
    </details>

- OpenSSL连接失败
    <details>
    <summary>详情</summary>
      
    遇到`OpenSSL SSL_read: Connection was reset, errno 10054`时，  
    建议取消验证
    `git config --global http.sslVerify "false"`
    </details>

- 云端资源改变对本地更新的影响
    <details>
    <summary>详情</summary>
      
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
    </details>

## 附件链接
- [从GitHub上下载资源](./download.md)
- [本地资源上传至GitHub](./upload.md)
- [项目更新](./up_to_date.md)
- [Git使用常见问题](./Q%26A.md)
