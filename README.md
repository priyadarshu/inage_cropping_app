# Image cropping App

I always wanted to build my own image cropping app. So, I built it, though with references to Youtube Channel.

built using imagecroper and imagepicker plugins

Steps followed in creating the app

1. Add plugin image_picker: ^0.6.7+21 and image_cropper: ^1.3.1 (make sure you use the recent version)
2. Then add the below code to your AndroidManifest.xml file in the end before the </application

```
<intent-filter>
        <action android:name="android.intent.action.MAIN"/>
        <category android:name="android.intent.category.LAUNCHER"/>
 </intent-filter>
  </activity>
  <activity android:name="com.yalantis.ucrop.UCropActivity" android:screenOrientation="portrait" android:theme="@style/Theme.AppCompat.Light.NoActionBar"/>
    
```
3. The coding part UI design
4. Coding the logics
