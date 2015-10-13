cordova-plugin-mauron85-background-geolocation-phonegapbuild
==============================

Fork notice
==============================

This is fork of [cordova-plugin-mauron85-background-geolocation](https://github.com/mauron85/cordova-plugin-background-geolocation).
The only reason to fork is that [Adobe® PhoneGap™ Build](http://build.phonegap.com) does not support external frameworks like google-play-services directly.

The documentation and code base will stay at former location [cordova-plugin-background-geolocation](https://github.com/mauron85/cordova-plugin-background-geolocation).

## Registering plugin for Adobe® PhoneGap™ Build

To register plugin add following line into your config.xml:

```
<gap:plugin name="cordova-plugin-mauron85-background-geolocation-phonegapbuild" source="npm"/>
```

NOTE: If you're using *hydration*, you have to download and reinstall your app with every new version of the plugin, as plugins are not updated.

## Licence ##

[Apache License](http://www.apache.org/licenses/LICENSE-2.0)

Copyright (c) 2013 Christopher Scott, Transistor Software

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
