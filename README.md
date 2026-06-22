# Celyfos Theme

## Background

This is a custom Shopify theme for [Celyfos](www.example.com), an e-commerce website that sells leather products.

## Features

The theme includes support for Tailwind classes.

## Usage

To use this theme on your own Shopify site, you can download the ZIP file for the theme, then in your Shopify admin page, under Online Store -> Themes, click "Import theme", then "Upload zip file", then upload the ZIP file you downloaded. Keep in mind that the theme uses several pieces of custom metadata, so you will need to add them before uploading the theme.

| Place to add metafield | Definition name   | Type             | Validation | Storefront API Access |
| ---------------------- | ----------------- | ---------------- | ---------- | --------------------- |
| Pages                  | hero_button_link  | URL              | None       | True                  |
| Pages                  | hero_title        | Single line text | None       | True                  |
| Pages                  | hero_button_text  | Single line text | None       | True                  |
| Pages                  | hero_image        | File             | None       | True                  |
| Pages                  | hero_text         | Multi-line text  | None       | True                  |
| Shop                   | processed_orders  | Single line text | None       | False                 |
| Shop                   | fulfillment_month | Single line text | None       | False                 |
| Shop                   | queue_total       | Integer          | Min 0      | False                 |
| Shop                   | monthly_limit     | Integer          | Min 0      | False                 |

This theme also relies on a [custom Shopify app](https://github.com/PROJXON/Get-Monthly-Limit) as well which will also need to be installed prior to installing the theme.
