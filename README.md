<!-- tyhp-readme:start -->
# tyhpdef/symfony-polyfill-intl-grapheme

Tyhp type definitions for `symfony/polyfill-intl-grapheme` `1.41.0`.

```bash
composer require --dev tyhpdef/symfony-polyfill-intl-grapheme:1.41.0
```

This is a metapackage. Composer also installs `tyhpdef/symfony-polyfill-intl-grapheme-impl` (type files).
Require **this** name, not `tyhpdef/symfony-polyfill-intl-grapheme-impl`.

See https://tyhplang.com.

## Maintain `symfony/polyfill-intl-grapheme`? Ship the types yourself

If you are a Packagist maintainer of `symfony/polyfill-intl-grapheme`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/symfony-polyfill-intl-grapheme-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `symfony/polyfill-intl-grapheme` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/symfony-polyfill-intl-grapheme": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `symfony/polyfill-intl-grapheme` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `symfony/polyfill-intl-grapheme` with a real constraint,
   `"replace": { "tyhpdef/symfony-polyfill-intl-grapheme": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `symfony/polyfill-intl-grapheme` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/symfony-polyfill-intl-grapheme` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
