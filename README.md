Official source:

https://android.googlesource.com/platform/frameworks/opt/datetimepicker/
(Android 4.3+)

#DateTimePicker 

DateTimePicker is a library which contains the beautiful DatePicker and TimePicker that can be seen in the new Google Agenda app.

I've removed all requirements for the support library and for nineoldandroids, so this works for projects that do not want the support

library

**This modified version of the picker is available for 3.1+. For 2.1+, look [upstream][1]**.

You have a recurrence picker in the same style [here](https://github.com/Shusshu/Android-RecurrencePicker).

## WARNING

* Accessibility is missing for DatePicker on all devices and Below ICS devices for TimePicker.
* Scroll adjustment is missing below ICS devices for TimePicker and DatePicker.

## Description

This library reproduces as much as possible the original picker contained in the new Google Agenda app.

![Example Image][2]

Try out the sample APK [here][3]

Or browse the [source code of the sample application][4] for a complete example of use.

## Usage

Using the library is simple, just look at the source code of the provided sample [here][5]

## Acknowledgements

* Thanks to Google for this beautiful picker and to Flavien Laurent and others for putting it together

## License

    Copyright 2013 Flavien Laurent (DatePicker) edisonw (TimePicker)

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

 [1]: https://github.com/flavienlaurent/datetimepicker
 [2]: https://raw.github.com/biboune/datetimepicker/master/graphics/img1.png
 [3]: https://raw.github.com/biboune/datetimepicker/master/datetimepicker-sample.apk
 [4]: https://github.com/biboune/datetimepicker/tree/master/datetimepicker-sample
 [5]: https://github.com/biboune/datetimepicker/blob/master/datetimepicker-sample/src/com/fourmob/datetimepicker/sample/MainActivity.java
