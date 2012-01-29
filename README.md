# Redmon

** Work in progress in the very early stages of dev **

Simple sinatra based dashbord for redis.  After seeing the [fnordmetric](https://github.com/paulasmuth/fnordmetric)
project I was inspired to write this.  Some of the ideas there have be carried over here.

[ ![Build status - Travis-ci](https://secure.travis-ci.org/steelThread/redmon.png) ](http://travis-ci.org/steelThread/redmon)

----

Watch your redis server live.

![](http://dl.dropbox.com/u/27525257/dash-new.png)

----

Interact with redis using a familiar cli interface.

![](http://dl.dropbox.com/u/27525257/cli-new.png)

----

Dynamically update your server configuration.

![](http://dl.dropbox.com/u/27525257/configuration-new.png)

----

Intuitively introspect registered keys.  ** Coming Soon **

----

## Usage
Note:  Current version of Redmon is dependent on [Highcharts JS](http://www.highcharts.com/) which is not included with this repo and requires a license.  This will be replaced with something open source friendly in the future.

Currently not a registered gem, but soon.  For now clone the repo &

```bash
$ bundle install
$ ruby sample/app.rb
```

If you want to simulate a weak load on redis

```bash
$ ruby sample/load_sim.rb
```

Open your browser to 0.0.0.0:4567

License

Copyright (c) 2012 Sean McDaniel

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to use, copy and modify copies of the Software, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.