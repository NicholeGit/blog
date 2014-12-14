---
title: 关于
layout: page
comments: no
---

---
###自我介绍

{{ site.about }}

专业打杂程序员，全栈工程师，擅长打杂，吹牛逼...

看过以下但不仅限于以下列出的项目的源码：

> Linux kernel, MySQL/InnoDB, Docker, Kubernetes, Ceph, SQLite, Memcached, Haproxy...

使用过以下但不仅限于以下列出的语言：

> C/C++, Shell, Go, Python, PHP, Perl, C#, Java, Lua, Html...

格言

> 阅码无数，心中无码

----

###联系方式：

{% if site.qq %}
ＱＱ：[{{ site.qq }}](tencent://message/?uin={{ site.qq }})
{% endif %}
网站：[{{ site.name }}]({{ site.url }})

邮箱：[{{ site.email }}](mailto:{{ site.email }})

GitHub：[http://github.com/{{ site.github }}](http://github.com/{{ site.github }})

@cnblogs：[hustcat](http://hustcat.cnblogs.com)

----

[![新浪微博](http://service.t.sina.com.cn/widget/qmd/1831504255/02345c5a/1.png)](http://weibo.com/u/1831504255?s=6uyXnP)

---
###社区动态：

Docker：

* [set tx_queuelen to 0 when create veth device](https://github.com/docker/libcontainer/pull/193)
* [access private registry: x509: certificate signed by unknown authority](https://github.com/docker/docker/issues/8849)
* [poor NAT & networking performance](https://github.com/docker/docker/issues/7857)

CoreOS/etcd

* [Error: 501: All the given peers are not reachable](https://github.com/coreos/etcdctl/issues/109)


MySQL：

* [Bug #70270	mysqldump's bug with binary character set](http://bugs.mysql.com/bug.php?id=70270)

