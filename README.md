# [📚 Look Scanned](https://lookscanned.io)

https://lookscanned.io

Look Scanned is a pure frontend site that makes your PDFs look scanned! No need for printers and scanners anymore - everything you need to do is just a few clicks. Inspired by [baicunko/scanyourpdf](https://github.com/baicunko/scanyourpdf).

This fork removes web fonts that were loaded from third party servers. This prevents the user's IP from being shared with other servers, making the site GDPR compliant.

## Features

* Everything is processed in your browser. No privacy risk.
* Works without network connection using PWA.
* See scanned PDF side-by-side in real time.
* Works on all modern browsers and devices.
* All files are static. No backend servers needed.
* Tweak the settings to make your PDF look better.

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

## Credits

* [baicunko/scanyourpdf: Repository for the Scan Your Pdf community](https://github.com/baicunko/scanyourpdf)
* [cancerberoSgx/magica: ImageMagick for browser and Node.js, easy setup, high level API and Command Line Interface](https://github.com/cancerberoSgx/magica)
* [mozilla/pdf.js: PDF Reader in JavaScript](https://github.com/mozilla/pdf.js)
* [Scanner icons created by Freepik - Flaticon](https://www.flaticon.com/free-icons/scanner)

## License

MIT License
