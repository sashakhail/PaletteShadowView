# PaletteShadowView
This library shows the shadow of the image by it's palette color.

![final 1](https://user-images.githubusercontent.com/22986571/54155896-0f46d300-446b-11e9-9f6a-dfd72c5691e8.jpg)

[![Platform](https://img.shields.io/badge/platform-android-blue.svg)](http://developer.android.com/index.html)
[![API](https://img.shields.io/badge/API-19%2B-blue.svg?style=flat)](https://android-arsenal.com/api?level=19)

USAGE
-----
To add shadow in your imageview and color of the shadow will be according to pallete color in your image as well as other properties to handle shadow radius , color , offset and also shape of the image. you can grab this library using your Gradle file. 
 
Gradle
------

```
dependencies {
    ...
    implementation 'com.jackandphantom.android:paletteshadowview:1.0.1'
    implementation 'com.android.support:palette-v7:28.0.0'
}
```
##### 1.Few ScreenShots

XML
-----

```xml
<!-- <a> circular progressbar xml</a> -->
<com.jackandphantom.paletteshadowview.PaletteShadowView
        android:layout_width="250dp"
        android:layout_height="250dp"
        android:layout_marginTop="120dp"
        android:id="@+id/hr"
        app:paletteOffsetX="15"
        app:paletteOffsetY="15"
        android:layout_centerHorizontal="true"
        app:paletteSrc="@drawable/image"
        />
```
### xml attributes


  
  JAVA
-----
  ```xml

  ```
  
 ### Contribution
 If you want to add feature and find a bug feel free to contribute , you can  create issue related to bug , feature and send a pull.
 
 LICENCE
-----

 Copyright 2019 Ankit kumar

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
  
  Thanks to DingMouRen.
