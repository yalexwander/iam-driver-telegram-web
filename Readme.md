## Introdution

This is an ItIsAllMail driver for site t.me.

Supported features:

- fetcher

## Installation:

1) Install ItIsAllMail.
2) Install the driver.

    cd lib/ItIsAllMail/Driver/
    git clone https://github.com/yalexwander/iam-driver-telegram-web telegram-web

3) Add driver to ItIsAllMail `conf/config.yml`:

```
drivers :
  - "telegram-web"
```

2) Add source in `conf/sources.yml`:

```
- url: https://t.me/opennet_ru
  mailbox_base_dir: /tmp
  mailbox: mailbox_tg
```
