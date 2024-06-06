---
# snazzyDocs - DO NOT REMOVE OR EDIT BELOW THIS LINE
title: 'Banner Customization'
id: D5O-DVIV-TQQ-IKA
slug: banner-customization
isVisible: true
lastUpdated: '2023-09-22 11:37:56'
---
# Styling Your Cookie Banner

All styling options are located in the main navigation menu in the **Banner** section. You must be both logged in to TRUENDO and have selected the website which you wish to customize.

## Banner Color

Both Essentials and Premium users may change the color of the banner by using the color picker or by entering a specific HEX color code.

<br />

<figure><img src="https://app.snazzydocs.com/storage/users/hEfI2V55cVTdM5ty/docs/G2IomO8914MUXZZJ/images/h3ZLQbVyL4MiCNHp6lpJ.png"></figure>

<br />

## Displaying the Privacy Widget

Users may also toggle whether to display the Privacy Widget on their pages or not.

<figure><img src="https://app.snazzydocs.com/storage/users/hEfI2V55cVTdM5ty/docs/G2IomO8914MUXZZJ/images/PzusuuQHSzqBBbzEElcO.png"></figure>

<br />

<div class="sd-callout" data-callout-type="alert">The following customization options are <strong>only</strong> available to <strong>Premium</strong> users</div>

<br />

## Banner design

Premium users may select from 6 banner designs. Essentials users may only use the Standard Banner design. To preview our banner styles please click [here](https://demo.truendo.com). Premium users can also set up their own [custom design](http:#?target=FGQ-IBXJ-AFE-PC0).

<figure><img src="https://app.snazzydocs.com/storage/users/hEfI2V55cVTdM5ty/docs/G2IomO8914MUXZZJ/images/gPP8VszgGnYbyh4aCeMl.png"></figure>

<figure><img src="https://app.snazzydocs.com/storage/users/hEfI2V55cVTdM5ty/docs/G2IomO8914MUXZZJ/images/FCbMvtad44xKdV2DYz68.png"></figure>

<br />

## Banner Display Time Delay

Some users may wish to delay the display of the consent request banner to website visitors. This may be useful if a website has loading animations or other visual features that require a lead-in/play time. This feature is implemented by means of adding an attribute to the TRUENDO script.

To add a delay to the TRUENDO banner popup’s appearance, simply add the following attribute to your TRUENDO script:

`data-popup-delay=“5”`

In this example, the banner appearance will be delayed by 5 seconds, but you can set it from 0 to 10 seconds.

<br />

<div class="sd-callout" data-callout-type="info">It is advisable that this delay is kept as short as possible i.e. just long enough for the animation/visual queue requires to conclude.</div>

<br />

The final script will look like this:<br />
<br />
`&lt;!-- TRUENDO Privacy Center --&gt;&lt;script data-popup-delay=“5” id="truendoPrivacyPanel" type="text/javascript" src="https://cdn.priv.center/pc/app.pid.js" data-siteid="YOUR_SITE_ID"&gt;&lt;/script&gt;&lt;!-- End TRUENDO Privacy Center --&gt;`

<br />

## Removing the TRUENDO logo

Premium users can also choose whether to display the TRUENDO logo on their banner or not.

<figure><img src="https://app.snazzydocs.com/storage/users/hEfI2V55cVTdM5ty/docs/G2IomO8914MUXZZJ/images/PZJw3k5WpkD620u8raQh.png"></figure>

<br />