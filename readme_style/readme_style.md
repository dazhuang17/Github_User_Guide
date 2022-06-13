# readme_user_guide

## 0 写在前面
- 部分内容摘自[guodongxiaren](https://github.com/guodongxiaren/README)的项目
- 在本文中，博主仅写出自己使用过的`markdown`语法

## 1 收缩文本
<details>
<summary>详情</summary>  
  
- 使用如下代码
```
<details>
<summary>详情</summary>  
    
xxx
</details>
```  
</details>

## 2 文本
  
<details>
<summary>详情</summary>  
  
- 换行  
  直接回车不能换行  
  在上一行结尾打出两个空格  
  这就是示例  
- 高亮  
  使用键盘上`tab`上边的反引号  
  单行-单对反引号，多行-三对反引号  
  示例  
  `这是单行文本`  
  ```
  这是多行文本
  这是多行文本
  这是多行文本
  ```
 - 字体格式&表格  

  |语法|效果|
  |----|-----|
  |`*斜体1*`|*斜体1*|
  |`_斜体2_`| _斜体2_|
  |`**粗体1**`|**粗体1**|
  |`__粗体2__`|__粗体2__|
  |`这是一个 ~~删除线~~`|这是一个 ~~删除线~~|
  |`***斜粗体1***`|***斜粗体1***|
  |`___斜粗体2___`|___斜粗体2___|
  |`***~~斜粗体删除线1~~***`|***~~斜粗体删除线1~~***|
  |`~~***斜粗体删除线2***~~`|~~***斜粗体删除线2***~~|  
</details>

## 3 图片
<details>
<summary>详情</summary>  
    
  - __建议将所需图片上传至自己的github__  
  [这是个教程](https://github.com/dazhuang17/github_user_guide/tree/main/Git_user_guide)  
  
  基本格式：  
  `![alt](URL title)`  
  alt和title即对应HTML中的alt和title属性（都可省略）：
  ```
  - alt表示图片显示失败时的替换文本
  - title表示鼠标悬停在图片时的显示文本（注意这里要加引号）
  - __URL可以重定义__，例如：
  ```

  |#|语法|效果|
  |---|---|----
  |1|`![baidu](http://www.baidu.com/img/bdlogo.gif "百度logo")`|![baidu](http://www.baidu.com/img/bdlogo.gif "百度logo")
  |2|`![Image text](https://github.com/dazhuang17/doc_img/blob/main/github_user_guide/0.jpg)`|![Image text](https://github.com/dazhuang17/doc_img/blob/main/github_user_guide/0.jpg)
  |3|`![][GitHub]`|![][GitHub]

 
</details> 
  
  
## 4 超链接
<details>
<summary>详情</summary>  
    
- 文字链接  
[这是一个文字链接](https://github.com/dazhuang17)，指向dazhuang17的github。  
  示例  
  `[这是一个文字链接](https://github.com/dazhuang17)`  
  一般的，将[]作为ui显示载体，()内为链接地址。
- 图片链接

</details>

--------------------------------
[GitHub]:https://github.com/dazhuang17 "我的github"
[zhihu]:https://www.zhihu.com/people/guodongxiaren "我的知乎，欢迎关注"
[weibo]:http://weibo.com/linpiaochen
[baidu-logo]:http://www.baidu.com/img/bdlogo.gif "百度logo"
[weibo-logo]:/img/weibo.png "点击图片进入我的微博"
[csdn-logo]:/img/csdn.png "我的CSDN博客"
[code-past]:/img/codepast-logo.jpg "公众号：编程往事"
[zhihu-shield]:https://img.shields.io/badge/dynamic/json?color=0084ff&logo=zhihu&label=%E6%9E%9C%E5%86%BB%E8%99%BE%E4%BB%81&query=%24.data.totalSubs&url=https%3A%2F%2Fapi.spencerwoo.com%2Fsubstats%2F%3Fsource%3Dzhihu%26queryKey%3Dguodongxiaren


