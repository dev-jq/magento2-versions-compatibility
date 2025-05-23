# [Magento 2.x.x lifecycle](https://magento.com/sites/default/files/magento-software-lifecycle-policy.pdf)

| | Magento Minor Version | Release | End of Quality Fixes| End of Security Fixes/End of Software Support |
|:---|---|---|---|---|
|:no_entry:|2.0 |November 2015|March 2018|March 2018|
|:no_entry:|2.1 |June 2016|June 2019|July 1, 2019|
|:no_entry:|2.2 |September 2017|December 2019|December 2019|
|:no_entry:|2.3 |November 2018|July 2021|April 28, 2022|
|:heavy_check_mark:|**2.4**|July 2020|||

# Release information and [release planning](https://experienceleague.adobe.com/en/docs/commerce-operations/release/planning/schedule)
:arrow_right: Magento [2.4.8](https://experienceleague.adobe.com/en/docs/commerce-operations/release/notes/adobe-commerce/2-4-8)

:arrow_right: Magento [2.4.7](https://experienceleague.adobe.com/en/docs/commerce-operations/release/notes/adobe-commerce/2-4-7)

:arrow_right: Magento [2.4.6](https://experienceleague.adobe.com/en/docs/commerce-operations/release/notes/adobe-commerce/2-4-6)

:arrow_right: Magento [2.4.5](https://experienceleague.adobe.com/en/docs/commerce-operations/release/notes/adobe-commerce/2-4-5)

:arrow_right: Magento [2.4.4](https://experienceleague.adobe.com/en/docs/commerce-operations/release/notes/adobe-commerce/2-4-4)

:arrow_right: Magento [2.4.3](https://experienceleague.adobe.com/en/docs/commerce-operations/release/notes/adobe-commerce/2-4-3)

:arrow_right: Magento [2.4.2](https://experienceleague.adobe.com/en/docs/commerce-operations/release/notes/adobe-commerce/2-4-2)

:arrow_right: Magento [2.4.1](https://experienceleague.adobe.com/en/docs/commerce-operations/release/notes/adobe-commerce/2-4-1)

:arrow_right: Magento [2.4.0](https://experienceleague.adobe.com/en/docs/commerce-operations/release/notes/adobe-commerce/2-4-0)

# [Supported Software](https://experienceleague.adobe.com/docs/commerce-operations/installation-guide/system-requirements.html?lang=en)

## PHP

| Magento Minor Version | PHP 7.1 | PHP 7.2 | PHP 7.3 | PHP 7.4 | PHP 8.0 | PHP 8.1 | PHP 8.2 | PHP 8.3 | PHP 8.4 |
|:---|---|---|---|---|---|---|---|---|---|
|2.3.x|:white_check_mark:<sup>[1]</sup>|:information_source:Until 2.3.6-p1|:heavy_check_mark:2.3.3 - 2.3.6<sup>[2]</sup>|:heavy_check_mark:2.3.7+|:x:|:x:|:x:|:x:|:x:|
|2.4.x|:x:|:x:|:information_source:Until 2.4.1<sup>[2]</sup>|:information_source:Until 2.4.5<sup>[3]</sup>|:information_source:<sup>[3]</sup>|:heavy_check_mark:2.4.4 - 2.4.6|:heavy_check_mark:2.4.6+|:heavy_check_mark:2.4.7+|:heavy_check_mark:2.4.8+|

Notes:
1. Supports ~7.1.3
2. The composer.json in 2.3.7, 2.4.1, and 2.4.2 appears to support 7.3, however the [System Requirements](https://devdocs.magento.com/guides/v2.3/install-gde/system-requirements.html) does not list it as a supported version. This likely means it can work, but you'll be on your own.
3. Adobe has announced they're removing 7.3 in 2.4.4.  This likely means that 2.4.4 will be semi-compatible with 7.4 and 8.0, though it is targeting 8.1.
4. Adobe Commerce 2.4.7 is still compatible with PHP 8.1 for upgrade purposes only. PHP 8.1 is not supported and not recommended.

| Magento Version | PHP 7.1 | PHP 7.2 | PHP 7.3 | PHP 7.4 | PHP 8.0 | PHP 8.1 | PHP 8.2 | PHP 8.3 | PHP 8.4 |
|:---|---|---|---|---|---|---|---|---|---|
|2.2.0| :white_check_mark: | :x: | :x: | :x: | :x: | :x: | :x: | :x: | :x: |
|2.3.0| :white_check_mark: | :white_check_mark: | :x: | :x: | :x: | :x: | :x: | :x: | :x: |
|2.4.0| :x: | :x: | :white_check_mark: | :white_check_mark: | :x: | :x: | :x: | :x: | :x: |
|2.4.1| :x: | :x: | :white_check_mark: | :white_check_mark: | :x: | :x: | :x: | :x: | :x: |
|2.4.2| :x: | :x: | :white_check_mark: | :white_check_mark: | :x: | :x: | :x: | :x: | :x: |
|2.4.3| :x: | :x: | :white_check_mark: | :white_check_mark: | :x: | :x: | :x: | :x: | :x: |
|2.4.4| :x: | :x: | :x: | :information_source:<sup>[3]</sup> | :information_source:<sup>[3]</sup> | :white_check_mark: | :x: | :x: | :x: |
|2.4.5| :x: | :x: | :x: | :information_source:<sup>[3]</sup> | :information_source:<sup>[3]</sup> | :white_check_mark: | :x: | :x: | :x: |
|2.4.6| :x: | :x: | :x: | :x: | :x: | :white_check_mark: | :white_check_mark: | :x: | :x: |
|2.4.7| :x: | :x: | :x: | :x: | :x: | :information_source:<sup>[4]</sup> | :white_check_mark: | :white_check_mark: | :x: |
|2.4.8| :x: | :x: | :x: | :x: | :x: | :x:| :white_check_mark: | :white_check_mark: | :white_check_mark: |

## Composer
| Magento Minor Version | Composer 1 | Composer 2 |
|:---|---|---|
|2.3| :information_source: Until 2.3.7<sup>[1]</sup>| :heavy_check_mark: 2.3.7+|
|2.4| :information_source: Until 2.4.2<sup>[1]</sup>| :heavy_check_mark: 2.4.2+|

Notes:
1. Composer 1 still works with Magento 2.3.7 and 2.4.2, but is no longer supported.

## Elasticsearch

| Magento Minor Version | ES 5.x | ES 6.x | ES 7.4.x | ES 7.6.x | ES 7.9.x | ES 7.10.x | ES 8.x |
|:---|---|---|---|---|---|---|---|
|2.3|:information_source: Until 2.3.5|:white_check_mark:|:heavy_check_mark:: 2.3.5+|:x:|:heavy_check_mark: 2.3.7+|:x:|:x:|
|2.4|:x:|:x:|:heavy_check_mark: 2.4.2+<sup>[2]</sup>|:heavy_check_mark: 2.4.0-2.4.1<sup>[1]</sup>| :heavy_check_mark: 2.4.2 - 2.4.3| :heavy_check_mark:2.4.4 - 2.4.5|:heavy_check_mark:2.4.6 - 2.4.7|

Notes:
1. 2.4.0 specifically declares support for ES 7.6.x
2. 2.4.2 states "Magento 2.4.x remains compatible with Elasticsearch 7.4.x" despite compatibility not being declared at any point
3. 2.4.8 "The Elasticsearch 7 and Elasticsearch 8 options are now labeled as "(Deprecated)". We recommend using OpenSearch as a search engine instead."

## Opensearch

| Magento Minor Version | OS 1.x | OS 2.x |
|:---|---|---|
|2.3|:x:|:x:|
|2.4|:heavy_check_mark:2.4.4+|:heavy_check_mark:2.4.7+|

Notes:
1. 2.4.8 is now optimized for OpenSearch 2.19 and is no longer compatible with Elasticsearch.

## Databases

### MySQL

| Magento Minor Version | MySQL 5.6 | MySQL 5.7 | MySQL 8.0 |
|:---|---|---|---|
|2.3|:white_check_mark:<sup>[1]</sup>|:white_check_mark:|:x:|
|2.4|:x:|:white_check_mark:<sup>[1]</sup>|:white_check_mark:|

Notes:
1. Magento is also compatible with, but has not been tested and is not recommended

### MariaDB

| Magento Minor Version | MariaDB 10.0 | MariaDB 10.1 | MariaDB 10.2 | MariaDB 10.3 | MariaDB 10.4 | MariaDB 10.5 | MariaDB 10.6 | MariaDB 11.4 
|:---|---|---|---|---|---|---|---|---|
|2.3|:white_check_mark:<sup>[1]</sup>|:white_check_mark:<sup>[1]</sup>|:white_check_mark:<sup>[1]</sup>|:white_check_mark:<sup>[1]</sup>|:white_check_mark:<sup>[1]</sup>|:x:|:x:|:x:|
|2.4|:x:|:x:|:white_check_mark:<sup>[2]</sup>|:white_check_mark:<sup>[2]</sup>|:white_check_mark:<sup>[2]</sup>|:white_check_mark:|:heavy_check_mark:2.4.6+|:heavy_check_mark:2.4.8+|

Notes:
1. Magento only uses MySQL features compatible with MariaDB. MariaDB may not be compatible with all MySQL features, however, so be sure to research compatibility issues before using a feature in your Magento module.
2. Magento is also compatible, but has not been tested and is not recommended

## Redis

| Magento Minor Version | Redis 4.x | Redis 5.x | Redis 6.2 | Redis 7.2 |
|:---|---|---|---|---|
|2.3|:heavy_check_mark:2.3.1 - 2.3.5|:heavy_check_mark:2.3.1 - 2.3.6|:heavy_check_mark:2.3.7+|:x:|
|2.4|:x:|:heavy_check_mark:2.4.0 - 2.4.1|:heavy_check_mark:2.4.2 - 2.4.6|:heavy_check_mark:2.4.7+|

## Varnish

| Magento Minor Version | Varnish 4.x | Varnish 5.x | Varnish 6.x | Varnish 7.x |
|:---|---|---|---|---|
|2.3|:white_check_mark:|:white_check_mark:<sup>[1]</sup>|:white_check_mark:<sup>[2]</sup>|:x:|
|2.4|:x:|:x:|:white_check_mark:<sup>[3]</sup>|:heavy_check_mark:2.4.4+|

Notes:
1. Magento declares support for 5.2+
2. Magento declares support for 6.2+, 6.5.1 explicitly supported with 2.3.7
3. Tested with 6.3.1. Magento 2.4.2 tested with 6.4
