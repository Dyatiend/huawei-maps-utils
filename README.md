# HUAWEI Map Kit Utility Library (Unofficial)

Utilities that are useful for a wide range of applications using the [HUAWEI Map Kit](https://developer.huawei.com/consumer/en/hms/huawei-MapKit).

- **Marker clustering** — handles the display of a large number of points
- **Heat maps** — display a large number of points as a heat map
- **IconGenerator** — display text on your Markers
- **Poly decoding and encoding** — compact encoding for paths, interoperability with Maps API web services
- **Spherical geometry** — for example: computeDistance, computeHeading, computeArea
- **KML** — displays KML data
- **GeoJSON** — displays and styles GeoJSON data

Forked from [Maps SDK for Android Utility Library](https://github.com/googlemaps/android-maps-utils)

## Declaring dependencies

To add a dependency on HUAWEI Map Kit Utility Library (Unofficial), you must add the JCenter Maven and Huawei Maven repositories to your project.

Add the dependencies for the artifacts you need in the `build.gradle` file for your app or module:

```groovy
dependencies {
    implementation 'me.tatiyanupanwong.supasin.android.libraries.huawei.maps:maps-utils:1.0.0-alpha02'
}  
```

For more information about dependencies, see [Add build dependencies](https://developer.android.com/studio/build/dependencies).

## Feedback

Your feedback helps make this library better. Let us know if you discover new issues or have ideas for improving this library. Please take a look at the [existing issues](https://github.com/SupasinTatiyanupanwong/huawei-maps-utils/issues) in this library before you create a new one.

Please keep in mind that the goal of this library is to provides the same functionality of the original one to the [HUAWEI Map Kit](https://developer.huawei.com/consumer/en/hms/huawei-MapKit). We will periodically keep this fork in sync.

## License

```
Copyright 2020 Supasin Tatiyanupanwong

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
