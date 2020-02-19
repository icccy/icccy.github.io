使用github desktop管理步兵代码

1、登录github，在github建立一个新资料库

![1582102901883](C:\Users\79155\AppData\Roaming\Typora\typora-user-images\1582102901883.png)

只输入库名字就行了，注意我们的代码应该把库设成私有的（private）

2、下载并安装并登录github desktop

（我的是以前就下好的所以这部分操作忘记了，百度一下不难的）

3、然后点开自己的github

![1582103281551](C:\Users\79155\AppData\Roaming\Typora\typora-user-images\1582103281551.png)

点到自己的资源库，选择open in desktop

4、然后就到这个界面

![1582103338662](C:\Users\79155\AppData\Roaming\Typora\typora-user-images\1582103338662.png)

这时候看github desktop的资源文件夹中已经有了一个名字相同的文件code for stm32，这时这个文件夹就已经和github连上了

![1582103406806](C:\Users\79155\AppData\Roaming\Typora\typora-user-images\1582103406806.png)

5、点开code for stm32，把自己的代码工程整个复制进去

![1582103668659](C:\Users\79155\AppData\Roaming\Typora\typora-user-images\1582103668659.png)

6、点github desktop，发现有待commit的，点commit

![1582103686460](C:\Users\79155\AppData\Roaming\Typora\typora-user-images\1582103686460.png)

7、这时候文件只是存在了本地库，点push推到网上

![1582103755101](C:\Users\79155\AppData\Roaming\Typora\typora-user-images\1582103755101.png)

7.5、第一次上传工程的时候可能会commit很多个文件，然后只能一个一个commit，不能一起commit。

![1582103880886](C:\Users\79155\AppData\Roaming\Typora\typora-user-images\1582103880886.png)

解决办法是先commit一个，然后撤销

![1582103923070](C:\Users\79155\AppData\Roaming\Typora\typora-user-images\1582103923070.png)

然后在全选

![1582103941675](C:\Users\79155\AppData\Roaming\Typora\typora-user-images\1582103941675.png)

就可以了。等push结束在github端也能看到自己的工程了

8、这样一套流程下来一次下载、修改、上传的组合拳就打完了，但是现在我们的资源库是私有的，组员没法看到。点回资源库，点setting

![1582104092786](C:\Users\79155\AppData\Roaming\Typora\typora-user-images\1582104092786.png)

点绿色的邀请共同开发者，输入自己组员的id，应该能让组员看到自己的私有工程了