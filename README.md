# SimpleArcLoader
- bored of seeing the same old Android Loader ? SimpleArcLoader is one thing you should try. 

# Preview 
<img src="https://github.com/generic-leo/SimpleArcLoader/blob/master/preview/simplearcdialog_1.gif" width="30%">
<img src="https://github.com/generic-leo/SimpleArcLoader/blob/master/preview/simplearcdialog_2.gif" width="30%">

# Setup


## Example 1
To show dialog
```java
SimpleArcDialog mDialog = new SimpleArcDialog(this);
mDialog.setConfiguration(new ArcConfiguration(this));
mDialog.show();
```
## Example 2 
Making use of just the Loader
```xml
<com.leo.simplearcloader.SimpleArcLoader
  android:visibility="visible"
  android:id="@+id/loader"
  android:layout_centerInParent="true"
  android:layout_width="60dp"
  android:layout_height="60dp"
  custom:arc_style="simple_arc"
  custom:arc_speed="medium"
  custom:arc_margin="3dp">
</com.leo.simplearcloader.SimpleArcLoader>
```
## Example 3
Customizing Dialog using ArcConfiguration 
```java
ArcConfiguration configuration = new ArcConfiguration(context);
configuration.setLoaderStyle(SimpleArcLoader.STYLE.COMPLETE_ARC);
configuration.setText("Please wait..");

mDialog.setConfiguration(configuration);
```
## More Customizations 
- please refer the sample with some of the basic customization.

# Developed By
- prathamesh.s1989@gmail.com

# License

  Copyright 2016 Prathamesh Sawant

  Licensed under the Apache License, Version 2.0 (the "License");
  you may not use this file except in compliance with the License.
  You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

  Unless required by applicable law or agreed to in writing, software
  distributed under the License is distributed on an "AS IS" BASIS,
  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
  See the License for the specific language governing permissions and
  limitations under the License.

