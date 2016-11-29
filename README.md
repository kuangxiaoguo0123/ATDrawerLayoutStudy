# ATDrawerLayoutStudy
Android DrawerLayout的使用

# ScreenShots
![](https://github.com/kuangxiaoguo0123/ATDrawerLayoutStudy/blob/master/screenshots/drawerLayout.gif)

# xml使用
````
<android.support.v4.widget.DrawerLayout
        android:id="@+id/drawer_layout"
        android:layout_width="match_parent"
        android:layout_height="match_parent">

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:gravity="center"
            android:text="主布局内容"
            android:textSize="18sp" />

        <LinearLayout
            android:layout_width="150dp"
            android:layout_height="match_parent"
            android:layout_gravity="start"
            android:background="@color/colorAccent"
            android:orientation="vertical">

            <Button
                android:id="@+id/left_button"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_gravity="center_horizontal"
                android:text="左侧布局" />
        </LinearLayout>
</android.support.v4.widget.DrawerLayout>
````
