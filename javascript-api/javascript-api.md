---
# snazzyDocs - DO NOT REMOVE OR EDIT BELOW THIS LINE
title: 'Javascript API'
id: 4O6-WKD8-FTV-1H0
slug: javascript-api
isVisible: true
lastUpdated: '2023-09-22 10:36:22'
---
# <span style="color:rgb(0, 0, 0);"><span style="background-color:rgb(255, 255, 255);">Javascript API</span></span>

<span style="color:rgb(0, 0, 0);"><span style="background-color:rgb(255, 255, 255);">With TRUENDO you can create custom buttons to open the Privacy Widget at certain pages.</span></span>

## <span style="color:rgb(0, 0, 0);"><span style="background-color:rgb(255, 255, 255);">Opening tabs with a link</span></span>

<span style="color:rgb(0, 0, 0);"><span style="background-color:rgb(255, 255, 255);">Use the following code to:</span></span>

**<span style="color:rgb(0, 0, 0);"><span style="background-color:rgb(255, 255, 255);">Open Privacy Widget</span></span>**

`&lt;a href="javascript:Truendo.openPrivacyPanel()"&gt;Privacy Center&lt;/a&gt;`

**<span style="color:rgb(0, 0, 0);"><span style="background-color:rgb(255, 255, 255);">Open the Privacy tab</span></span>**

`&lt;a href="javascript:Truendo.openYourRights()"&gt;Privacy Policy&lt;/a&gt;`

**<span style="color:rgb(0, 0, 0);"><span style="background-color:rgb(255, 255, 255);">Open the Cookies tab</span></span>**

`&lt;a href="javascript:Truendo.openCookieSettings()"&gt;Cookie Manager&lt;/a&gt;`

<br />

## <span style="color:rgb(0, 0, 0);"><span style="background-color:rgb(255, 255, 255);">Toggle Categories</span></span>

<span style="color:rgb(0, 0, 0);"><span style="background-color:rgb(255, 255, 255);">Toggle the service categories with these functions:</span></span>

**<span style="color:rgb(0, 0, 0);"><span style="background-color:rgb(255, 255, 255);">Social Content</span></span>**

`&lt;a href="javascript:window.Truendo.toggleContent();"&gt;Toggle Social Content&lt;/a&gt;`

**<span style="color:rgb(0, 0, 0);"><span style="background-color:rgb(255, 255, 255);">Marketing</span></span>**

`&lt;a href="javascript:window.Truendo.toggleMarketing();"&gt;Toggle Marketing&lt;/a&gt;`

**<span style="color:rgb(0, 0, 0);"><span style="background-color:rgb(255, 255, 255);">Statistics</span></span>**

`&lt;a href="javascript:window.Truendo.toggleStatistics();"&gt;Toggle Statistics&lt;/a&gt;`

**Additional Features**

`&lt;a href="javascript:window.Truendo.addFeatures();"&gt;Toggle Additional Features&lt;/a&gt;`

**<span style="color:rgb(0, 0, 0);"><span style="background-color:rgb(255, 255, 255);">Preferences</span></span>**

`&lt;a href="javascript:window.Truendo.togglePreferences();"&gt;Toggle Preferences&lt;/a&gt;`

<br />

## Other API calls

**Unblocking**

This call reruns the CMP unblocking functionality based on the user's current consent choices.

```
window.Truendo.runUnblockService()
```

<br />