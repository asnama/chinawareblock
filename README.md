# chinawareblock
国产流氓、娱乐软件和不受欢迎的软件屏蔽工具
其实是个很菜的东西


# 制作背景
* 由于[舞恸零一](https://liwei2.com/)开发的[流氓软件终结者3.5](https://liwei2.com/2015/11/27/378.html)已经很久没有更新，现在的流氓基本挡不住了，这个把证书防御的部分拿出来续了一下。
* 组策略中证书规则 https://www.zhihu.com/question/26917038
* 我自己的工作内容之一是给政府部门维护电脑，所以工具本身除了防住一些特别讨厌招烦的国产流氓，还要防止不自觉的人员在上面使用一些人民群众和纪检监察不乐意看到的软件，就是什么视频网站app，游戏平台，直播平台，股票软件，之类的。


# 使用要求和限制

* 需要Vista以上系统，需要UAC开启
* 软件也要有点级别，那些连数字证书都没有的产品这个防不住
* 据说配置非常差的电脑不建议拉黑太多证书 

# 使用方法

* 最简单粗暴的方法，把工具随便解压在哪里，双击运行**除腾讯全拉黑.bat**，会拉黑子文件夹下所有证书相关的软件。腾讯文件夹下的不敢拉黑，不然这电脑没人用了，腾讯你牛逼。
* 也可以单独进一个个文件夹，点击**~一键拉黑.bat**，拉黑文件夹下所有证书。证书可以根据需要自行增减。
* 证书文件的命名方式是公司名-软件名-加密方式-到期日，所以如果到期日已经过了的证书，应该要留一下他们新的安装包，可能要补充新的拉黑了。

# 需要扩充的功能

* 本人不会写程序，这些证书基本都是一个个下载流氓，用右键手动导出证书然后改名的。例外是过期证书文件夹，是[舞恸零一](https://liwei2.com/)导出的。如果有朋友帮忙，开发一个工具可以导出文件夹下所有exe的数字签名，按照一定的格式命名，例如哈希值-公司-到期日，就方便很多了。
