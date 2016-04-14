
AVLoadingIndicatorView
===================

## Introduction
LoadingIndicatorView is a collection of nice loading animations for Android.

You can also find iOS version of this [here](https://github.com/ninjaprox/NVActivityIndicatorView).

## Demo
![](https://github.com/googolmo/AVLoadingIndicatorView/blob/master/Demo2.gif)

## Usage

### Step 1

Add dependencies in build.gradle.
```groovy
    repositories {
        maven { url  "https://dl.bintray.com/googolmo/maven" }
    }

    dependencies {
       compile 'im.amomo.loading:library:1.0.7'
    }
```

### Step 2

Add the LoadingIndicatorView to your layout:
```java
    <im.amomo.loading.LoadingIndicatorView
        android:id="@+id/LoadingIndicatorView"
        android:layout_width="wrap_content"  //or your custom size
        android:layout_height="wrap_content"  //or your custom size
        android:visibility="visible"  //visible or gone
        app:indicator="BallPulse"
        app:indicator_color="your color"
        />
```

### Step 3

It's very simple use just like Progressbar.
```java
   void startAnim(){
        findViewById(R.id.LoadingIndicatorView).setVisibility(View.VISIBLE);
   }
   
   void stopAnim(){
        findViewById(R.id.LoadingIndicatorView).setVisibility(View.GONE);
   }
   
```

## Indicators

As seen above in the **Demo**, the indicators are as follows:

**Row 1**
 * `BallPulse`
 * `BallGridPulse`
 * `BallClipRotate`
 * `BallClipRotatePulse`

**Row 2**
 * `SquareSpin`
 * `BallClipRotateMultiple`
 * `BallPulseRise`
 * `BallRotate`

**Row 3**
 * `CubeTransition`
 * `BallZigZag`
 * `BallZigZagDeflect`
 * `BallTrianglePath`

**Row 4**
 * `BallScale`
 * `LineScale`
 * `LineScaleParty`
 * `BallScaleMultiple`

**Row 5**
 * `BallPulseSync`
 * `BallBeat`
 * `LineScalePulseOut`
 * `LineScalePulseOutRapid`

**Row 6**
 * `BallScaleRipple`
 * `BallScaleRippleMultiple`
 * `BallSpinFadeLoader`
 * `LineSpinFadeLoader`

**Row 7**
 * `TriangleSkewSpin`
 * `Pacman`
 * `BallGridBeat`
 * `SemiCircleSpin`

## Thanks
- [nineoldandroids](https://github.com/JakeWharton/NineOldAndroids)
- [NVActivityIndicatorView](https://github.com/ninjaprox/NVActivityIndicatorView)
- [Connor Atherton](https://github.com/ConnorAtherton)

##Contact me

 If you have a better idea or way on this project, please let me know, thanks :)

[Email](mailto:81813780@qq.com)

[Weibo](http://weibo.com/601265161)




### License
```
Copyright 2015 jack wang

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

