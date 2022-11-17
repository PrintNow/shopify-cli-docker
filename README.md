# Shopify CLI Docker

Base on:

- [https://github.com/Shopify/shopify-cli/releases/latest](https://github.com/Shopify/shopify-cli/releases/latest)
- [dylansmith/docker-shopify-cli](https://github.com/dylansmith/docker-shopify-cli)

## Docker images

| tag                  | Docker Pull Command                      |
|----------------------|------------------------------------------|
| **latest** `v2.32.0` | `docker pull shine09/shopify-cli`        |
| **v2.32.0**          | `docker pull shine09/shopify-cli:2.32.0` |

## Custom Build

```shell
docker build -t <tag> --build-arg version=2.32.0 .

# for example
docker build -t shine09/shopify-cli:2.32.0 --build-arg version=2.32.0 .
```
