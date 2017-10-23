# Go -selpg



---

使用Go实现Linux命令行程序selpg
## 功能简介
在输入（stdin或文件）的内容中，根据指定-s [Number] -e [Number]参数，选择指定页码范围内的内容输出，同时可以通过-d [destPrinter]将输出内容直接传送到目标打印机进行打印。
## 程序运行
---
### 编译
![test1][1]

### 测试部分

 1. 输出第一页前15行
![test2][2]
 2. 输入第一页内容
 ![test3][3]
 3. 从标准输入中读入，输出第一页，每页3行，输出到标准输出
 ![test4][4]


  [1]: https://github.com/kingchiuoy/Go/blob/master/Images/img1.png
  [2]: https://github.com/kingchiuoy/Go/blob/master/Images/img2.png
  [3]: https://github.com/kingchiuoy/Go/blob/master/Images/img3.png
  [4]: https://github.com/kingchiuoy/Go/blob/master/Images/img4.png