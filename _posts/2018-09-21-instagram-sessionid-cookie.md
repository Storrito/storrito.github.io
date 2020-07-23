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
stories on your behalf.

<!--more-->

## Get the session ID with a browser extension

### Google Chrome - Cookie Tab Viewer:

1. Install the extension [Cookie Tab Viewer](https://chrome.google.com/webstore/detail/cookie-tab-viewer/fdlghnedhhdgjjfgdpgpaaiddipafhgk) and allow the extension to work in incognito:
    1. Right click on the extension icon
    2. Click on "Manage Extensions"
    3. Activate the “Allow in Incognito” check box.

2. **Open an incognito window in Google Chrome. This is an important step!**

3. Go to [https://www.instagram.com/](https://www.instagram.com/) and log into your Instagram account

4. Click on the extension icon:
  ![cookie tab viewer 1](/images/instagram-sessionid-cookie/cookie-tab-viewer-1.png)

5. Copy the sessionid cookie by clicking on the copy button:  
  ![cookie tab viewer 2](/images/instagram-sessionid-cookie/cookie-tab-viewer-2.png)

6. Please paste the `session-id` into the proper input field on Storrito (see [Connect your Instagram account to Storrito](#connect-your-ig-account))

### Firefox - Cookie Quick Manager:

1. Install the addon [Cookie Quick Manager](https://addons.mozilla.org/de/firefox/addon/cookie-quick-manager/) and allow it to run in Private Windows:
   ![cookie quick manager](/images/instagram-sessionid-cookie/cookie-quick-manager.png)

2. Open a private firefox window

3. Go to [https://www.instagram.com/](https://www.instagram.com/) and log into your Instagram account

4. Click on the browser addon icon and select:
  ![cookie quick manager](/images/instagram-sessionid-cookie/cookie-quick-manager-2.png)

5. From left to right: Select the **.instagram.com** domain, Click on the first cookie called **sessionid**, Copy the cookie from the marked textbox:
  ![cookie quick manager](/images/instagram-sessionid-cookie/cookie-quick-manager-3.png)

6. Please paste the `session-id` into the proper input field on Storrito (see [Connect your Instagram account to Storrito](#connect-your-ig-account))


## How to get the Instagram sessionid cookie manually (Google Chrome, Firefox, Edge)

1. Open your browser

2. **Open an incognito window in Google Chrome (in Firefox it is called private window). This is an important step!**

3. Go to https://www.instagram.com/ and log into your Instagram account

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

## <a id="connect-your-ig-account"></a> Connect your Instagram account to Storrito

If you have not opened Storrito's Instagram Connect page yet, please open
it:

<a href="https://app.storrito.com/#/instagram/connect" target="_blank">https://app.storrito.com/#/instagram/connect</a>

Then click on `CONNECT AN INSTAGRAM ACCOUNT`  
![Instagram-connect step 1](/images/instagram-sessionid-cookie/instagram-connect-1.png "Instagram Connect step 1")

Choose `USE AN ALTERNATIVE METHOD`  
![Instagram-connect step 2](/images/instagram-sessionid-cookie/instagram-connect-2.png "Instagram Connect step 2")

On the next page (shown below) you need paste the `sessionid` (see
green rectangle) and then click on the `CONNECT` button (see green arrow).
**Please see the tutorials further up to get the `sessionid` for your Instagram account.**

![Manual-Instagram-connect](/images/instagram-sessionid-cookie/manual-instagram-connect.png "Manual Instagram Connect")

Afterwards the new connected Instagram account will appear in the
'Your connected Instagram accounts' list. You can now close the
incoginto tab, please do not click on logout there, since this would
disconnect Storrito from Instagram.

If you have any problems please contact our Storrito support
(support@storrito.com) or click the red circle in the right bottom
corner.