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
    compile 'com.github.xiedong11:RippleView:1.2'
    	}
}
```
    
## Usage
    
**XML**

``` xml
<com.zhuandian.rippleview.RippleView
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    app:rv_alpha="99"
    app:rv_color="#faf"
    app:rv_centered="true"
    app:rv_type="simpleRipple"
    app:rv_zoomDuration="300"
    app:rv_ripplePadding="200px"
    />
    <ImageView
        android:id="@+id/imageview"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent" />
</com.zhuandian.rippleview.RippleView>
``` 

**属性**

 
