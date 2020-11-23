# class-dump

### 官网
http://stevenygard.com/projects/class-dump/
### 使用
``class-dump -H 解压完成的APP的Mach-O文件路径 -o 指定生成文件路径``

class-dump，顾名思义，就是用来dump目标对象的class信息的工具。它利用Objective-C语言的runtime特性，将存储在Mach-O文件中的头文件信息提取出来，并生成对应的.h文件。
需要是已砸壳的二进制文件。
