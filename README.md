# PopupWindow-camera
Andorid 6.0权限，编辑头像，点击按钮弹出PopupWindow，打开相机或相册选择头像并裁剪后显示在ImageView上。
参考  http://www.jianshu.com/p/64baf3f9c38f   Android 6.0后权限申请工具库的用法
工具库的用法：
project's build.gradle (工程下的 build.gradle)：

allprojects {
        repositories {
            ...
            maven { url 'https://jitpack.io' }
        }
    }

module's build.gradle (模块的build.gradle)：

dependencies {
    compile 'com.github.Jerey-Jobs:PermissionTools:1.5'
}

参考  http://blog.csdn.net/harvic880925/article/details/43163175  拍照、相册及裁剪的终极实现
