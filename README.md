![](https://travis-ci.org/1c7/travis-ci-ruby.svg?branch=master)

# 介绍
这里这个库就是简单玩了下 Travis ci  https://travis-ci.org


<br/>
# 一句话总结
Travis CI 用了之后，你每次 github push 之后就会帮你自动做测试，然后告诉你结果。测试成功还是失败了。
具体 linux 的错误 log 是什么。
就是这样。

测试的环境和方法由你来定制，具体方法是在根目录下写个 .travis.yml 文件  
然后这个文件里的内容符合规定的语法  


<br/>
# 长一点点的总结
travis-ci 玩了一下还不错，和 github 结合的很紧密，  
总之就是在根目录下放个 .travis.yml 文件，里面写点东西说怎么测，  
然后每次 push 之后就会自动跑测试了，也不用多管。  


https://docs.travis-ci.com/user/for-beginners  
这篇是给 0 基础看的，
这篇教程叫你 fork 一个库，然后去 travis-ci 上用 github 登录，把 fork 库的开关打开，这样提交之后就会自动测试了。  
然后它叫你随便改个 txt 文件（里面没代码，就是个空 txt），保存提交，然后测试会失败，因为故意的。  
.travis.yml 里写的是，测试另一个写错了的 php 文件。  

然后教程教你怎么改对，保存提交。这次 ci 就提示正确了  


最上面那个图标实际上就是  
```
![](https://travis-ci.org/1c7/travis-ci-ruby.svg?branch=master)
```
