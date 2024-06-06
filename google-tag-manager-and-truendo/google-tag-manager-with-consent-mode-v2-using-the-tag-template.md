---
# snazzyDocs - DO NOT REMOVE OR EDIT BELOW THIS LINE
title: 'Google Tag Manager with consent mode v2 using the tag template'
id: RRK-AEO3-EIM-GWV
slug: google-tag-manager-with-consent-mode-v2-using-the-tag-template
isVisible: true
lastUpdated: '2024-05-27 07:15:58'
---
# How to Set up Google Tag Manager with Consent Mode v2

TRUENDO now offers a GTM Tag Template to make setting up TRUENDO in GTM easier than ever.

<div class="sd-callout" data-callout-type="tip">This is the recommended method for implementing TRUENDO in GTM</div>

<div class="sd-callout" data-callout-type="alert">Before proceeding please <strong>remove/deactivate any existing scripts/plugins you may have previously used to integrate TRUENDO</strong> on your website. Google Tag manager will do it automatically once the procedure below is completed.</div>

### <span style="color:rgb(0, 0, 0);">Step 1</span>

<span style="color:rgb(14, 16, 26);">In Google Tag manager (GTM) enable Google's Consent Mode by navigating to the 'Admin' tab, selecting the 'Container Settings' option, and ticking the </span> **<span style="color:rgb(14, 16, 26);">Enable consent overview (BETA)</span>** <span style="color:rgb(14, 16, 26);">checkbox under 'Additional Settings', click </span> **<span style="color:rgb(14, 16, 26);">Save</span>**<span style="color:rgb(14, 16, 26);">.</span>

<figure><img src="https://app.snazzydocs.com/storage/users/hEfI2V55cVTdM5ty/docs/G2IomO8914MUXZZJ/images/u3gDUAeOq6mkPLlWA4XF.png"></figure>

### Step 2

Download the TRUENDO Tag Template for GTM **[here](https://truendo-file-hosting.s3.eu-central-1.amazonaws.com/TRUENDO+Cookie+Consent+Management+v1.tpl).**

<br />

### Step 3

In GTM navigate to the workspace tab of the container to which you wish to add TRUENDO, then click 'Templates' from the panel on the left

<figure><img src="https://app.snazzydocs.com/storage/users/hEfI2V55cVTdM5ty/docs/G2IomO8914MUXZZJ/images/s12ysxhACCssfNPaH3LL.png"></figure>

### Step 4

Click the Menu (three vertical dots) button in the top right of the 'Template Editor' screen and then click 'Import', then add the TRUENDO Tag template you just downloaded.

<figure><img src="https://app.snazzydocs.com/storage/users/hEfI2V55cVTdM5ty/docs/G2IomO8914MUXZZJ/images/M7E0dja5Q6orScd3bakn.png"></figure>

### Step 5

Click The blue 'Save' button and close the 'Template Editor' screen (cross on the top left).

<figure><img src="https://app.snazzydocs.com/storage/users/hEfI2V55cVTdM5ty/docs/G2IomO8914MUXZZJ/images/Vp2nOZYv6LEwOiXyFcNF.png"></figure>

<br />

### Step 6

Click 'Tags' in the panel on the left. Then click the 'New' button in the top right of the 'Tags' screen.

<img src="https://app.snazzydocs.com/storage/users/hEfI2V55cVTdM5ty/docs/G2IomO8914MUXZZJ/images/qVnqzgXBNuQ883mug005.png">

<br />

### Step 7

An 'Untitled Tag' screen will appear containing the 'Tag Configuration' and 'Triggering' panes. Rename this tag to TRUENDO, this is not necessary but recommended to help you keep track.

<figure><img src="https://app.snazzydocs.com/storage/users/hEfI2V55cVTdM5ty/docs/G2IomO8914MUXZZJ/images/hHSVTL3zbSagKwgy4J1Y.png"></figure>

### Step 8

Click the Edit (pencil) button that appears when you hover in the top right of the 'Tag Configuration' pane. Scroll down to Custom and select the TRUENDO tag you just added.

<figure><img src="https://app.snazzydocs.com/storage/users/hEfI2V55cVTdM5ty/docs/G2IomO8914MUXZZJ/images/pXfcO7UcGnFmZDHKNH42.png"></figure>

### Step 9

Tick the checkbox titled 'Inject TRUENDO via GTM'. Check any additional check boxes based on your preferences. Leave the Tag editor pane open and proceed to the next step. Do not close or save this yet.

<figure><img src="https://app.snazzydocs.com/storage/users/hEfI2V55cVTdM5ty/docs/G2IomO8914MUXZZJ/images/0ZeJhBTgSGeW513ePu0c.png"></figure>

### Step 10

<span style="color:rgb(0, 0, 0);"><span style="background-color:rgb(255, 255, 255);">Now you need to add your Site ID to the TRUENDO tag. In a separate browser window to GTM:</span></span>

1.  <span style="color:rgb(0, 0, 0);"><span style="background-color:rgb(255, 255, 255);">Log in to the TRUENDO </span></span> [<span style="color:rgb(0, 85, 187);"><span style="background-color:transparent;">Console</span></span>](https://console.truendo.com/), (select the correct Organization and website if you have more than one) then click **Banner** in the panel on the left of the screen, now scroll until you see **Integration via script**.
2.  <span style="color:rgb(0, 0, 0);"><span style="background-color:rgb(255, 255, 255);">Click </span></span> **<span style="color:rgb(0, 0, 0);"><span style="background-color:rgb(255, 255, 255);">Copy Site ID</span></span>**<span style="color:rgb(0, 0, 0);"><span style="background-color:rgb(255, 255, 255);">.</span></span>
3.  <span style="color:rgb(0, 0, 0);"><span style="background-color:rgb(255, 255, 255);">Back in Google Tag Manager in the already opened Tag Editor paste the Site ID in the field provided</span></span>

### Step 11

Click the Edit button in the Triggering pane, then select 'Consent Initialization - All Pages' in the screen that appears.

<figure><img src="https://app.snazzydocs.com/storage/users/hEfI2V55cVTdM5ty/docs/G2IomO8914MUXZZJ/images/PuNnCAmBIF5Yt4e1SMzL.png"></figure>

### Step 12

Click Save, Congratualtions you have succesfully setup TRUENDO in Google Tag Manager.

<figure><img src="https://app.snazzydocs.com/storage/users/hEfI2V55cVTdM5ty/docs/G2IomO8914MUXZZJ/images/8lhPkX3Z8GNXrasuZg6x.png"></figure>

<br />