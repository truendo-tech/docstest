---
# snazzyDocs - DO NOT REMOVE OR EDIT BELOW THIS LINE
title: Scripts
id: IAX-IEU-9UP-WCT
slug: scripts
isVisible: true
lastUpdated: '2023-02-14 07:20:00'
---
# Scripts

## <span style="color:rgb(0, 0, 0);"><span style="background-color:rgb(255, 255, 255);">How to Block Cookies</span></span>

<span style="color:rgb(0, 0, 0);"><span style="background-color:rgb(255, 255, 255);">You will have to add two attributes to every script in your website that needs to be controlled by TRUENDO.</span></span>

The first attribute `truendo` is set to `"true"`, thus ensuring that it is not autoblocked by TRUENDO.

<span style="color:rgb(0, 0, 0);"><span style="background-color:rgb(255, 255, 255);">Second we set the </span></span>`type` attribute to `"text/plain"`. This way the script is not running before the user accepts it.

<span style="color:rgb(0, 0, 0);"><span style="background-color:rgb(255, 255, 255);">The third attribute is </span></span>`data-trucookiecontrol`. This attribute has to be set to the corresponding category. For example `"statistics"`. When both are in the script it could look something like this:

```html
<script truendo="true" data-trucookiecontrol="statistics" src="[...]" type="text/plain"></script>

```

[click here](http:#?target=0EB-94M4-TBP-GIU) for a list of technical category names.

> <div class="sd-callout" data-callout-type="info">**Important Note:** Scripts that fall under the necessary category should not be changed as these can run without consent.</div>