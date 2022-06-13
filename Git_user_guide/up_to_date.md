# up_to_date

## 4 项目更新

### 0） 直接覆盖上次内容  
<details>
<summary>详情</summary>
 
  将修改后的本地项目，右击进入git命令行
  ```
  git add .
  git commit -m "注释语句"
  git push 
  ```
  至此，结束项目更新
</details>

### 1） 建立新分支，与之前版本并行
<details>
<summary>详情</summary>
 
  将修改后的本地项目，右击进入git命令行
  ```
  git branch -a  # 我就看看
  git branch -M name # name为分支名
  git add .
  git commit -m "注释语句"
  git push -u origin name  # 第一次提交新分支需说明新分支，之后git push即可
  ```

</details>

