# RippleView [![](https://jitpack.io/v/xiedong11/RippleView.svg)](https://jitpack.io/#xiedong11/RippleView)

Material Design风格View点击水波荡效果



## Gradle

``` groovy
项目中添加jitpack仓库

allprojects {
		repositories {
			maven { url 'https://jitpack.io' }
		}
	}
	
Module中添加依赖


dependencies {
    compile 'com.github.xiedong11:RippleView:1.2'
    	}
====================================================================================
如果你的项目中引入后，项目目依赖包发生 Manifest Merge 冲突，请在Module把依赖改成如下：
compile ('com.github.xiedong11:RippleView:6e9f300a82'){
    exclude group: 'com.android.support'
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

**属性说明**

 * `rv_alpha`  Ripple透明度
 * `rv_color`  Ripple颜色
 * `rv_centered`   指定是否在当前View的正中间触发ripple
 * `rv_rippleDuration` ripple的持续时长
 * `rv_type`  Tpye可设置为rectangle|simpleRipple|doubleRipple
 * `rv_ripplePadding`  ripple设置padding
 * `rv_zoomScale` 设置View缩放的比例
 * `rv_zoom`  设置View是否最ripple缩放
 * `rv_zoomDuration`   zoom持续时长