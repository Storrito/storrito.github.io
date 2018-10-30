---
layout: post
title: How to get the Instagram sessionid cookie
image: /images/manualconnect.jpg
description: How to get the Instagram sessionid cookie
author: Storrito
twitter:
  username: StorritoFresh
categories: Instagram
tags: Instagram stories schedule creator online storitto storrito pc computer desktop mac resolution
---

![How to post](/images/manualconnect.jpg "Storrito Instagram Story Aspect Ratio")

Storrito's Manual Instagram Connect uses a so-called cookie to log
into your Instagram account. This is required to let Storrito post
stories on your Instagram account.

<!--more-->
We recommend to use our [Chrome
extension](https://chrome.google.com/webstore/detail/plnpnichbepfpgbhineljllbhdpglkpn)
or [Firefox
Add-On](https://addons.mozilla.org/de/firefox/addon/storrito/) to do
the Instagram Connect for your Storrito account. If you still want to
do it manually, please find the instructions below.

A cookie has name and contains a text. For the Instagram Connect we
need the `sessionid` cookie. The section below describes how to
extract this cookie.

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

If you have not opened Storrito's Instagram Connect page, please open
it:

<a href="https://app.storrito.com/#/instagram/connect" target="_blank">https://app.storrito.com/#/instagram/connect</a>

Then choose the 'Manual' connect option (see orange oval):

![Instagram-connect](/images/instagram-sessionid-cookie/instagram-connect.png "Instagram Connect")

On the next page (shown below) you paste the copied `sessionid` (see
orange oval), then click on the `CONNECT` button (see green oval).

![Manual-Instagram-connect](/images/instagram-sessionid-cookie/manual-instagram-connect.png "Manual Instagram Connect")

Afterwards the new connected Instagram account will appear in the
'Your connected Instagram accounts' list. You can now close the
incoginto tab, please do not click on logout there, since this would
disconnect Storrito from Instagram.

If you have any problems please contact our Storrito support
(support@storrito.com) or click the red circle in the right bottom
corner.
