# mini-breakpad-server

Minimum collecting server for crash reports sent by
[google-breakpad](https://code.google.com/p/google-breakpad/).


## Features

* No requirement for setting up databases or web servers.
* Collecting crash reports with minidump files.
* Simple web interface for viewing translated crash reports.

## Run

* `npm install .`
* `grunt`
* Put your breakpad symbols under `pool/symbols/`
* `node lib/app.js`

## Building with Docker
```
docker build -t premiereglobal/mini-breakpad-server:dev .
```
