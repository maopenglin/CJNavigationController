
##CJNavigationController是什么?
是一个仿天猫等一些APP，滑动全屏返回的插件。

![(下拉刷新02-动画图片)](http://files.cnblogs.com/files/runssnail/show.gif)

##使用方法
* 继承并用CJNavigationController创建NavigationController

##注意点：
```obj
    一定要删除系统自带的滑动返回，删除方法有很多种，可以通过设置
    self.navigationController.interactivePopGestureRecognizer.enabled = NO;
```
    
