## Lux sensor sample for Android Things

This sample demonstrates how to control the TSL256x light-to-digital sensor
and integrate it to the Android `SensorManager`.
                                                           


## Pre-requisites

- Android Things compatible board
- Android Studio 3.1+
- 1 [TSL2561 sensor](http://ams.com/eng/Products/Light-Sensors/Ambient-Light-Sensors/TSL2561)
- jumper wires
- 1 breadboard


# Build and install

On Android Studio, click on the "Run" button.

If you prefer to run on the command line, from this repository's root directory, type

```bash
./gradlew sample-tsl256x:installDebug
adb shell am start com.leinardi.android.things.sample.tsl256x/.LuxActivity
```

If you have everything set up correctly, in the logcat will be printed the values
from the accelerometer.


## License

Copyright 2018 Roberto Leinardi.

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements.  See the NOTICE file distributed with this work for
additional information regarding copyright ownership.  The ASF licenses this
file to you under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License.  You may obtain a copy of
the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  See the
License for the specific language governing permissions and limitations under
the License.
