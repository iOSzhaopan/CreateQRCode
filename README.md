# CreateQRCode
一个生成二维码的Demo
##一句话帮你搞定二维码生成
```objc
/**
     得到二维码的方法，如果不需要中间的头像可以将iconImage传空或者iconImageSize传0
     
     - parameter iconImage: 二维码中间的头像(穿空时候不显示)
     - parameter message:   生成二维码包含的信息
     - parameter iconImageSize:   头像的大小设置太大容易扫不出二维码建议(20)
     
     - returns: 返回二维码
     */
imageView.cerateQRCode(UIImage(named: "xuexi8_logo"), message: "xxx", iconImageSize: 20)
```
