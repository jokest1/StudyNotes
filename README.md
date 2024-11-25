# 仓库描述
个人学习进度记录的仓库,只存储相关的代码和笔记相关的插图
# 进度记录
- 2024年11月25日
  - 
# 文件目录结构

# 相关学习内容笔记
## Git介绍
### Git介绍
Git是一个分布式版本控制系统使用仓库数据库跟踪每个文件的修改和变动记录,通过Git可以对文件进行更新恢复回退等功能,是一个高效的多用户合作管理项目工具

Git的使用方式:
- 命令行
- IDE插件
- 图形化界面

### Git初始化配置
git为了区分Linux相关的命令所有的命令都以git开头,使用git要先配置用户名和邮箱来区分提交的人是谁,使用一下几个命令来进行配置
```git
//配置用户名
git config --global user.name "test my"
//配置邮箱
git config --gloabl user.email "123456@qq.com"
//自动输入密码
git config --global credential.helper store
//显示该仓库的配置信息
git config --global --list
```
其中关于`--gloabl`是为了区分配置信息的作用范围:
- local 只作用于当前仓库
- global 作用于所有仓库
- system 作用于所有用户


