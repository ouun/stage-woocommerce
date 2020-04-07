# WooCommerce integration for Sage 10 & Stage

This package enables WooCommerce integration with Stage & Sage 10 themes and Blade templates.

## Installation

Install the package in your theme folder:

```bash
composer require ouun/stage-woocommerce
```

## Usage

Create `shop` folder in `/resources/views` folder of your theme and place there any template used by WooCommerce with `.blade.php` extension. This template will be loaded instead of a template from the WooCommerce plugin. If you want to replace particular template, please have a look into plugin folder `woocommerce/templates` and use same folder structure and file name (and change the extension to `.blade.php`) as the original template.

## Forked

This is a fork from `roots/sage-woocommerce` for Sage 9 and adjusted to Sage 10.
