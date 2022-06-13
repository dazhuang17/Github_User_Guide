# Upload

## 2 本地资源上传至GitHub
### 0）在GitHub上创建相关项目
<details>
<summary>详情</summary>   
  
  创建仓库  
  `个人主页 -> repositories -> New`  
  ![Image text](https://github.com/dazhuang17/doc_img/blob/main/github_user_guide/4.jpg)  
    
  然后输入项目名称、信息配置即可  
  ![Image text](https://github.com/dazhuang17/doc_img/blob/main/github_user_guide/5.jpg)  
    
  点击`Create repository`即创建成功！
</details>

### 1）安装Git及配置
<details>
<summary>详情</summary>   
  
  Git官网地址：http://git-scm.com/download/  
  选择对应系统，安装一路默认就行（可以改安装路径）  
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
  
### 2）上传资源
<details>
<summary>详情</summary>   
  
  **方案很多，博主仅使用其中一种**
  - 将上述GitHub上创建好的项目pull到本地，在pull到的项目中添加所需上传的资源，即&ensp;pull到的项目记作A，所需上传的资源为B，将B中的文件均复制到A中，即可  
</details>

## 附件链接
- [从GitHub上下载资源](https://github.com/dazhuang17/Github_User_Guide/blob/main/Git_user_guide/download.md)
- [本地资源上传至GitHub](https://github.com/dazhuang17/Github_User_Guide/blob/main/Git_user_guide/upload.md)
- [项目更新](https://github.com/dazhuang17/Github_User_Guide/blob/main/Git_user_guide/up_to_date.md)
- [Git使用常见问题](https://github.com/dazhuang17/Github_User_Guide/blob/main/Git_user_guide/Q%26A.md)
