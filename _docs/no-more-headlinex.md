---
layout: page
title: No More Headline X
inline-title: No More Headline X
permalink: /no-more-headline-x/
---
# no-more-headlinex

No more headlines of X on Chinese news sites, X stands for big brother.

## Introduction

Not long time ago, "global headlines of Big brother" have become "normal" on Chinese news web sites and apps. It means whenever you visit a Chinese news web sites or apps, there are always a set of news about Big Brother.

It's unhappy to see this kind of news always be on headline. We don't care what have he done or what is he doing.

PRs for actions is highly welcomed!

## Actions

To make it disappear for us, I came up with an idea that make a Chrome extension, which is silimar to URLAutoRedictor, but block elements rather than redirections.

### Web

This case is what exactly an AD Blocker is doing. So we may utilize [AdBlock](https://chrome.google.com/webstore/detail/adblock/gighmmpiobklfepjocnamgkkbiglidom) to block it.

AdBlock can block perfectly based on HTML elements. Thus, it cannot be blocked if the headline is just a normal elements of a news feed.

* __ThePaper__: `www.thepaper.cn##DIV[id="cont2206302"][class="pdtt01"]`
* __QQ__: `www.qq.com##DIV[id="newsContent01"][class="newsContent"]`
* __163__: Not available.
* __Toutiao__: Not available.
* __Sina__: `www.sina.com.cn##UL[class="list-a news_top"]`
* __Sohu__: `www.sohu.com##DIV[class="news"]`

### Apps

I don't know the best practice for news apps in this case.

## Conclusion

For news web sites users, AdBlock can be used to cover some of the cases.

And since news are censored, controlled, fragmented, and mostly boring, we may practise minimalism on news.

However, we can *block* or simply not read news, it is just a escape from reality. No one can tell what the hell will finally terminated.

## License

[CC BY-NC-ND](http://creativecommons.org/licenses/by-nc-nd/4.0/)
