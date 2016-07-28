# PhotoViewDemo
仿微信的个人相册，来回浏览个人图片和视频，其中图片时需要实现双击放大和缩小的。那么PhotoView完美解决这个问题。这里记录一下，写一个Studio的demo，我觉得每次去博客上找那些文章时，最想要的还是代码，设身处地的为同僚们着想，我还是写个简单的应用。方便大家参考和使用。
	在grandle中导入photoView。
compile 'com.commit451:PhotoView:1.2.4'
然后xml文件中使用，就行了。
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context="com.abings.photoviewdemo.MainActivity">

    <uk.co.senab.photoview.PhotoView
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:src="@drawable/a"
        />
</RelativeLayout>
这样放入一张图片就能放大缩小了。简单实用，大家会爱上它的。

