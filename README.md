# picture_difference

计算图片的差异

entry.java 是入口，目前直接指向dHash（差异hash算法），将代码拉下来后，修改entry.py里面的img1，img2两个变量，随意指向本机的图片，执行代码可以得到图片差异，返回值[0, 1.0]。 0表示不相同，1表示相同。

用户在拉取代码后，可以将pHash粘贴到自己的项目中，引用后仿照entry.py示例来使用
