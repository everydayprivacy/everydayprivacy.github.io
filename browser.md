## Web Browsers

Use [Firefox](https://mozilla.org/firefox/)

Do not use Chrome, Internet Explorer, Microsoft Edge.

Objectives

* Prevent Eavesdropping

* Prevent Tracking

* Prevent Fingerprinting

Use these Firefox settings / add-ons:

* Use "**Enable DNS over HTTPS**"

    This hides your DNS lookups from ISPs and other network providers

    Find this setting in Firefox Edit -> Preferences -> General -> Network Settings

* Use **DuckDuckGo** as the default search engine

    See [search](search.md) for the rationale for doing this

    Find this setting in Firefox Edit -> Preferences -> Search -> Default Search Engine

* Install Firefox add-on [HTTPS Everywhere](https://addons.mozilla.org/en-US/firefox/addon/https-everywhere/)

    This will ensure all communications are encrypted whenever possible

    This is a Firefox add-on.  Go to Firefox -> Tools -> Add-ons, search for "HTTPS Everywhere", select it, and click "Add to Firefox"

* Install Firefox add-on [Privacy Badger](https://addons.mozilla.org/en-US/firefox/addon/privacy-badger17/)

    This will help reduce the tracking of you as you surf the web

    This is a Firefox add-on.  Go to Firefox -> Tools -> Add-ons, search for "Privacy Badger", select it, and click "Add to Firefox"

## Fingerprinting

[Browser Fingerprinting](https://pixelprivacy.com/resources/browser-fingerprinting/) is a serious problem

These sites will tell you how unique you are on the public internet:

* [https://panopticlick.eff.org/](https://panopticlick.eff.org/)

* [https://privacy.net/analyzer/](https://privacy.net/analyzer/)

Consider using these Firefox settings / add-ons:

* Consider setting Firefox setting "**privacy.resistFingerprinting**" to true

    This help hinder fingerprinting

    Type "about:config" in the Firefox address bar, search for "privacy.resistFingerprinting" and change the setting to "true"

* Consider installing Firefox add-on [CanvasBlocker](https://addons.mozilla.org/en-US/firefox/addon/canvasblocker/)

    _Important: Be aware that this add-on has not be reviewed by Mozilla for quality, security, or adherence to policies, so we do not include it as a recommendation.  However, some may assess the tradeoffs as being worth it, and so we raise your awareness of this add-on._

    This helps hinder fingerprinting

    This is a Firefox add-on.  Go to Firefox -> Tools -> Add-ons, search for "CanvasBlocker", select it, and click "Add to Firefox"

* Consider changing Firefox setting "**Allow pages to choose their own fonts**" to UNCHECKED

    This further reduces your uniqueness

    Find this setting in Firefox -> Edit -> Preferences -> General -> Fonts and Colors -> Advanced
