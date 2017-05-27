# Caddy configuration for running Shopware

This is an example configuration from running [Shopware](https://github.com/shopware/shopware) using
[caddy](https://caddyserver.com/). Which is a HTTP/2 web server with automatic HTTPS.

## Warning

Please only use caddy if you know what you are doing. Shopware AG provides no support for running caddy as appserver.
Also note that Shopware will not run faster with caddy. A properly configured apache webserver is in most cases as fast as caddy or nginx.

## Compatibility

This configuration is tested with Shopware 5.1 or later.