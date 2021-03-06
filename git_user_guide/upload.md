# Upload

## 2 本地资源上传至GitHub
- 在GitHub上创建相关项目
  <details>
  <summary>详情</summary>   
    
    创建仓库  
    `个人主页 -> repositories -> New`  
    ![Image text](./images/4.jpg)  
      
    然后输入项目名称、信息配置即可  
    ![Image text](./images/5.jpg)  
      
    点击`Create repository`即创建成功！
  </details>

- 安装Git及配置
  <details>
  <summary>详情</summary>
  
  Git官网地址：http://git-scm.com/download/  
  选择对应系统，安装一路默认就行（可以改安装路径）  
  **本文安装环境为Windows**  

  **第一次使用Git**
  - 本地生成SSH密钥  
    右键打开git命令行工具，输入以下命令
    ```
    git config --global user.name "github_name"
    git config --global user.email "github_email"
    ssh-keygen -t rsa -C "github_email"
    ```
    
    密钥默认位置在`C:\Users\（你的用户名)\.ssh\id_rsa.pub`中，复制其中内容即可  
  - GitHub 账号配置SSH公钥  
  `个人主页 -> 右上角头像点击 -> Settings -> 左侧菜单栏SSH and GPG keys -> New SSH key`   
  然后新出来的页面中的key输入框中输入前面复制的`id_rsa.pub`文件的内容  
  至此，结束配置流程
  </details>
  
- 上传资源
  <details>
  <summary>详情</summary>   
  
  **方案很多，博主仅使用其中一种**
  - 将上述GitHub上创建好的项目clone到本地，在clone到的项目中添加所需上传的资源，**clone到的项目中需含有`.git`文件夹** **（也可将`.git`文件夹复制到所需上传的资源中）**
  - 之后，在项目中右击打开git命令行
  - 输入
  ```
  git add .
  git commit -m "注释语句"
  git push
  ```  
  至此，结束上传资源流程
</details>

## 附件链接
- [从GitHub上下载资源](./download.md)
- [本地资源上传至GitHub](./upload.md)
- [项目更新](./up_to_date.md)
- [Git使用常见问题](./Q%26A.md)
