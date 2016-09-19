# View 类的XML属性、相关方法和说明
###对齐
表格可以指定对齐方式

|           XML属性           |         相关方法                       |               说明                                 |
| :-------------------------- |:-------------------------------------- | :--------------------------------------------------|
| android:alpha               | setAlpha(float)                        | 设置该证件的透明度                                 |
| android:background          | setBackgroundResource(int)             | 设置该组件的背景颜色                               |
| android:clickable           | setClickable(boolean)                  | 设置该组件是否可以激发单击事件                     |
| android:contentDescription  | setContentDescription(CharSequence)    | 设置该组件的内容描述信息                           |
| android:drawingCacheQuality | setContentCacheQuality(int)            | 设置该组件所使用的绘制缓存的质量                   |
| android:elevation           | setElevation(float)                    | 设置该组件“浮”起来的高度，通过设置该属性可以让组件呈现3D效果|
| android:fadeScrollbars      | setScrollbarFadingEnable(boolean)      | 当不使用该组件的滚动条时,是否淡出显示滚动条        |
| android:fadingEdge          | setVerticalFadingEdgeEnable(boolean)   | 设置滚动该组件的组件边界是否使用淡出效果           |
| android:fadingEdgeLength    | getVerticalFadingEdgeLength()          | 设置淡出边界的长度                                 |
| android:focusable           | setFocusable(boolean)                  | 设置该组件是否可以得到焦点                         |
| android:focusableInTouchMode| setFocusableInTouchMode(boolean)       | 设置该组件在触摸模式下是否可以得到焦点             |
| android:id                  | setId(int)                             | 设置该组件的唯一标识。在java代码中通过findViewById获取|
| android:isScrollContainer   | setScrollContainer(boolean)            | 设置该组件是否会强制手机屏幕一直打开               |
| android:keepScreenOn        | setKeepScreenOn(boolean)               | 设置该组件是否会强制手机屏幕一直打开               |
| android:longClickable       | setLongClickable(boolean)              | 设置该组件是否可以相应长单击事件                   |
| android:minHeight           | setMinimumHeight(int)                  | 设置该组件的最小高度                               |
| android:minWidth            | setminimumWidth(int)                   | 设置该组件的最小宽度                               |
| android:nextFocusDown       | setNextFocusDownId(int)                | 设置焦点在该组件上，且单击向下键时获得焦点的组件Id |
| android:nextFocusLeft       | setNextFocusLeftId(int)                | 设置焦点在该组件上，且单击向左键时获得焦点的组件Id |
| android:nextFocusRight      | setNextFocusRight(int)                 | 设置焦点在该组件上，且单击向右时获得焦点的组件Id   |
| android:nextFocusUp         | setNextFocusUp(int)                    | 设置焦点在该组件上，且单击向上时获得焦点组件id     |
