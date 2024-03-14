# [Magento 2.x.x lifecycle](https://magento.com/sites/default/files/magento-software-lifecycle-policy.pdf)

| Magento Minor Version | Release | End of Quality Fixes| End of Security Fixes/End of Software Support |
|:---|---|---|---|
|2.0 :no_entry: |November 2015|March 2018|March 2018|
|2.1 :no_entry: |June 2016|June 2019|July 1, 2019|
|2.2 :no_entry: |September 2017|December 2019|December 2019|
|2.3 :no_entry: |November 2018|July 2021|April 28, 2022|
|**2.4**|July 2020|||

# Release information
:arrow_right: Magento [2.4.7-beta](https://experienceleague.adobe.com/en/docs/commerce-operations/release/notes/adobe-commerce/2-4-7)

:arrow_right: Magento [2.4.6](https://experienceleague.adobe.com/en/docs/commerce-operations/release/notes/adobe-commerce/2-4-6)

:arrow_right: Magento [2.4.5](https://experienceleague.adobe.com/en/docs/commerce-operations/release/notes/adobe-commerce/2-4-5)

:arrow_right: Magento [2.4.4](https://experienceleague.adobe.com/en/docs/commerce-operations/release/notes/adobe-commerce/2-4-4)

:arrow_right: Magento [2.4.3](https://experienceleague.adobe.com/en/docs/commerce-operations/release/notes/adobe-commerce/2-4-3)

:arrow_right: Magento [2.4.2](https://experienceleague.adobe.com/en/docs/commerce-operations/release/notes/adobe-commerce/2-4-2)

:arrow_right: Magento [2.4.1](https://experienceleague.adobe.com/en/docs/commerce-operations/release/notes/adobe-commerce/2-4-1)

:arrow_right: Magento [2.4.0](https://experienceleague.adobe.com/en/docs/commerce-operations/release/notes/adobe-commerce/2-4-0)

# [Supported Software](https://experienceleague.adobe.com/docs/commerce-operations/installation-guide/system-requirements.html?lang=en)

## PHP

| Magento Minor Version | PHP 7.1 | PHP 7.2 | PHP 7.3 | PHP 7.4 | PHP 8.0 | PHP 8.1 | PHP 8.2 | PHP 8.3 |
|:---|---|---|---|---|---|---|---|---|
|2.3.x|:white_check_mark:<sup>[1]</sup>|Until 2.3.6-p1|2.3.3 - 2.3.6<sup>[2]</sup>|2.3.7+|:x:|:x:|:x:|:x:|
|2.4.x|:x:|:x:|Until 2.4.1<sup>[2]</sup>|Until 2.4.5<sup>[3]</sup>|:x:<sup>[3]</sup>|2.4.4+|2.4.6+|2.4.7-beta3+|

Notes:
1. Supports ~7.1.3
2. The composer.json in 2.3.7, 2.4.1, and 2.4.2 appears to support 7.3, however the [System Requirements](https://devdocs.magento.com/guides/v2.3/install-gde/system-requirements.html) does not list it as a supported version. This likely means it can work, but you'll be on your own.
3. Adobe has announced they're removing 7.3 in 2.4.4.  This likely means that 2.4.4 will be semi-compatible with 7.4 and 8.0, though it is targeting 8.1.

| Magento Version | PHP 7.1 | PHP 7.2 | PHP 7.3 | PHP 7.4 | PHP 8.0 | PHP 8.1 | PHP 8.2 | PHP 8.3 |
|:---|---|---|---|---|---|---|---|---|
|2.4.4| :x: | :x: | :x: | :information_source:<sup>[3]</sup> | :information_source:<sup>[3]</sup> | :white_check_mark: | :x: | :x: |
|2.4.4-p1| :x: | :x: | :x: | :information_source:<sup>[3]</sup> | :information_source:<sup>[3]</sup> | :white_check_mark: | :x: | :x: |
|2.4.4-p2| :x: | :x: | :x: | :information_source:<sup>[3]</sup> | :information_source:<sup>[3]</sup> | :white_check_mark: | :x: | :x: |
|2.4.4-p3| :x: | :x: | :x: | :information_source:<sup>[3]</sup> | :information_source:<sup>[3]</sup> | :white_check_mark: | :x: | :x: |
|2.4.4-p4| :x: | :x: | :x: | :information_source:<sup>[3]</sup> | :information_source:<sup>[3]</sup> | :white_check_mark: | :x: | :x: |
|2.4.4-p5| :x: | :x: | :x: | :information_source:<sup>[3]</sup> | :information_source:<sup>[3]</sup> | :white_check_mark: | :x: | :x: |
|2.4.4-p6| :x: | :x: | :x: | :information_source:<sup>[3]</sup> | :information_source:<sup>[3]</sup> | :white_check_mark: | :x: | :x: |
|2.4.4-p7| :x: | :x: | :x: | :information_source:<sup>[3]</sup> | :information_source:<sup>[3]</sup> | :white_check_mark: | :x: | :x: |
|2.4.5| :x: | :x: | :x: | :x: | :x: | :white_check_mark: | :x: | :x: |
|2.4.5-p1| :x: | :x: | :x: | :x: | :x: | :white_check_mark: | :x: | :x: |
|2.4.5-p2| :x: | :x: | :x: | :x: | :x: | :white_check_mark: | :x: | :x: |
|2.4.5-p3| :x: | :x: | :x: | :x: | :x: | :white_check_mark: | :x: | :x: |
|2.4.5-p4| :x: | :x: | :x: | :x: | :x: | :white_check_mark: | :x: | :x: |
|2.4.5-p5| :x: | :x: | :x: | :x: | :x: | :white_check_mark: | :x: | :x: |
|2.4.5-p6| :x: | :x: | :x: | :x: | :x: | :white_check_mark: | :x: | :x: |
|2.4.6| :x: | :x: | :x: | :x: | :x: | :white_check_mark: | :white_check_mark: | :x: |
|2.4.6-p1| :x: | :x: | :x: | :x: | :x: | :white_check_mark: | :white_check_mark: | :x: |
|2.4.6-p2| :x: | :x: | :x: | :x: | :x: | :white_check_mark: | :white_check_mark: | :x: |
|2.4.6-p3| :x: | :x: | :x: | :x: | :x: | :white_check_mark: | :white_check_mark: | :x: |
|2.4.6-p4| :x: | :x: | :x: | :x: | :x: | :white_check_mark: | :white_check_mark: | :x: |
|2.4.7-beta2| :x: | :x: | :x: | :x: | :x: | :white_check_mark: | :white_check_mark: | :x: |
|2.4.7-beta3| :x: | :x: | :x: | :x: | :x: | :grey_question: | :white_check_mark: | :white_check_mark: |

## Composer
| Magento Minor Version | Composer 1 | Composer 2 |
|:---|---|---|
|2.0| :white_check_mark: | :x: |
|2.1| :white_check_mark: | :x: |
|2.2| :white_check_mark: | :x: |
|2.3| :information_source: Until 2.3.7<sup>[1]</sup>| :white_check_mark: 2.3.7+|
|2.4| :information_source: Until 2.4.2<sup>[1]</sup>| :white_check_mark: 2.4.2+|

Notes:
1. Composer 1 still works with Magento 2.3.7 and 2.4.2, but is no longer supported.

## Elasticsearch

| Magento Minor Version | ES 5.x | ES 6.x | ES 7.4.x | ES 7.6.x | ES 7.9.x | ES 7.10.x |
|:---|---|---|---|---|---|---|
|2.3|:information_source: Until 2.3.5|:white_check_mark:|:white_check_mark: 2.3.5+|:x:|:white_check_mark: 2.3.7+|:x:|
|2.4|:x:|:x:|:white_check_mark: 2.4.2+<sup>2</sup>|:white_check_mark: 2.4.0-2.4.1<sup>1</sup>| :white_check_mark: 2.4.2+| :white_check_mark:2 .4.4+

Notes:
1. 2.4.0 specifically declares support for ES 7.6.x
2. 2.4.2 states "Magento 2.4.x remains compatible with Elasticsearch 7.4.x" despite compatibility not being declared at any point

## Opensearch

| Magento Minor Version | OS 1.x
|:---|---|
|2.4|2.4.4+|

## Databases

### MySQL

| Magento Minor Version | MySQL 5.6 | MySQL 5.7 | MySQL 8.0 |
|:---|---|---|---|
|2.0|✓|✗|✗|
|2.1|✓|2.1.2+|✗|
|2.2|✓|✓|✗|
|2.3|✓<sup>1</sup>|✓|✗|
|2.4|✗|✓<sup>1</sup>|✓|

Notes:
1. Magento is also compatible with, but has not been tested and is not recommended

### MariaDB

| Magento Minor Version | MariaDB 10.0 | MariaDB 10.1 | MariaDB 10.2 | MariaDB 10.3 | MariaDB 10.4 | MariaDB 10.5 |
|:---|---|---|---|---|---|---|
|2.0|✓|✓|✗|✗|✗|✗|
|2.1|✓|✓|2.1.2+|✗|✗|✗|
|2.2|✓|✓|✓<sup>1</sup>|✓<sup>1</sup>|✓<sup>1</sup>|✗|
|2.3|✓<sup>1</sup>|✓<sup>1</sup>|✓<sup>1</sup>|✓<sup>1</sup>|✓<sup>1</sup>|✗|
|2.4|✗|✗|✓<sup>2</sup>|✓<sup>2</sup>|✓<sup>2</sup>|✓|

Notes:
1. Magento only uses MySQL features compatible with MariaDB. MariaDB may not be compatible with all MySQL features, however, so be sure to research compatibility issues before using a feature in your Magento module.
2. Magento is also compatible, but has not been tested and is not recommended

## Redis

| Magento Minor Version | Redis 2.4 | Redis 3.0 | Redis 3.2 | Redis 4.x | Redis 5.x | Redis 6.0 |
|:---|---|---|---|---|---|---|
|2.0|✗|✓|✗|✗|✗|✗|
|2.1|✓|✓|✓|2.1.17+|2.1.17+|✗|
|2.2|✓|✓|✓|✗|✗|✗|
|2.3|Until 2.3.6|Until 2.3.6|Until 2.3.6|2.3.1 - 2.3.5|2.3.1 - 2.3.6| :white_check_mark: 2.3.7+|
|2.4|✗|✗|✗|✗|2.4.0 - 2.4.1|:white_check_mark: 2.4.2+|

## Varnish

| Magento Minor Version | Varnish 3.5 | Varnish 4.x | Varnish 5.x | Varnish 6.x |
|:---|---|---|---|---|
|2.0|✓|✓|✗|✗|
|2.1|✓|✓|✗|✗|
|2.2|✗|✓|✓|✗|
|2.3|✗|✓|✓<sup>1</sup>|✓<sup>2</sup>|
|2.4|✗|✗|✗|✓<sup>3</sup>|

Notes:
1. Magento declares support for 5.2+
2. Magento declares support for 6.2+, 6.5.1 explicitly supported with 2.3.7
3. Tested with 6.3.1.  Magento 2.4.2 tested with 6.4
