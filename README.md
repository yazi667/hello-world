# hello-world
This is my first Git repository file!

OK,I now create a new branch! -2016-11-18

WHY CAN NOT FIND DIFFERENT?

------------------------------------关于可能出现的错误----------------------------------

1.在执行

$ git remote addorigin git@github.com:defnngj/hello-world.git

错误提示：fatal: remote origin already exists.

解决办法：

$ git remote rm origin

然后在执行：$ git remote add origin git@github.com:defnngj/hello-world.git 就不会报错误了

 

2. 在执行

$ git push origin master

错误提示：error:failed to push som refs to.......

解决办法：

$ git pull origin master // 先把远程服务器github上面的文件拉下来，再push 上去。

