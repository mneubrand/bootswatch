Bootswatch
==========

<<<<<<< HEAD
Bootswatch is a collection of free themes for [Bootstrap](http://getbootstrap.com/). Check it out at [bootswatch.com](http://bootswatch.com).

Usage
-----
Download the `bootstrap.min.css` file associated with a theme and replace Bootstrap's default stylesheet.

The themes are also hosted on [BootstrapCDN](http://www.bootstrapcdn.com/bootswatch/).

 Rails users should check out:

* [twitter-bootswatch-rails](https://github.com/scottvrosenthal/twitter-bootswatch-rails) if using _LESS_.
* [bootswatch-rails](https://github.com/maxim/bootswatch-rails) if using _SASS_.
=======
Bootswatch is a collection of free themes for [Twitter Bootstrap](http://twitter.github.com/bootstrap/). Check it out at [bootswatch.com](http://bootswatch.com).

On GitHub, the source is located in the [gh-pages branch](https://github.com/thomaspark/bootswatch/tree/gh-pages).

Usage
-----
Head over to [Bootswatch](http://bootswatch.com) and download the `bootstrap.min.css` file associated with a theme.

In Bootstrap’s CSS directory, you’ll find a stylesheet in full (`bootstrap.css`) and minified (`bootstrap.min.css`) forms. Rename them or move them to a safe place, and replace with the downloaded file. If you ever change your mind, simply drop in another theme or switch back to the original.

For use with Rails, check out [bootswatch-rails](https://github.com/maxim/bootswatch-rails) (Sass) and [twitter-bootswatch-rails](https://github.com/scottvrosenthal/twitter-bootswatch-rails) (LESS).
>>>>>>> 4f965965b6e8a39502e571fea51523ca31d798d7


Customization
------
<<<<<<< HEAD
Bootswatch is open source and you’re welcome to modify the themes.

Each theme consists of two LESS files. `variables.less`, which is included by default in Bootstrap, allows you to customize [these settings](http://getbootstrap.com/customize/#less-variables). `bootswatch.less` introduces more extensive structural changes.

These files are also available in SASS.

Check out the [Help page](http://bootswatch.com/help/) for more details on building your own theme.
=======
Bootswatch is an open source project, and you’re welcome to modify the themes further. If you’re interested, fork or follow the GitHub repository. The files of interest are in the `gh-pages` branch.

Each raw theme consists of two LESS files. One is `variables.less`, which is included by default in Bootstrap and allows you to customize [these settings](http://twitter.github.com/bootstrap/customize.html#variables). The other is called `bootswatch.less` and introduces more extensive structural changes.

Check out the README in the [swatchmaker directory](https://github.com/thomaspark/bootswatch/tree/master/swatchmaker) for step-by-step instructions on building your own swatch.
>>>>>>> 4f965965b6e8a39502e571fea51523ca31d798d7

API
-----

<<<<<<< HEAD
A simple API is available for integrating your platform with Bootswatch. Send your request to `http://api.bootswatch.com/3/`.

The swatch objects are returned in an array called `themes`, each one with the following properties:  `name`, `description`, `preview`, `thumbnail`, `css`, `cssMin`, `less`, and `lessVariables`.

More info at http://bootswatch.com/help/#api

Author
------
Thomas Park

+ http://github.com/thomaspark
+ http://thomaspark.co

Thanks
------
[Mark Otto](https://github.com/mdo) and [Jacob Thornton](https://github.com/fat) for [Bootstrap](https://github.com/twbs/bootstrap).

[Jenil Gogari](http://www.jgog.in/) for his contributions to the Flatly theme.

[James Taylor](https://github.com/jostylr) for [cors-lite](https://github.com/jostylr/cors-lite).

[Corey Sewell](https://github.com/cjsewell) for SASS conversion.
=======
A simple API is available for integrating your platform with Bootswatch.

The swatch objects are housed in an array called `themes`, and each swatch has the following properties:  `name`, `description`, `preview`, `thumbnail`, `css`, `css-min`, `less`, and `less-variables`.

CORS and JSONP are supported. Send your request to `http://api.bootswatch.com`.

A simple demo, using mustache.js for templating: http://jsbin.com/asowud/1/edit

Feedback
------
Please send feedback to thomas@thomaspark.me. For more information, visit http://thomaspark.me/2012/02/introducing-bootswatch/.

Author
------
[Thomas Park](http://github.com/thomaspark)

+ http://thomaspark.me

Thanks
------
[Mark Otto](http://github.com/markdotto) and [Jacob Thornton](http://github.com/fat) for [Bootstrap](https://github.com/twitter/bootstrap).

[James Taylor](http://github.com/jostylr) for [cors-lite](https://github.com/jostylr/cors-lite).

[Zack Maril](http://github.com/zmaril) for [bootswatch/swatchmaker/watcher.rb](https://github.com/thomaspark/bootswatch/blob/master/swatchmaker/watcher.rb).
>>>>>>> 4f965965b6e8a39502e571fea51523ca31d798d7


Copyright and License
----
<<<<<<< HEAD
Copyright 2014 Thomas Park

Code released under the MIT License.
=======
Copyright 2012 Thomas Park

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
>>>>>>> 4f965965b6e8a39502e571fea51523ca31d798d7
