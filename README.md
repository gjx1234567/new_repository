# GitHub
## 关键字查询：
xx(pathon) awesome:查询该标签下的xx(pathon)项目
xx(python) tutorial:查询xx(python)资料、书籍、文档
xx(socket) sample:查询对应技术(socket)的代码样本
## GitHub三要素：
### Respository仓库：
仓库是github项目管理存储基本能单位
一个仓库中存储一个项目，一个用户可以拥有多个仓库，一般仓库分为public,private
### Commit 提交：
程序员在整个开发周期，有大量的对代码资源的迭代和修改，都可以通过commit的方式进行记录，便于程序员回溯代码，即使这些代码被删除
提交便于使用者观察整个工程的开发流程以及设计程
### Branch 分支：
在仓库中可以包含多个分支，分支才是代码文件的第一存储单位，默认的仓库主分支为
master/main,可以管理代码存储，便于多人协作开发
![image](https://github.com/gjx1234567/new_repository/blob/master/img/Branch.png)
## 仓库内容
Code,资源存储，代码资源，二进制，项目管理脚本，许可证等等

issues,使用时遇到的bug或进行提交，等待反馈

README,使用markdown语言编写，工程自述文件，开发进度，版本更新，使用介绍等等

LICENSE许可证：GPL2.0，3.0，APahce2.0,Mit,这些准可证，给使用者最大使用权限

## Git软件，分布式版本控制系统
仓库管理软件，使用git管理私人代码或企业代码<br>
![image](https://github.com/gjx1234567/new_repository/blob/master/img/2.png)

## 设备认证
### 1、让网站的账户与设备绑定，后续完成代码的管理，上传下载
```markdown
	git init    //创建本地仓库，后续对仓库的操作，都要在仓库位置(master)
```
```markdown
	git config -list    //查看git的配置文件
```
#### 修改或添加config配置项
```markdown
	git config --global user.name	//用户名
	git config --global user.email	//注册邮箱
```
#### 生成本机设备密文
```markdown
	ssh-keygen -t rsa -C "注册邮箱"  //创建本地密文   去对应的目录下查找密文文件
```
![image](https://github.com/gjx1234567/new_repository/blob/master/img/4.png)



Markdown,文本修饰语言，用特殊符号修饰正文效果<br>
## 标题修饰符\#
# 标题修饰符（一级标题）
## （二级标题）
### （三级标题）
#### （四级标题）
##### （五级标题）

##正文内容
输入正文内容，但是如果需要换行，用\<br\>标签

##修饰正文
*一段测试文本*<br>
**一段测试文本**<br>
***一段测试文本***<br>
~~一段测试文本~~<br>
这是一段测试文本，将`关键字`重点显示

##分割线
  用\-\-\-表示分割线
---

##引用效果\>表示
>你自己就是一座金矿
>>苏格拉底
>>>三级引用
>>>>四级引用

##列表修饰符
###无序列表\*
* 一级
  * 二级
    * 三级
* 一级
  * 二级
  * 二级

###有序列表1.
1. 物理学
   1. 粒子物理
   2. 原子核物理
   3. 凝聚态物理
2. 计算机科学
   1. 分布式架构
   2. 云计算科学

###混合列表
1. 测试一级
   * 测试二级
    3. 测试三级

###表格
名称|技能|排行
-- |:--:|--:|
蝙蝠侠|有钱|32
海王|游泳|16
闪电侠|跑|010

###代码片段

```c
	#include<stdio.h>
```
```cpp
	#include<iostream>
```
```pathon
	import<os>
```
```bash
	echo "测试"
	pwd
	ps aux
```
