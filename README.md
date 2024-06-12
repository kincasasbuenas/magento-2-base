# Kinuz Base for Magento 2

## How to install

### 1. Install via composer (recommend)

I recommend you to install Kinuz_Base module via composer. It is easy to install, update and maintaince.

Run the following command in Magento 2 root folder.

#### 1.1 Install

```
composer require kinuz/base
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy -f
```

Run compile if your store in Production mode:

```
php bin/magento setup:di:compile
```

### 2. Copy and paste

If you don't want to install via composer, you can use this way. 

- Download [the latest version here](https://github.com/kincasasbuenas/magento-2-base/archive/master.zip) 
- Extract `master.zip` file to `app/code/Kinuz/Base` ; You should create a folder path `app/code/Kinuz/Base` if not exist.
- Go to Magento root folder and run upgrade command line to install `Kinuz_Base`:

```
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```