# RippleView [![](https://jitpack.io/v/xiedong11/RippleView.svg)](https://jitpack.io/#xiedong11/RippleView)

Material Design风格View点击水波荡效果



## Gradle

``` groovy
In Your Project

allprojects {
		repositories {
			maven { url 'https://jitpack.io' }
		}
	}
	
In Your Module
dependencies {
    compile 'com.github.xiedong11:RippleView:1.0'
}
```
    
## Usage
    
**XML**

``` xml
<com.github.xiedong11.RippleView
    android:layout_width="wrap_content"
    android:layout_height="wrap_content">
    <ImageView
        android:id="@+id/imageview"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent" />
</com.example.rippleview.RippleView>
``` 

**属性**

 
