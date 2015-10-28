# iOS-CFFlowButtonView

# 描述
CFFlowButtonView是一个对按钮实现流式布局的控件。自动适配屏幕。

![竖屏显示](http://img.blog.csdn.net/20151028143252885)

![横屏显示](http://img.blog.csdn.net/20151028143306518)



# 安装
1. 拖入CFFlowButtonView文件夹下的文件至项目中。
# 使用

实例化一个CFFlowButtonView对象

```
CFFlowButtonView *flowButtonView = [[CFFlowButtonView alloc] initWithButtonList:buttonList];
```
注意：对CFFlowButtonView设置约束时不需要设置高度相关的约束。

更多用法可以查看DEMO。
