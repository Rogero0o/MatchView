# Android MatchView

This project is learned from (https://github.com/liaohuqiu/android-Ultra-Pull-To-Refresh) .<br>
Thanks for liaohuqiu..<br>

I like the animation in that project...So i studied his codes and make this..<br>

![](http://ww1.sinaimg.cn/mw690/a695acdegw1emytnk4s45g20eg0mk490.gif)

..As you see right now,wish you like it.

## Demo

[Download Demo](https://raw.githubusercontent.com/Rogero0o/MatchView/master/demo/MatchView_Demo_V1.0.apk)

### Step

Import this project into android studio..it's built with it.

###  Usage

#### jcenter

gradle
```
compile 'com.roger.match.library:library:1.0.1'
```

##### Config in xml

```xml
 xmlns:match="http://schemas.android.com/apk/res-auto"

<com.roger.match.library.MatchTextView
        match:text="MATCH VIEW"
        match:textSize="30sp"
        match:textColor="#ffffff"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content" />
        
<com.roger.match.library.MatchButton
        match:text="Yes"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content" />
```

##### Or config in java code

```java
// the following are default settings
 mMatchTextView.setText("MATCH VIEW");
 mMatchTextView.setTextSize(30);
 mMatchTextView.setTextColor(Color.WHITE);
// setProgress  float 0-1
 mMatchTextView.setProgress(0.5f);
```


## About me

A small guy  in mainland FUJIAN China.

If you have any new idea about this project, feel free to tell me ,Tks. :smiley:

[![Android Arsenal](https://img.shields.io/badge/Android%20Arsenal-MatchView-brightgreen.svg?style=flat)](https://android-arsenal.com/details/1/1194)

## License

	The MIT License (MIT)

	Copyright © 2015 Roger

	Permission is hereby granted, free of charge, to any person obtaining a copy
	of this software and associated documentation files (the "Software"), to deal
	in the Software without restriction, including without limitation the rights
	to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
	copies of the Software, and to permit persons to whom the Software is
	furnished to do so, subject to the following conditions:

	The above copyright notice and this permission notice shall be included in
	all copies or substantial portions of the Software.

	THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
	IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
	FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
	AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
	LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
	OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
	THE SOFTWARE.
