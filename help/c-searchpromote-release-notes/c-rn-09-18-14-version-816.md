---
description: null
seo-description: null
seo-title: Search&amp;Promote 8.16.0 Release Notes (9/18/2014)
solution: Target
title: Search&amp;Promote 8.16.0 Release Notes (9/18/2014)
topic: Release Notes,Site search and merchandising
uuid: 0a59858b-213b-40d6-aea1-d085c4d6d2fa
---

# Search&amp;Promote 8.16.0 Release Notes (9/18/2014){#search-promote-release-notes}

## Search&amp;Promote 8.16.0 Release Notes (9/18/2014) {#topic_5BECD3F66C684987828F6AE65E62DA29}

## New features {#section_2A10EF6B40FC4F2CB2381FFA9FFA64BD}

* Caching of search results in Guided Search 3 (GS3) - To have this custom feature setup for you so that you can use it in your account, contact your Adobe Technical Account Manager. 
* Vertical updates for frequently changed fields - You now have the ability to quickly update all the values for a set of metadata fields without the need to completely reindex your content.

  See the Vertical Update Field option in the table in [Adding a new meta tag field](../c-about-settings-menu/c-about-metadata-menu.md#task_6DF188C0FC7F4831A4444CA9AFA615E5) and [About Vertical Update](../c-about-index-menu/c-about-vertical-updates.md#concept_E65A70C9C2E04804BF24FBE1B3CAD899).

  This feature can only be used on [!DNL Adobe Search&amp;Promote] accounts that use Index Connector. To have this custom feature setup for you so that you can use it in your account, contact your Adobe Technical Account Manager.

## Fixes and enhancements {#section_22D1AFC99F394D569898828A0D3C419D}

* Corrected the Index Connector parsing of XML feeds that contained `?>` string. 
* Fixed Index Connector SFTP feeds when the minimum document count was enforced. 
* Report export to Microsoft Excel now supports UTF8. 
* Guided Search: facets compile was slow. 
* Attribute Loader: aggregate data had duplicate keys. 
* Fixed wrong Business Rule run order when pushing an individual rule live. 
* The wrong facet Undo links were getting generated by Guided Search. 
* New remote control operation added ( `sp_lines=N`) that lets you check the progress and status of a currently running index crawl.

  See [About Remote Control for Indexing](../c-about-index-menu/c-about-remote-control-for-indexing.md#concept_C79B322190E84106A434E5C6D4A4118F). 

* Need to send auth information when fetching deletes information during Index Connector incremental. 
* The [!DNL Change Log] report now identifies the user who initiates a manual index operation.

  See [Viewing the Change Log](../c-about-reports-menu/c-about-reports-menu.md#task_166F1156719F4B3D834BEA8E249C8057). 

* When you export a [!DNL Terms Report], you are no longer limited to 500 or less items in the report.

  See [Viewing the Terms Report or the Null Search Terms Report...](../c-about-reports-menu/c-about-reports-menu.md#task_53B7ED1582DD4B0E8376546A7AFC789A). 

* The Index Connector **[!UICONTROL Strip HTML]** setting was always displaying as checked. 
* Inconsistent search results were experienced with the **[!UICONTROL Common Phrases]** feature. 
* Display of attribute names were getting truncated in the Rule list summaries. 
* Pushing an individual business rule live was pushing all business rules live.

