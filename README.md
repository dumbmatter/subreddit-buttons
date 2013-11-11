UNOFFICIAL SUBREDDIT BUTTONS
============================

Showcase your subreddit's success with these simple, static buttons featuring dynamic subscriber counts and a link to your subreddit.

To get started, checkout http://jdscheff.github.io/subreddit-buttons/

This is based on Mark Otto's GitHub buttons: https://github.com/mdo/github-buttons



Usage
-----

These buttons are hosted via GitHub Pages, meaning all you need to do is include an iframe and you're set. Once included, you can configure it with various options. Here's the include:

``` html
<iframe src="http://jdscheff.github.io/subreddit-buttons/subreddit-btn.html?name=SUBREDDIT"
  allowtransparency="true" frameborder="0" scrolling="0" width="150" height="20"></iframe>
```

### Requirements

`name`<br>
Subreddit name (the part after /r/ in the URL)<br>

### Optional

`count`<br>
Optional flag to hide the subcriber count: set to `false`

`size`<br>
Optional flag for using a larger button: set to `large`

`r`<br>
Optional flag to hide "/r/" from being displayed before the name: set to `false`



Examples
--------

**Basic button**

``` html
<iframe src="http://jdscheff.github.io/subreddit-buttons/subreddit-btn.html?name=BasketballGM"
  allowtransparency="true" frameborder="0" scrolling="0" width="150" height="20"></iframe>
```

**Large button**

``` html
<iframe src="http://jdscheff.github.io/subreddit-buttons/subreddit-btn.html?name=BasketballGM&size=large"
  allowtransparency="true" frameborder="0" scrolling="0" width="225" height="30"></iframe>
```

**Button with /r/ hidden**

``` html
<iframe src="http://jdscheff.github.io/subreddit-buttons/subreddit-btn.html?name=BasketballGM"
  allowtransparency="true" frameborder="0" scrolling="0" width="130" height="20"></iframe>
```

**Button with no subscriber count**

``` html
<iframe src="http://jdscheff.github.io/subreddit-buttons/subreddit-btn.html?name=BasketballGM"
  allowtransparency="true" frameborder="0" scrolling="0" width="125" height="20"></iframe>
```

**Large button with /r/ hidden and no subscriber count**

``` html
<iframe src="http://jdscheff.github.io/subreddit-buttons/subreddit-btn.html?name=BasketballGM&size=large"
  allowtransparency="true" frameborder="0" scrolling="0" width="160" height="20"></iframe>
```

Limitations
-----------

For the first version, functionality is limited and some concessions were made:

- Width and height must be specificed for all buttons, and you will probably have to customize the width based on the length of your subreddit's name.
- All attributes must be passed through via URL parameters.
- CSS and javascript are all included in the same HTML file to reduce complexity and requests.

**Usage with SSL**

In order to avoid `insecure content` warnings when using GitHub Buttons on a page behind an SSL certificate, simply host a copy of the `github-btn.html` file on your secure directory and substitute your domain in the iframe include: 

``` html
<iframe src="https://YOURDOMAIN.com/github-btn.html?name=SUBREDDIT"
  allowtransparency="true" frameborder="0" scrolling="0" width="145" height="20"></iframe>
```

More refinement and functionalty is planned with open-sourcing--any help is always appreciated!



Bug tracker
-----------

Have a bug? Please create an issue here on GitHub at https://github.com/jdscheff/subreddit-buttons/issues.



Authors
-------

Made by Jeremy Scheff

+ http://www.jeremyscheff.com/
+ http://github.com/jdscheff

Heavily based on [GitHub Buttons](https://github.com/mdo/github-buttons) by Mark Otto

+ http://twitter.com/mdo
+ http://github.com/mdo



Copyright and license
---------------------

Copyright 2013 Jeremy Scheff.

Copyright 2011 Mark Otto.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this work except in compliance with the License.
You may obtain a copy of the License in the LICENSE file, or at:

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
