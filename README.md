# AlipayRedPacketHackNet
支付宝 AR 红包 破解教程，文章地址：https://www.huxiu.com/article/175838.html

本教程基于tensorflow

# 注:
禁止用此方法做违法乱纪的事情

这里只公布破解思路和训练网络的网络结构和方法，供技术研究学习用

网络定义见 net.ipynb


# -----技巧-----
训练完成后，进行图片生成时有下面三个要点：

  1，将图片横条部分置零
  
  2，输入置零像素文件，求 “1px * 图像宽“ 空白部分内容
  
  3，将求得的内容和原内容叠加
  
  4，重复2，3，直至空白部分都已填充
  
  5，获得的图像就是可以扫描的复原图
  
然后。。。你懂的。。。
