# 自定义View 之 自定义属性：

1 values目录下自定义属性名称

2 在自定义的View 的构造函数中传入属性值和属性名称，得到绑定后的 TypedArray。

从 TypedArray 中根据 1 中定义的名称作为 key，得到属性值。然后通过代码给控件赋值。

3 在布局文件中引起自定义View ，添加属性的命名空间，并给自定义View 的自定义属性附上值。

如：my_cycle 这个名字可以随意写，写完后 IDE 会提供添加命名空间，就会把……/res-auto 赋值给my_cycle.
xmlns:my_cycle="http://schemas.android.com/apk/res-auto”
my_cycle:textColor2="#FF0000"



# CustomTitleBar
自定义标题栏
![效果图](https://github.com/linglongxin24/CustomTitleBar/blob/master/screenshots/%E8%87%AA%E5%AE%9A%E4%B9%89%E6%A0%87%E9%A2%98%E6%A0%8F.jpg)
