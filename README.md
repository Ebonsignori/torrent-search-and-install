# Torrent Search and Install

A tool that lets you search for torrents and open their magnet URL in your torrent client without leaving your CLI.

## Usage
Install deps

`npm i`

Run CLI app

`npm start`

## Config

Checkout the options in [config.js](./config.js)

Chose what you want to do with the torrent file
```javascript
method: {
  clipboard: false, // Copy magnet link to clipboard
  openInApp: false, // Open in utorrent (change openInApp prop with name of default app)
  openInDefault: true // Open in default browser
}
```

Chose your preferred provider
```javascript
providers: {
  available: ['1337x', 'ThePirateBay', 'ExtraTorrent', 'Rarbg', 'Torrent9', 'KickassTorrents', 'TorrentProject', 'Torrentz2'],
  active: '1337x'
}
```
