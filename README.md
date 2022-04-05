# guodong-summary

### 项目简介

此项目为《果冻的技术总结》的源码仓。文档使用 sphinx & rst 编写。

- [《果冻的技术总结》主页](https://guodong-summary.readthedocs.io/en/latest/)

- PDF、Epub等[文档下载](https://readthedocs.org/projects/guodong-summary/downloads/)


### 从源码构建

#### mac os

1、安装依赖

```bash
$ pip install sphinx
$ pip install sphinx-rtd-theme
```

2、构建网页

```bash
$ make html
```

#### ubuntu 20.04

1、安装sphinx
```shell
$ sudo apt-get install python3-sphinx
```

2、安装read-the-doc主题
```shell
$ pip install sphinx_rtd_theme
```

3、构建网页
```shell
$ make html
```

