# remove-baiduip-

来自破娃酱的博客 自己留作备份

复制下面内容到host 

1.0.0.1 api.map.baidu.com

1.0.0.1 ps.map.baidu.com

1.0.0.1 sv.map.baidu.com

1.0.0.1 offnavi.map.baidu.com

1.0.0.1 newvector.map.baidu.com

1.0.0.1 ulog.imap.baidu.com

1.0.0.1 newloc.map.n.shifen.com

::2 api.map.baidu.com

::2 ps.map.baidu.com

::2 sv.map.baidu.com

::2 offnavi.map.baidu.com

::2 newvector.map.baidu.com

::2 ulog.imap.baidu.com

::2 newloc.map.n.shifen.com


以上写法会让连接超时等待，如果你希望连接立即拒绝断开，那么把"1.0.0.1"改为"0.0.0.0"，把"::2"改为"::"即可

如果你使用代理，那么在代理服务器及本地都最好设置一下
原链接 ——https://breakwa11.blogspot.com/2016/12/baidu.html
