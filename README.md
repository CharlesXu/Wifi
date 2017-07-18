#-----关于投屏的几个demo    
1.Miracast  		需要更改部分源码，在RTD平台下可用   
2.MediaPlay_DLNA	需要依赖so库  
3.Airplay		需要移植，未测试   
4.WifiDirect		未测试

#------20170711 update     
删除原来的DLNA代码    
增加新版DLNA代码，兼容各大Android平台，注：由于Android5.0以上使用ART机制，底层库的反射函数可能需要更改      
     
使用PlatinumKit库去发现，连接设备，APP进行播放等操作    
关于DLNA的编译可参考博客：http://www.cnblogs.com/pngcui/p/7153933.html
