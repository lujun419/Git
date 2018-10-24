1.git init   // 初始化版本库
2.git add .   // 添加文件到版本库（只是添加到缓存区），.代表添加文件夹下所有文件
3.git commit -m "first commit" // 把添加的文件提交到版本库，并填写提交备注
我们完成了代码库的初始化，但代码是在本地，还没有提交到远程服务器

4.git remote add origin 你的远程库地址  // 把本地库与远程库关联
5.git push -u origin master    // 第一次推送时 
6.git push origin master  // 第一次推送后，直接使用该命令即可推送修改
7.test
