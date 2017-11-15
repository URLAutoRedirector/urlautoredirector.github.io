---
layout: page
title: URLAutoSplicer
inline-title: URLAutoSplicer
permalink: /URLAutoSplicer/
---

## Introduction

URLAutoSplicer is a simple Chrome Extension, which redirects you to self-constructed URL instantly with context selection.

The initial idea of URLAutoSplicer comes from my former tool [Tieba Service Caller](https://github.com/crisp-archive/chrome_tieba_service_caller). It allows developers to call API with context selection when they are developing and debugging.

## Installation

Download at [__Chrome WebStore__](https://chrome.google.com/webstore/detail/url-auto-splicer/kmlnjaeipdljbegfnfofknfaeojgojgm)

Alternative: Clone this project, then load ```src``` folder in ```developer mode```.

## Documentation

### Invoke UAS

After installation, UAS will create context menu named with "URL Auto Splicer". You may select any texts displayed on web page, and use right-click to show context menu. All the available rules (/#Rules) will be shown as sub menus of "URL Auto Splicer". It would be invoked if you had clicked a specific item.

### Rules

We have only one rule (Google Search) as an example, which has the same reaction to Chrome "Search Google for".

To add a new rule, you may specify a unique name and its URL Pattern. The URL Pattern should be a standard URL or a URL with `%UAS_PARAM%`.

Only one parameter `%UAS_PARAM%` is available. 

Hint: Protocols (e.g. `https://`) cannot be omitted.

We encourage users to share rules by `Export` `Import` rules.

## Contributing

* If you have a question about using URL Auto Redirector, start a discussion on [Gitter](https://gitter.im/UrlAutoRedirector/UrlAutoRedirector).
* If you think you've found a bug with URL Auto Redirector, [open an issue](https://github.com/crispgm/UrlAutoRedirector/issues/new).
* If you have useful rules in getting convenience by URL Auto Redictor, contribute to [awesome-rules](https://github.com/UrlAutoRedirector/awesome-rules).
* PR(Pull Request) is welcomed.