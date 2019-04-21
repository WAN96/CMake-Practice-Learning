# CMake-Practice-Learning
CMake Practice book learning. 
学习CMake Practice这本书，创建了一些书中的例子，逐步更新
CMake 是构建项目必不可少的编译语言体系，学习CMake有助于我们更好的构建程序项目，同时ros下的CMake构建也更容易，有助于我们的程序编译过程更加清晰。
本部分提供了CMake Practice书的pdf版本，由于作者在书中未标明，因此不知道具体的作者是谁，无法联系，但本书为开源项目，因此我把书放在这里。

---

## 说明
本项目提供的程序均来自CMake Practice书

    test1 对应第三节
    test2 对应第四节
    test3 对应第五节

***

## 书中遇到的问题
### 第五节：
按照书中所讲：我们要设置

    SET_TARGET_PROPERTIES(hello PROPERTIES CLEAN_DIRECT_OUTPUT 1)

之后动态与静态库在重名的情况下才不会在构建时清理掉其中一个，但我试了两次在不加入这个语句的情况下也可以同时构建
