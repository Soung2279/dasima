# Dasima
***
## 大司马发病评论

**默认文件夹名：dasima**
**默认服务名：发病评论**
**目录组成如下：**

> **dasima**
>> ilovedsm.py  #主要运行文件
>> README.md  #说明文件

### 功能介绍

~~人肉爬虫~~

随机发送大司马B站评论区的发病评论，嘿嘿，嘿嘿嘿，金轮我的金轮

无需依赖，安装即用。

### 安装

#### 通过github克隆

在hoshino/modules文件夹中，打开cmd或者powershell，输入以下代码按回车执行：
```powershell
git clone https://github.com/Soung2279/dasima.git
```

之后关闭cmd或powershell，在hoshino/config的`__bot__.py`文件中，在MODULES_ON = {}里添加dasima
```python
# 启用的模块
MODULES_ON = {
    'xxx',
    'xxx',
    'dasima',  #注意英文逗号！
    'xxx',
    'xxx',
}
```

#### 直接安装

直接下载本文件夹（dasima），将其放入hoshino/modules中

并在hoshino/config的`__bot__.py`文件中，在MODULES_ON = {}里添加dasima
```python
# 启用的模块
MODULES_ON = {
    'xxx',
    'xxx',
    'advance_check',  #注意英文逗号！
    'xxx',
    'xxx',
}
```

### 指令

- **`[发病]`** 随机一条评论
- **`[@bot 注入金轮]`** 每天到达上限次数后重置上限

### 可自定义内容

没啥好改的=  =

>~~其实本身写的也挺犯病的~~

### 其它

本人非专业程序员，业余写着玩玩，代码很菜，大佬们看看就好QwQ。

~~能跑就行.JPG~~

made by [Soung2279@Github](https://github.com/Soung2279/)

### 鸣谢

[HoshinoBot](https://github.com/Ice-Cirno/HoshinoBot)
