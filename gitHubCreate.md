<!--
 * @Author: your name
 * @Date: 2020-11-25 14:16:37
 * @LastEditTime: 2020-11-25 14:24:37
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \note-files\gitHubUpload.md
-->
```
echo "# noteFiles" >> README.md // 新建文件 echo 文件内容 >> 文件名
git init // 初始化git
git add README.md // 将创建的文件添加到暂存区
git commit -m "first commit" // 提交到版本库
git branch -M main // 修改分支名称
git remote add origin // https://github.com/cuicong1994/noteFiles.git // 连接远程仓库
git push -u origin main // 推送到远程
```