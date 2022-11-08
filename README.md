# MY_GPS_Location

### build.gradle(:app)
```c
dependencies {
    ...
    //구글주소
    implementation 'com.google.android.gms:play-services-location:18.0.0'
}
```

### AndroidManigest.xml
```c
<uses-permission android:name="android.permission.ACCESS_FINE_LOCATION" />
<uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION"/>
```
