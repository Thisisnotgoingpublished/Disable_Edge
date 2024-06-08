# Disable Edge
How to make some famous browser unable to take up your system usage. 

Could not uninstall Microsoft Edge for just now, even with old command line methods, but you can disable it at least, by following these:

1)Stop all processes that is from edge.

2)Navigate into %localappdata%\Microsoft\Edge from explorer.

3)Right click the Edge folder, select Properties -> Security -> Advance -> Disable Parenting -> Select the first option in the popup. -> OK -> Edit -> Delete all users -> Add -> input Everyone then check for the name -> Refuse all the permissions in the bottom box-> OK -> OK

Now it should be unable to start the Edge. Saves your precious system resources.

I did not find any abnormal in the system just yet.

====

无法卸载Edge，卡安装包bug的那招被封了,但是还算是可以禁用的，按照下面的操作就可以啦：

1)给我停止运行所有Edge相关的程序。

2)从地址栏打开 %localappdata%\Microsoft\Edge

3)右键点击Edge文件夹，选择属性->安全->高级选项->停止继承->弹出个窗口你选择第一个选项->确定->编辑->删掉所有用户->添加->输入Everyone然后单击检查名称->在下面拒绝所有权限->确定->确定

现在Edge就回天无力了，系统资源会减少一大半？（然而其实卵用都没有，不如还是研究研究services去吧）

停用了以后暂时还没发现系统出现啥不正常的地方。

====

According to the(引用资料):

Why you can't uninstall it? 凭啥不能卸载啊？

https://support.microsoft.com/en-us/microsoft-edge/why-can-t-i-uninstall-microsoft-edge-ee150b3b-7d7a-9984-6d83-eb36683d526d

Edge user date location...? 数据都他妈的存哪了？

https://answers.microsoft.com/en-us/microsoftedge/forum/all/how-to-reset-microsoft-edge-completely-from-a/e73ab2e8-8222-4da4-ab81-67c129dd13b7
