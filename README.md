# Rotate3D
This is a 3D ratate library ,You can easy use it

# Preview

![img](image/image.gif)

# Demo Apk

you can scan the qrcode for download demo apk

![](image/qrcode.png)

# Feature
- Light
- Noninvasive，You don't need to make changes to existing code.
- Wide applicability，It is available for all views

# Getting started

In your build.gradle:

    dependencies {
       compile 'com.jzp:rotate3D:1.0.0'
    }
    

# Usage
  create Rotate3D 
  
       Rotate3D  anim = new Rotate3D.Builder(this)
            .bindParentView(parent_ll)
            .bindPositiveView(account_login_ll)
            .bindNegativeView(account_phone_ll)
            .create();
                                
  start the 3D animation 
   
       anim.transform();
  # Follow Me
![](http://upload-images.jianshu.io/upload_images/1750086-58e561db5db3a196.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)      
 
 # License
 
    Copyright 2017, Rotate3D , 1179537855@qq.com
 
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
 
        http://www.apache.org/licenses/LICENSE-2.0
 
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
