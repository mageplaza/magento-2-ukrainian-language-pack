## Magento 2 Ukrainian Language Pack

Maybe **Magento 2 Ukrainian Language Pack** should be the first must-have thing to discover if you have an eCommerce store in Ukraine. Is it really important? The answer is absolutely yes for me. Because when you start a business in a new country, ensure that the different in the language culture is the biggest barrier. The deals is not be successful if the buyer can not understand what you are mentioning on the website. 

Today, I sincerely introduce the Ukrainian Language Package so that you can use the Ukrainian as a native store in Ukraine. You have to download a zip translation file via the link and install it on the store. Then choose the right store locale (Ukrainian (Ukraine)) from the backend. Please get the guides below for the perfect convertion.

Read more [Magento 2 Ukrainian Language Pack](https://www.mageplaza.com/magento-2-ukrainian-language-pack.html)


## Overview

- Download & Contribute
- Install Ukrainian Language Pack
- How to Install Ukrainian Language Pack

## Download & Contribute to Ukrainian Language Pack

Below are two active buttons which are required operations before installing the language package. Let's hit them to download and contribute Magento 2 Ukrainian Language Pack immediately!

**Download packages**:

- [Download .zip](https://github.com/mageplaza/magento-2-ukrainian-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/mageplaza/magento-2-ukrainian-language-pack/tarball/master)


Find other [language packs here]({https://www.mageplaza.com/kb/magento-2-language-pack/)

## How to Install Ukrainian Language Pack

There are 3 different methods to install this language pack.

### #1. Composer method
Install the Ukrainian language pack via composer is never easier.

**Install Ukrainian pack**:

```
composer require mageplaza/magento-2-ukrainian-language-pack
php bin/magento setup:static-content:deploy uk_UA
php bin/magento cache:clean
php bin/magento cache:flush

```


**Update  Ukrainian pack**:

```
composer update mageplaza/magento-2-ukrainian-language-pack
php bin/magento setup:static-content:deploy uk_UA
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush

```

#### Authentication required (Optional)

![Authentication required](https://cdn.mageplaza.com/media/general/dmryiPk.png)

If you have not added this authentication, you can follow [this guide](http://devdocs.magento.com/guides/v2.0/install-gde/prereq/connect-auth.html)


### #2. Copy & Paste method

This method suitable for non-technical people such as merchants. Just download the package then flush cache.

**Overview**

- Step 1: Download the Ukrainian language pack
- Step 2: Unzip Ukrainian pack
- Step 3: Flush Magento 2 Cache

#### Step 1 : Download the Ukrainian language pack

You can download the language pack from above link

#### Step 2: Unzip Ukrainian pack

Unzip the Ukrainian language pack to Magento 2 root folder. In this guide, we extract to `/var/www/html/`
Your Magento 2 root folder can be: `/home/account_name/yourstore.com/public_html/`

```
unzip fr.zip /var/www/html/
```

You also can unzip locally and upload them to Magento 2 root folder.

#### Step 3: Flush Magento 2 Cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


### #3. Download and install manually

To download and install Ukrainian pack manually, you have to access to your server via FTP or SFTP.

#### Step 1: Download the package

- [Download .zip](https://github.com/mageplaza/magento-2-ukrainian-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/mageplaza/magento-2-ukrainian-language-pack/tarball/master)

#### Step 1: Unzip and upload

Unzip the compressed file and upload file `uk_UA.zip` into `app/i18n/mageplaza/uk_UA/uk_UA.csv`

#### Step 2: Flush cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


## How to active language pack

Now time to active the language pack for your Magento 2 store. From Magento 2 admin panel, navigate to `Stores > Configuration > General > Locale Options`
![{{Magento 2 Ukrainian language pack}}](https://cdn.mageplaza.com/media/general/aPSUA0l.png)


<!-- ## Translation process of Ukrainian Language Pack
![process](http://progressed.io/bar/80) -->

Contribute to this language at https://crowdin.com/project/magento-2/uk

## Supported Magento versions

- Magento v2.0.0
- Magento v2.0.1
- Magento v2.0.2
- Magento v2.0.3
- Magento v2.0.4
- Magento v2.0.5
- Magento v2.0.6
- Magento v2.0.7
- Magento v2.0.8
- Magento v2.0.9
- Magento v2.0.10
- Magento v2.0.11
- Magento v2.0.12
- Magento v2.0.13
- Magento v2.0.14
- Magento v2.0.15
- Magento v2.1.0
- Magento v2.1.1
- Magento v2.1.2
- Magento v2.1.3
- Magento v2.1.4
- Magento v2.1.5
- Magento v2.1.6
- Magento v2.1.7



## Language package authors

- [Magento official translations project for Magento 2](https://crowdin.com/project/magento-2)
- Language packages built by [Mageplaza team](https://www.mageplaza.com/)


## References:

- https://www.mageplaza.com/magento-2-ukrainian-language-pack.html
- https://www.mageplaza.com/kb/magento-2-language-pack/
- https://crowdin.com/project/magento-2