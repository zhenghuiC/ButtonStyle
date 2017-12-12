# ButtonStyle
### 一、登录页按钮

##### 1、 正常状态下的按钮样式

- 按钮长度330dp,高度45dp,圆角大小7dp,背景颜色 #4ECD7B，字体大小18sp,字体颜色白色（#FFFFFF）


![正常状态下的登录页按钮样式](https://raw.githubusercontent.com/zhenghuiC/ButtonStyle/master/src/main/res/mipmap-xxhdpi/ic_login_normal.png)

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

##### 2、 点击状态下的按钮样式

- 按钮长度330dp,高度45dp,圆角大小7dp,背景颜色 #43C170，字体大小18sp,字体颜色白色（#FFFFFF）

![点击状态下的登录页按钮样式](https://raw.githubusercontent.com/zhenghuiC/ButtonStyle/master/src/main/res/mipmap-xxhdpi/ic_login_press.png)

button的代码如上面一致，背景换一下即可


按钮背景shape的代码
```
<?xml version="1.0" encoding="utf-8"?>
<shape xmlns:android="http://schemas.android.com/apk/res/android">
    <solid android:color="#43C170"/>
    <corners android:radius="7dp"/>
</shape>
```

##### 3、不可用状态下的按钮
- 按钮长度330dp,高度45dp,圆角大小7dp,背景颜色 #46A99D，字体大小18sp,字体颜色白色（#B0D7D2）

![不可用状态下的登陆页按钮样式](https://raw.githubusercontent.com/zhenghuiC/ButtonStyle/master/src/main/res/mipmap-xxhdpi/ic_login_disable.png)

button代码样式
```
<Button
        android:layout_width="330dp"
        android:layout_height="45dp"
        android:layout_marginTop="10dp"
        android:background="@drawable/bg_login_disable"
        android:text="登陆页大按钮(不可用状态)"
        android:textColor="#B0D7D2"
        android:textSize="18sp" />
```

按钮背景shape的代码

```
<?xml version="1.0" encoding="utf-8"?>
<shape xmlns:android="http://schemas.android.com/apk/res/android">
    <solid android:color="#46A99D"/>
    <corners android:radius="6dp"/>
</shape>
```

### 二、操作页界面按钮

##### 提交按钮

- 按钮宽度100dp，高度35dp，字体颜色白色，背景颜色#F2A730，圆角大小5dp，字体大小16sp

![操作界面提交按钮样式](https://raw.githubusercontent.com/zhenghuiC/ButtonStyle/master/src/main/res/mipmap-xxhdpi/ic_operate_orange.png)

button的代码：

```
<Button
    android:layout_width="100dp"
    android:layout_height="35dp"        
    android:background="@drawable/bg_operate_normal_orange"
    android:text="提交"
    android:textColor="#FFFFFF"
    android:textSize="16sp" />
```
按钮背景shape的代码：

```
<?xml version="1.0" encoding="utf-8"?>
<shape xmlns:android="http://schemas.android.com/apk/res/android">
    <corners android:radius="5dp"/>
    <solid android:color="#F2A730"/>
</shape>
```

##### 取消按钮

- 按钮宽度100dp，高度35dp，字体颜色#333333，背景颜色#e3e3e3，圆角大小5dp，字体大小16sp，边框颜色#C1C1C1，边框宽度0.5dp

![取消按钮样式](https://raw.githubusercontent.com/zhenghuiC/ButtonStyle/master/src/main/res/mipmap-xxhdpi/ic_operate_gray.png)

button代码：
```
<Button
    android:layout_width="100dp"
    android:layout_height="35dp"
    android:layout_marginLeft="20dp"
    android:background="@drawable/bg_operate_normal_gray"
    android:text="取消"
    android:textColor="#333333"
    android:textSize="16sp" />
```

按钮背景shape代码
```
<?xml version="1.0" encoding="utf-8"?>
<shape xmlns:android="http://schemas.android.com/apk/res/android">
    <corners android:radius="5dp"/>
    <solid android:color="#e3e3e3"/>
    <stroke android:width="0.5dp" android:color="#C1C1C1"/>
</shape>
```

### 三、列表上的操作按钮

- 字体大小12sp，字体颜色白色，按钮宽度50dp，按钮高度30dp，圆角大小5dp


button代码
```
 <Button
    android:layout_width="50dp"
    android:layout_height="30dp"
    android:background="@drawable/bg_list_orange"
    android:text="按钮"
    android:textColor="#FFFFFF"
    android:textSize="12sp" />
```


（背景颜色#FF7200）

![橘黄色按钮](https://raw.githubusercontent.com/zhenghuiC/ButtonStyle/master/src/main/res/mipmap-xxhdpi/ic_list_orange.png)

（背景颜色#58C37E）

![绿色](https://raw.githubusercontent.com/zhenghuiC/ButtonStyle/master/src/main/res/mipmap-xxhdpi/ic_list_green.png)


（背景颜色#E3E3E3）

![灰色](https://raw.githubusercontent.com/zhenghuiC/ButtonStyle/master/src/main/res/mipmap-xxhdpi/ic_list_gray.png)



shape样式代码：

```
<?xml version="1.0" encoding="utf-8"?>
<shape xmlns:android="http://schemas.android.com/apk/res/android">
    <corners android:radius="5dp"/>
    <solid android:color="#FF7200"/>
</shape>
```

### 四、状态按钮

##### 1、完成按钮
- 按钮宽度50dp，按钮高度25dp，字体大小12sp，字体颜色#58C37E，背景边框颜色#58C37E，背景边框宽度1dp

![完成状态按钮](https://raw.githubusercontent.com/zhenghuiC/ButtonStyle/master/src/main/res/mipmap-xxhdpi/ic_status_green.png)

button代码：

```
 <Button
    android:layout_width="50dp"
    android:layout_height="25dp"
    android:background="@drawable/bg_status_green"
    android:text="状态"
    android:textColor="#58C37E"
    android:textSize="12sp" />
```

背景shape代码：
```
<?xml version="1.0" encoding="utf-8"?>
<shape xmlns:android="http://schemas.android.com/apk/res/android">
    <stroke android:color="#58C37E" android:width="1dp"/>
    <corners android:radius="3dp"/>
</shape>
```

##### 2、未完成按钮
- 按钮宽度50dp，按钮高度25dp，字体大小12sp，字体颜色#FF7200，背景边框颜色#FF7200，背景边框宽度1dp

![未完成状态按钮](https://raw.githubusercontent.com/zhenghuiC/ButtonStyle/master/src/main/res/mipmap-xxhdpi/ic_status_orange.png)

button代码：

```
 <Button
    android:layout_width="50dp"
    android:layout_height="25dp"
    android:background="@drawable/bg_status_green"
    android:text="状态"
    android:textColor="#FF7200"
    android:textSize="12sp" />
```

背景shape代码：
```
<?xml version="1.0" encoding="utf-8"?>
<shape xmlns:android="http://schemas.android.com/apk/res/android">
    <stroke android:color="#FF7200" android:width="1dp"/>
    <corners android:radius="3dp"/>
</shape>
```







