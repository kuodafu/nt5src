# 写在前面的话
> 如果这里有什么缺漏或者写错的, 欢迎补充  
> 做这个的目的就是为了学习  
> 需要学习微软的一些功能是怎么实现的  
> 或者想看某个函数内部是怎么实现的  
> 这样就需要找到这个函数的定义  
> 如果不知道文件结构的话, 找起来会麻烦很多  
> 比如我知道ntdll的源码在 base/ntdll 这个目录下  
> 那我只需要对这个目录下的文件进行搜索  
> 大大加快了搜索的效率, 并且搜索结果少, 能更方便的定位到函数的位置  
> 一个人的精力肯定有限, 如果有很多人参与进来, 一人提供一个经验点  
> 那学习起来岂不是事半功倍了吗

这里只记录一些经验, 不提供源码下载, 如果需要下载源码  
可以在搜索引擎搜索 `Microsoft leaked source code archive_2020-09-24`  
或者搜索 `nt5src`  
搜索这两个关键字一般都能找到下载链接  
其中 `misc\windows_xp_source.rar` 这个压缩包的解压密码是: internaldev  

----

# 文件结构

主文件夹名 `Microsoft leaked source code archive_2020-09-24`  

`nt5src\Source\Win2K3`  windows2003源码路径  
`nt5src\Source\XPSP1`  	windowsXPSP1源码路径  


这里大部分以xp为主, 所有路径都是基于 `nt5src\Source\XPSP1\NT\` 这个目录下  



`base/ntdll` 	这个目录应该是ntdll的源码  
`base/ntos`		这个目录应该是ntoskrnl.exe的源码  
`base/win32`	这个目录应该是kernel32的源码  

`windows\advcore\gdiplus` 这里是gdi+的源码
