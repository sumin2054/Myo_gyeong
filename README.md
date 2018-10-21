# Myo_gyeong


   <!--activity_main.xml text에서 -->
<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    <!--배경이미지설정 -->
    android:background="@drawable/d_0003">
    tools:context=".MainActivity">
 <ImageButton
        android:id="@+id/button"
        android:layout_width="35dp"
        android:layout_height="26dp"
        android:layout_marginEnd="16dp"
        android:layout_marginRight="16dp"
        android:layout_marginBottom="16dp"
        android:background="@drawable/btn1"
        android:onClick="btn"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent" />
</android.support.constraint.ConstraintLayout>
