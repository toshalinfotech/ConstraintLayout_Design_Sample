<font size="6"><b>ConstraintLayout Design sample</b></font>

This is the sample app that shows how to implement ConstraintLayout in Android

The steps that required to use ConstraintLayout:

<b>Include in your project</b>

Android Studio 2.2 and above

<font size="4"><b> Gradle dependencies </b></font>

ConstraintLayout library in <b>build.gradle</b> file with latest version:

<pre>dependencies 
{
  compile 'com.android.support.constraint:constraint-layout:x.x.x'
}</pre>

Add ConstraintLayout in <b>activity_main.xml </b> : 
<pre>

<androidx.constraintlayout.widget.ConstraintLayout
xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:layout_gravity="center">
    ...
    </androidx.constraintlayout.widget.ConstraintLayout></pre>
    

ScreenShots of output :
![upload_one](app/src/main/res/drawable/upload_one.jpg)
![upload_two](app/src/main/res/drawable/upload_two.png)
