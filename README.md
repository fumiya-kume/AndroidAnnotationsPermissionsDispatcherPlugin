[![](https://jitpack.io/v/AleksanderMielczarek/AndroidAnnotationsPermissionDispatcherPlugin.svg)](https://jitpack.io/#AleksanderMielczarek/AndroidAnnotationsPermissionDispatcherPlugin)

# AndroidAnnotationsPermissionDispatcherPlugin

Plugin for [AndroidAnnotations](http://androidannotations.org/) allowing to use it together with [PermissionsDispatcher](https://github.com/hotchemi/PermissionsDispatcher).
All you have to do is to include it in your dependencies.

## Usage

Add it in your root build.gradle at the end of repositories:

```groovy
allprojects {
	repositories {
        ...
        maven { url "https://jitpack.io" }
    }
}
```

Add the dependency

```groovy
dependencies {
    apt 'com.github.AleksanderMielczarek:AndroidAnnotationsPermissionDispatcherPlugin:0.1.0'
}
```

## License

    Copyright 2016 Aleksander Mielczarek

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.