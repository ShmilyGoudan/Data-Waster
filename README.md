
本文为流量消耗器的使用说明

前言：
这个东西最初产生的原因其实是因为
刚转换了芝麻卡套餐定向流量多大没地儿用,便搭建了这个个玩意儿自用
之前在网上看的的都是一些本地版的，还要消耗服务器的流量，占用服务器的带宽
便扒拉了别人的改了改，页面也增加了一些当时很火的显示元素，如显示IP归属信息等

后面陆续改了很多，增加了一堆测速节点，发现每次切换来切换去都很麻烦，便产生了更换的念头，正好看到@net909的新版工具网，界面更优雅美观，就扒拉了下来，简单了修改了下，已适应多节点切换需要，之后发布到酷安后，爆火，单日IP流量突然800+，还一度以为被打了。。

近来也发现好些个小伙伴们扒拉本站源代码，
为了方便各位动手能力强的大佬们自行部署等个性化需求,
手工扒拉这个站点也费劲儿，暂时托管到了GitHub,方便各位大佬打包下载.

部署说明：
如果部署旧版流量消耗器,即可参考当前路径下的 old-index.php 文件，自己指定节点的话，需要修改两处
1，指定文件直链链接
2，修改上面指定文件文件大小
(因为每成功循环一次会加上这个大小，不指定正确，会导致测速流量统计不准，
另外因为统计周期是一个文件下载完，所以，即使你设定消耗10MB流量，那如果你指定的下载文件大小为5MB，线程为3，那实际本轮将会消耗15MB流量)

Gcod
2022 年 07月 19日
当然，如果谁要请我喝罐可乐，我也不会拒绝
![pyjy][1]

  [1]: https://wx1.vv1234.cn/2022/07/19/62d6cae36db89.jpg
