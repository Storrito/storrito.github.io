---
layout: post
title: How to get the Instagram sessionid cookie
description: How to get the Instagram sessionid cookie
author: Storrito
twitter:
  username: StorritoFresh
categories: Instagram
tags: Instagram
hidden: true
---

Storrito's new Instagram Connect uses a so-called cookie to log into
your Instagram account. This is required to let Storrito post stories
on your Instagram account.

A cookie has name and contains a text. For the Instagram Connect we
need the `sessionid` cookie. The section below describes how to
extract this cookie. Soon Storrito will offer a Chrome extension and a
Firefox add-on to make this super easy.

## How to get the Instagram sessionid cookie

1. Open Google Chrome, Firefox or Edge

2. Open an incognito window in Google Chrome (in Firefox it is called
private window).

3. Go to https://www.instagram.com/

2. Open Development console by doing a right click on the webpage and
select "Inspect" or "Inspect Element" from the menu.

3. Open a tab with stored page items. That tab called "Storage" in
Firefox, "Application" in Google Chrome and "Debugger" in MS Edge.

4. Click on "Cookies", then on "https://www.instagram.com/"

5. Find a cookie with the name "sessionid". Double click on the value
and copy it.

Google Chrome:

![Google Chrome](/images/instagram-sessionid-cookie/chrome.png "Google Chrome")

Firefox:

![Firefox](/images/instagram-sessionid-cookie/chrome.png "Firefox")

Edge:

![Edge](/images/instagram-sessionid-cookie/edge.png "Edge")


## Connect your Instagram account to Storrito

Please open a new browser tab and open:

[https://app.storrito.com/#/instagram/connect](https://app.storrito.com/#/instagram/connect)

There you paste the copied `sessionid` (see green oval), then click
the `+ ADD NEW INSTAGRAM ACCOUNT` button (see orange oval).

![Storrito](/images/instagram-sessionid-cookie/storrito.png "Storrito")

If you have any problems please contact our Storrito support
(support@storrito.com) or click the red circle in the right bottom
corner.