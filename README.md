# [lookscanned.io](https://lookscanned.io)

Look Scanned is a pure frontend site that makes your PDFs look scanned! No need for printers and scanners anymore - everything you need to do is just a few clicks. Inspired by [baicunko/scanyourpdf](https://github.com/baicunko/scanyourpdf).

This fork removes web fonts that were loaded from third party servers. This allows the site to be used without "talking" to the Internet at all.

## Develop

```sh
npm run dev
```

## Build

```sh
npm run build:all
```

## Run

### Local port only

```sh
npm run serve
```

### Local and external port

```sh
npm run serve -- --host
```

## Credit

* [baicunko/scanyourpdf](https://github.com/baicunko/scanyourpdf)
* [cancerberoSgx/magica](https://github.com/cancerberoSgx/magica)
* [mozilla/pdf.js](https://mozilla.github.io/pdf.js/)
* [Scanner icons created by Freepik - Flaticon](https://www.flaticon.com/free-icons/scanner)
