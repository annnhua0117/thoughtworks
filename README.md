# thoughtworks作业
## 如何运行我的源代码
### 我使用的运行方式是mac上的终端，具体步骤如下：
1. 使用cd命令行进入我的源代码RomanToNumber.java所在的目录
2. 然后使用javac命令行编译产生.class文件
3. 最后使用java命令行运行.class文件来测试代码
```命令行
cd /Users/anhua/Desktop
javac RomanToNumber.java
java RomanToNumber
```
## 测试我的代码
```java
CXXIII //显示123的液晶数字形式 
MMVXIII //显示2018的液晶数字形式
set size 2
CXXIII //显示2倍的123的液晶数字形式
MMVXIII //显示2倍的2018的液晶数字形式
set size 1
FOOBAR //显示E即错误 foobar不属于合法的罗马数字
```
我还额外加入了3，4，5...等size的字体大小以供测试，同上使用set size就可以了
