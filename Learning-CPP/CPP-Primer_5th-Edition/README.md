## C++ Primer 中文第5版 
- Cpp_Primer_Answers-master 文件夹: 为中文第5版的习题答案


## 生词
- **paradigm ['pærədaɪm] --n.示范，范例**
    + --> There's no paradigm to follow in this new industry.
        在这个崭新的行业里没有范例可做参考。
- **generic [dʒi'nerik] --adj.普通的，一般的**
     + --> generic identity 通用特性
     + --> generic term. 通用数据
     + --> The generic term for wine, spirits and beer is alcoholic beverages.


## 术语表
- 面向对象(object-oriented)
- 基于对象(object-based)
- 程序设计方法 (programming paradigm)
- 泛型算法 (generic algorithm) 


## 笔记
- 我们编写的程序主要是由 2 个主要方面组成:
    - (1)**算法**的集合 (就是将指令组织成程序来解决某个特定的问题)
    - (2)**数据**的集合 (算法在这些数据上操作，以提供问题的解决方案)
    + 纵观短暂的计算机发展史，这 2 个主要方面 (算法和数据) 一直保持不变。发展演化的是他们
      之间的关系，这就是所谓的 "程序设计方法 (programming paradigm)"

- C++ 语言可以看作是 3 部分组成的:
    1. 低级语言，大部分继承自 C 语言。
    1. 现代高级语言特性，允许我们定义自己的类型以及组织大规模程序和系统。
    1. 标准库，它利用高级特性来提供有用的数据结构和算法。

- C++ 融合了 5 种编程范型(paradigm)
    + 面向过程
    + 基于对象
    + 面向对象
    + 泛型
    + 函数式

------
- C++ 在 C 的面向过程编程的基础上增加了面向对象的编程 (OOP) 和泛型编程。其中泛型编程主要
  指的是利用模板特性进行的编程。
- 上面说了我们编写的程序主要由 "算法" 和 "数据" 2个主要方面组成，而 OOP 强调的是数据，C++
  中的类是一种就是一种规范，用来描述对象的数据格式，对象就是在类的规范下构建的数据结构。其中
  重要的概念有: 重用代码、访问控制、多态、继承等。
- 泛型编程：泛型编程是独立于任何特定类型的编码方式; C++ 的数据类型有多种类型 —— 整数、浮点
  型、字符、字符串、用户定义的...由多种类型组成的符合结构。  例如，要多不同类型的数据进行
  排序，通常必须要为每种类型创建一个排序函数。而泛型编程就是针对这一问题，对语言进行扩展，只
  编写一个泛型函数就可以完成对不同类型的数据的处理。C++ 模板提供了完成这种任务的机制。
- C++ 代码的执行过程主要就是 2 个部分: 编译和链接。编译就是将源代码编译为汇编代码然后生成
  目标代码（机器语言）。链接就是将目标函数同使用的其他目标代码和库代码组合起来，生成可执行
  程序。
------

- 类是面向对象编程和泛型编程的基础。    

> C++ 支持的特性保包含但不限于: 
- 模板(template)
- 支持 面向对象(object-oriented) 和 基于对象(object-based) 程序设计所需要的 
  类(class) 机制。
- 嵌套类型 
- 函数重载
- STL (标准模板库)
- 关联容器类型: vector, list, map 和 set
- 可扩展的泛型算法 (generic algorithm)   
