OpenStack Magnum 源码分析
============
> 原文：[OpenStack Magnum 源码分析](https://github.com/yeasy/openstack_code_Magnum)

> 作者：[yeasy](https://github.com/yeasy)

> 版本：V0.3: 2015-06-11

[Magnum](https://wiki.openstack.org/wiki/Magnum) 是 OpenStack 项目中负责提供容器即服务（Container as a Service）的组件，它基于 Swarm、Kubernetes 等平台，实现对容器资源的管理。

本书将剖析 Magnum 组件的代码。

最新版本在线阅读：[GitBook](https://www.gitbook.io/book/yeasy/openstack_code_Magnum)。

本书源码在 Github 上维护，欢迎参与： [https://github.com/yeasy/openstack_code_Magnum](https://github.com/yeasy/openstack_code_Magnum)。

感谢所有的 [贡献者](https://github.com/yeasy/openstack_code_Magnum/graphs/contributors)。

## 更新历史:
* V0.3: 2015-06-11
    * 完成 conductor 部分，基本内容完成。
* V0.2: 2015-06-09
    * 完成 API 部分分析。
	* 完成 doc、etc、tools 等部分的分析。
* V0.1: 2015-06-08
	* 完成基本结构。


## 参加步骤
* 在 GitHub 上 `fork` 到自己的仓库，如 `user/openstack_code_Magnum`，然后 `clone` 到本地，并设置用户信息。
```
$ git clone git@github.com:user/openstack_code_Magnum.git
$ cd openstack_code_Magnum
$ git config user.name "User"
$ git config user.email user@email.com
```

* 修改代码后提交，并推送到自己的仓库。
```
$ #do some change on the content
$ git commit -am "Fix issue #1: change helo to hello"
$ git push
```

* 在 GitHub 网站上提交 pull request。
* 定期使用项目仓库内容更新自己仓库内容。
```
$ git remote add upstream https://github.com/yeasy/openstack_code_Magnum
$ git fetch upstream
$ git checkout master
$ git rebase upstream/master
$ git push -f origin master
```
