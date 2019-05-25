# Inside The C++ Programming Language

> 源码之前,了无秘密

## Preface

我在打下这些字的时候已经是2019年, C++20已经要来了, 然而大部分的学校仍然在教授C++03的东西.因此想要深入了解C++这门语言, 必须要阅读大量的经典书籍、博客、文档. C++的书籍都是大部头, 硬啃通常非常吃力, 有时候配合一些绝佳的博客食用效果会更佳, 然而这种博客真的少之又少, 或者网络原因无法访问, 国内经典的CSDN已经被垃圾文章灌满, 有些甚至充满错误. 这个项目创建的目的就是总结归纳C++的知识点, 一来巩固自身水平, 二来为后来者提供一个良好资源.

## Todo

在已经了解了 C++11/14 的大体知识后, 按模块来详细的归纳相关知识, 思路是先梳理出一颗结构树, 然后对整棵树做深搜写文.

目前该项目会整合以下图书内容以及在线资源:

+ [《C++ Primer 5th》](http://product.dangdang.com/23321562.html?&unionid=P-113189815m)
+ [《Effective C++》](http://product.dangdang.com/21000966.html?&unionid=P-113189815m)
+ [《Inside The C++ Object Model》](http://product.dangdang.com/22588609.html?&unionid=P-113189815m )
+ [《Effective Modern C++》](http://product.dangdang.com/25273601.html?&unionid=P-113189815m)
+ [《Effective STL》](http://product.dangdang.com/27647910.html?&unionid=P-113189815m)
+ [《STL 源码剖析》](http://product.dangdang.com/23807467.html?&unionid=P-113189815m)
+ [《Thinking in C++》](http://product.m.dangdang.com/22453473.html?&unionid=P-113189815m)
+ [C++ Reference](https://en.cppreference.com/w/)
+ [知乎](https://www.zhihu.com)

未来会加入的资源:

+ 《C++ Template》
+ 《Modern C++ Design》
+ [AwesomeCpp](https://github.com/fffaraz/awesome-cpp)
+ [AwesomeModernCpp](https://github.com/rigtorp/awesome-modern-cpp)




## Contribute

+ fork [该项目](https://github.com/maochongxin/InsideTheCpp.git).
+ 选择相关条目,深入阅读,查阅标准库研究best practice后写出文章或翻译优秀C++文章. 提交格式要求为Markdown.
+ 按格式修改README.
+ Pull Request.



## Directory

```
Tree			// 随时优化改动
|
|——C++基础
|——标准库
|	|——IO库
|	|——STL
|	|	|———算法
|	|	|———容器
|	|	|———迭代器
|	|	|———空间配置器
|	|	|———配接器
|	|	|———仿函数
|	|——智能指针
|——拷贝控制
|	|——————销毁
|	|——————资源管理
|	|——————交换
|	|——————RAII
|	|——————移动语意
|——重载
|——类型转换
|——面向对象
|	|————对象模型
|	|————虚函数
|	|————构造/析构函数
|	|————静态成员
|	|————多重继承
|	|————虚继承
|——模版
|	|———模版实参推导
|	|———重载与模版
|	|———可变参数模版
|	|———模版偏特化
|——	模版元编程
|——异常
|——命名空间
|——特殊工具和技术
|	|————运行时类型识别
|	|————嵌套类,局部类
|	|————运行时类型识别
|	|————固有的不可移植的特性
|		  |————位域
|		  |————volatile
|		  |————extern "C"
|		  |————类成员指针
|		  |————枚举类型
|		  |————union
|——编译模型
|
|

```

## 文章列表



###编译模型

[浅谈C/C++编译模型(未完)](./CppCompilerModel.md)