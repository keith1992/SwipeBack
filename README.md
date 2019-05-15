 # SwipeBack
Android SwipeBack，滑动返回，支持上下左右滑动返回关闭页面。
在原项目：https://github.com/ikew0ng/SwipeBackLayout 上新增了从上滑动的方向   

# Screenshot
<img src="https://github.com/keith1992/SwipeBack/blob/master/art/left.png">left  <img src="https://github.com/keith1992/SwipeBack/blob/master/art/right.png"> right

<img src="https://github.com/keith1992/SwipeBack/blob/master/art/bottom.png">bottom  <img src="https://github.com/keith1992/SwipeBack/blob/master/art/top.png"> top


# Usage
1、要实现滑动放回的Activity 必须继承 SwipeBackActivity

2、设置滑动方向

    mSwipeBackLayout.setEdgeTrackingEnabled(edgeFlag);
    saveTrackingMode(edgeFlag);
