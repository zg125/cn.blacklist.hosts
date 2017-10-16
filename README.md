# cn.blacklist.hosts
主要是一些天朝流氓网站的子域名，方便写入hosts屏蔽


## 使用方法

### Linux
使用root用户，将项目中的hosts文件添加（请勿覆盖）到当前/etc/hosts文件末尾
<pre><code> wget https://github.com/4lan5/cn.blacklist.hosts/blob/master/hosts </code></pre>
<pre><code> cat hosts >> /etc/hosts </code></pre>

### Windows
用你喜欢的编辑器（如记事本）打开hosts文件（C:\Windows\System32\drivers\etc\hosts），将 https://github.com/4lan5/cn.blacklist.hosts/blob/master/hosts 中的内容复制到文件末尾，保存即可

PS：注意权限，参考[win10怎么修改hosts](http://www.pc841.com/Win10/201511-57111.html　"win10怎么修改hosts")

PPS：某些安全软件或者流氓软件（360，百毒，金山，疼逊等）可能会阻止你修改hosts文件，请选择放行或卸载流氓软件，再修改hosts屏蔽



## 流氓名单

* 百毒 [参考项目](https://github.com/zoln/baidu-hosts "参考项目")
* 360
* 瑞星
* 金山毒霸
* 疼逊电脑管家
* VeryCD
* 流氓雷
