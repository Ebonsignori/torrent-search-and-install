# Torrent and Install

Install deps

`npm i`

Run CLI app

`npm start`

## Config

Checkout the options in [config.js](./config.js)

Chose what you want to do with the torrent file
```json
method: {
  clipboard: false, // Copy magnet link to clipboard
  openInApp: false, // Open in utorrent (change openInApp prop with name of default app)
  openInDefault: true // Open in default browser
}
```

Chose your preferred provider
```json
providers: {
  available: ['1337x', 'ThePirateBay', 'ExtraTorrent', 'Rarbg', 'Torrent9', 'KickassTorrents', 'TorrentProject', 'Torrentz2'],
  active: '1337x'
}
```
