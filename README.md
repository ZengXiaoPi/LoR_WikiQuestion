# LoR_WikiQuestion
一个能自助生成月亮计划中文维基编辑部问题的网页。
## 简介
网址： https://wiki.zxpweb.eu.org
## 添加题目
### 自行修改并提交PR
请进入<b>index.html</b>，找到下图的位置。
![image](https://user-images.githubusercontent.com/102937102/233114587-e2f6c6b3-bfc5-4cbc-86b3-8dcc140168bd.png)

按照格式添加题目即可。
例如：
```
var easyQuestions = ["第一个简单问题"， "第二个简单问题"]
```
添加第三个问题即为
```
var easyQuestions = ["第一个简单问题"， "第二个简单问题", "第三个简单问题"]
```

easyQuestions 为简单问题
mediumQuestions 为普通问题
hardQuestions 为困难问题
extremeQuestions 为极难问题

在修改完成后请提交PR（合并请求）
### 你不会？
找我就行。
