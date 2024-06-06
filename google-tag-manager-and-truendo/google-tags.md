---
# snazzyDocs - DO NOT REMOVE OR EDIT BELOW THIS LINE
title: 'Google Tags'
id: JRI-GCBU-8GF-ZHS
slug: google-tags
isVisible: true
lastUpdated: '2024-05-23 09:53:37'
---
# Google Tags

<span style="color:rgba(10,10,10,1);">Google Consent Mode v2 enables granular management of Google service-based tags such as Google Analytics and Google Ads, incorporating built-in consent checks to meet GDPR requirements.</span>

<br />

## <span style="color:rgba(10,10,10,1);">Conditional Data Collection (Recommended by Google):</span>

-   <span style="color:rgba(10,10,10,1);">Set 'Additional consent checks' to 'Not set'. In this configuration, the Google tag will fire on all page visits regardless of consent status. Data collection, however, is controlled based on the user’s specific consents for 'Statistics' and 'Marketing' categories:</span>
-   <span style="color:rgba(10,10,10,1);">Verification:</span>

<span style="color:rgba(10,10,10,1);">On the webpage where the tags are implemented, press F12 to open Developer Tools, then go to the 'Network' tab. Reload the page (F5) and search for a 'Collect' request with your tag ID.</span>

<figure><img src="https://app.snazzydocs.com/storage/users/hEfI2V55cVTdM5ty/docs/G2IomO8914MUXZZJ/images/FdRxLu2uMXUtNwr4NWPt.png"></figure>

-   <span style="color:rgba(10,10,10,1);">Click on the request and Examine the Request URL looking for the gcs parameter</span>

<figure><img src="https://app.snazzydocs.com/storage/users/hEfI2V55cVTdM5ty/docs/G2IomO8914MUXZZJ/images/ul0XQPou0ifTmKNCbj8z.png"></figure>

-   <span style="color:rgba(10,10,10,1);">Examine the 'gcs' parameter:</span>

<span style="color:rgba(10,10,10,1);">- </span> `gcs=G100`: Both analytics\_storage and ad\_storage are denied.

<span style="color:rgba(10,10,10,1);">- </span> `gcs=G110`: Analytics\_storage is denied, ad\_storage is granted.

<span style="color:rgba(10,10,10,1);">- </span> `gcs=G101`: Analytics\_storage is granted, ad\_storage is denied.

<span style="color:rgba(10,10,10,1);">- </span> `gcs=G111`: Both analytics\_storage and ad\_storage are granted.

<span style="color:rgba(10,10,10,1);">- </span> `gcs=G1--`: Consent for ad\_storage or analytics\_storage was not required by the site.<br />
<br />
To summarise the above method will result in the **<span style="color:rgba(10,10,10,1);">Google tag firing but no data will be collected unless the respective category is consented to</span>**<span style="color:rgba(10,10,10,1);">.</span>

<br />

### <span style="color:rgba(10,10,10,1);">Consent-Dependent Tag Firing</span>

<div class="sd-callout" data-callout-type="info">Do this when you <strong>do not want the Google tags to fire at all until consent is given</strong>.</div>

-   <span style="color:rgba(10,10,10,1);">Modify 'Additional consent checks' to 'Require additional consent for tag to fire', selecting 'analytics_storage' and/or 'ad_storage' as needed. This configuration ensures the tag fires only with explicit user consent.</span>

<br />