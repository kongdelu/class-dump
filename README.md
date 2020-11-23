# class-dump

将Objective-C编写的二进制文件反编出头文件，需要是已砸壳的二进制文件。
class-dump，顾名思义，就是用来dump目标对象的class信息的工具。它利用Objective-C语言的runtime特性，将存储在Mach-O文件中的头文件信息提取出来，并生成对应的.h文件。
