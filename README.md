# ButtonStyle
### 登录页按钮

#### 正常状态下的按钮样式

- 按钮长度330dp,高度45dp,圆角大小7dp,背景颜色 #4ECD7B，字体大小18sp,字体颜色白色（#FFFFFF）


![正常状态下的登录页按钮](https://raw.githubusercontent.com/zhenghuiC/ButtonStyle/master/src/main/res/mipmap-xxhdpi/ic_login_normal.png)

按钮代码
```
<Button
        android:layout_width="330dp"
        android:layout_height="45dp"
        android:layout_marginTop="5dp"
        android:background="@drawable/bg_login_normal"
        android:text="登陆页大按钮(正常状态)"
        android:textColor="#FFFFFF"
        android:textSize="18sp" />
```
背景的shape代码

```
<?xml version="1.0" encoding="utf-8"?>
<shape xmlns:android="http://schemas.android.com/apk/res/android">
    <solid android:color="#4ECD7B"/>
    <corners android:radius="7dp"/>
</shape>

```


![点击状态下的登录页按钮](https://raw.githubusercontent.com/zhenghuiC/ButtonStyle/master/src/main/res/mipmap-xxhdpi/ic_login_press.png)


