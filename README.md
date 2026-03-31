# php

**php** is a GitHub Actions pipeline that:

1. Watches php.net for new releases (daily)
2. Downloads the source tarball and verifies its GPG signature
3. Builds a statically-linked `php` binary using [static-php-cli](https://github.com/crazywhalecc/static-php-cli)
4. Publishes it as a GitHub Release

## Usage (mise)

**I recommend forking this repo and using your own version if you want to guarantee longetivity.**

If not, then:

```bash
mise use github:crdx/php
```

For anything else, there's the releases page.

## Platforms

Linux x86_64 and aarch64. The good ones.

## Contributions

Open an [issue](https://github.com/crdx/php/issues) or send a [pull request](https://github.com/crdx/php/pulls).

## Licence

[GPLv3](LICENCE).
