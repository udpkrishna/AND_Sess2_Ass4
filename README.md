<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:paddingBottom="@dimen/activity_vertical_margin"
    android:paddingLeft="@dimen/activity_horizontal_margin"
    android:paddingRight="@dimen/activity_horizontal_margin"
    android:paddingTop="@dimen/activity_vertical_margin"
    tools:context="me.rk.linearlayoutsess2ass4.MainActivity">

    <RelativeLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:background="@color/accent_material_light"
        android:layout_alignParentTop="true"
        android:layout_alignParentLeft="true"
        android:layout_alignParentStart="true"
        android:layout_marginTop="74dp"
        android:layout_alignParentBottom="true">

        <EditText
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:inputType="textEmailAddress"
            android:ems="10"
            android:id="@+id/editText"
            android:layout_marginTop="67dp"
            android:background="@color/dim_foreground_material_dark"
            android:autoText="true"
            android:text="email"
            android:layout_alignParentTop="true"
            android:layout_centerHorizontal="true" />

        <EditText
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:inputType="textPassword"
            android:ems="10"
            android:id="@+id/editText2"
            android:background="@color/dim_foreground_material_dark"
            android:textColor="@color/abc_primary_text_disable_only_material_light"
            android:textIsSelectable="false"
            android:textColorHighlight="@color/abc_primary_text_material_light"
            android:text="password"
            android:layout_marginTop="51dp"
            android:layout_below="@+id/editText"
            android:layout_alignLeft="@+id/editText"
            android:layout_alignStart="@+id/editText" />

        <Button
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Login"
            android:id="@+id/button"
            android:layout_marginTop="28dp"
            android:layout_below="@+id/editText2"
            android:layout_centerHorizontal="true" />

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:textAppearance="?android:attr/textAppearanceLarge"
            android:text="Not a member? Sign up now"
            android:id="@+id/textView2"
            android:layout_marginTop="25dp"
            android:layout_below="@+id/button"
            android:layout_centerHorizontal="true"
            android:textColor="@color/abc_primary_text_material_dark" />
    </RelativeLayout>

    <LinearLayout
        android:orientation="vertical"
        android:layout_width="match_parent"
        android:layout_height="73dp"
        android:layout_row="0"
        android:layout_column="0"
        android:layout_alignParentTop="true"
        android:layout_alignParentRight="true"
        android:layout_alignParentEnd="true"
        android:background="@color/abc_input_method_navigation_guard"
        android:weightSum="1">

        <TextView
            android:layout_width="138dp"
            android:layout_height="wrap_content"
            android:textAppearance="?android:attr/textAppearanceMedium"
            android:text="LoginScreen"
            android:id="@+id/textView"
            android:layout_weight="0.53"
            android:textColor="@color/abc_primary_text_material_dark"
            android:layout_marginTop="20dp" />
    </LinearLayout>
</RelativeLayout>
