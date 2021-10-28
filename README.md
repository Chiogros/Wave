# Wave
A wave View for Android apps.

## Files
- `Wave.java`: view class
- `attrs.xml`: attributes list and types

## How to use
In your activity layout, set
```Java
// /*package name*/ refers to something like `com.example.appname`
</*package name*/.folder.Wave
	xmlns:custom="http://schemas.android.com/apk/res//*package name*/"
	android:layout_width="match_parent"
	android:layout_height="125dp"
	custom:numberOfWaves="2"
	custom:waveGravity="top"
/>
```

## How it renders
<img src="screenshot/wave.png" alt="Wave example" width="200"/>
