TintLayout
========== 

This library help you to achieve popular tint effect from view.

[![Android Arsenal](https://drive.google.com/uc?export=download&id=0BxPO_UeS7wScc1hHQ25mMjFUTTg)](http://android-arsenal.com/details/1/3315)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![Android](https://drive.google.com/uc?export=download&id=0BxPO_UeS7wSccEZaclNGN0R5OWc)](https://github.com/DevLight-Mobile-Agency)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![Download](https://drive.google.com/uc?export=download&id=0BxPO_UeS7wScYkVuVngxdlNYVDQ)](https://bintray.com/gigamole/maven/tintlayout/_latestVersion)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![License](https://drive.google.com/uc?export=download&id=0BxPO_UeS7wScU0tmeFpGMHVWNWs)](https://github.com/DevLight-Mobile-Agency/TintLayout/blob/master/LICENSE.txt)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![Codacy](https://drive.google.com/uc?export=download&id=0BxPO_UeS7wScSHhmckZyeGJDcXc)](https://www.codacy.com/app/gigamole53/TintLayout?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=DevLight-Mobile-Agency/TintLayout&amp;utm_campaign=Badge_Grade)

<p align="center">
    <img src="https://drive.google.com/uc?export=download&id=0BxPO_UeS7wScQTl2QUNMa2thdzg"/>
</p>

You can check the sample app [here](https://github.com/DevLight-Mobile-Agency/TintLayout/tree/master/app).

Warn
====
```
This library is not more supported. 
If you want to add new feature or fix a bug, grab source code and do it. 
If you think your fix or feature would be useful to other developers, 
I can add link of your repository to this README file. 
Thank you for using our libraries.
```

Download
========

You can download a `.aar` from GitHub's [releases page](https://github.com/GIGAMOLE/TintLayout/releases).

Or Gradle:  
```groovy
compile 'devlight.io:tintlayout:1.0.3'
```

Or Maven:  
```xml
<dependency>
  <groupId>devlight.io</groupId>
  <artifactId>tintlayout</artifactId>
  <version>1.0.3</version>
  <type>pom</type>
</dependency>
```

Or Ivy:  
```groovy
<dependency org='devlight.io' name='tintlayout' rev='1.0.3'>
  <artifact name='$AID' ext='pom'></artifact>
</dependency>
```

Android SDK Version
===================

`TintLayout` requires a minimum SDK version of 11.

Sample
========

<b>Parameters</b>

You can set such parameters as:

 - color:  
    allows you to set solid color.
    
 - colors:  
    allows you to create shadow with transparent etc.
    
 - angle:  
    allows you to set the angle of tint.

<b>Tips</b>

`TintLayout` must have child. Only one child.  
The angle can only be positive and be in range from 0 to 360.

<b>Init</b>

Check out in code init:  
```java
final TintLayout tintLayout = (TintLayout) findViewById(R.id.tint_layout);
tintLayout.setAngle(145);
```

To invalidate tint call this method:  
```java
tintLayout.invalidateTint();
```

And XML init:  
```xml
<devlight.io.library.TintLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        app:tl_angle="45"
        app:tl_color="@color/color"
        app:tl_colors="@array/colors">

    <View
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"/>

</devlight.io.library.TintLayout>
```

Getting Help
============

To report a specific problem or feature request, [open a new issue on Github](https://github.com/DevLight-Mobile-Agency/TintLayout/issues/new).

Author
======

Created by [Basil Miller](https://github.com/GIGAMOLE) - [@gigamole](mailto:gigamole53@gmail.com)
