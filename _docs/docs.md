---
layout: page
title: Docs
inline-title: Docs
permalink: docs.html
---
## Overview

URL Auto Redirector is a chrome extension that enables you to skip certain pages, mostly useless referral/ad pages, after you click on affiliate links.
By doing so, it gets you directly to your destination page.

## Installation

### Chrome WebStore

[![](https://developer.chrome.com/webstore/images/ChromeWebStore_Badge_v2_496x150.png)](https://chrome.google.com/webstore/detail/mckfcfnegaimgcgepikhdnajpkkhdnkn)

Download at [__Chrome WebStore__](https://chrome.google.com/webstore/detail/mckfcfnegaimgcgepikhdnajpkkhdnkn)

### Install Manually

1. Clone this project
2. Load ```src``` folder in ```developer mode```.

## Usage

### New Tab/Current Tab

Redirection can be done in either new tab or current tab. For original design, redirection in new tab is reserved to allow users to see the chain of redirections.

### Prompt Badge

While a redirection happens, the redirected page will prompt a ```Redirected by URL Auto Redirector``` badge.

We are considering to allow users to decide whether allow the badge occurs or not.

### Rules Setting

```Source```, ```Destination``` and ```RegExp``` are critical for a rule.

While ```RegExp``` is checked, URL Auto Redirector will parse ```Source``` and ```Destination``` using regular expression, following JavaScript RegExp engine. For more information about regular expression, check [https://developer.mozilla.org/en/docs/Web/JavaScript/Guide/Regular_Expressions](https://developer.mozilla.org/en/docs/Web/JavaScript/Guide/Regular_Expressions).

Otherwise, it would be a whole-word matching.

Hint: Protocols(e.g. ```http://```) cannot be omitted.

### Preset Rules
We have several preset rules as default. You might add your own rule in the option page.

We encourage users to share rules by ```Export``` ```Import``` rules.

And we receive orders for adding your awesome rules in preset rules list. See [contributing](#contributing).

### Compatibility
Current version has been tested on Chrome 64-bit, version 44 through 51, both on Mac OS and Windows.

Theoretically, Chrome for Linux should be okay.

## Contributing

* If you have a question about using URL Auto Redirector, start a discussion on [Gitter](https://gitter.im/UrlAutoRedirector/UrlAutoRedirector).
* If you think you've found a bug with URL Auto Redirector, [open an issue](https://github.com/crispgm/UrlAutoRedirector/issues/new).
* If you have useful rules in getting convenience by URL Auto Redictor, comment in the [Collection of awesome rules](https://github.com/UrlAutoRedirector/UrlAutoRedirector/issues/17) or pull request for [Awesome Rules](https://github.com/UrlAutoRedirector/awesome-rules).
* PR(Pull Request) is welcomed.