# AndroidSourceReader

Android-Studio 阅读AOSP源码所必须的几个文件，免去复杂的编译过程

1. 这些文件如何产生？
参见：https://www.jianshu.com/p/8557170d34a9

2. 版本不能严格匹配怎么办？
准确来说，版本不匹配，只能自己重新去编译，但基于同一个大版本下，文件调整（比如新建类、接口修改等）不是很大，所以使用同一个大版本的文件并没有什么问题。

3. 如何使用？
将对应版本下的文件复制到本地的AOSP根目录下，使用Android-Studio打开android.ipr，等待索引完成，即可阅读源码。

