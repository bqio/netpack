<p align="center">
  <img width="100" height="100" src="logo.png">
</p>
<h1 align="center">Netpack</h1>
<p align="center">Smart utility for download content.</p>
<p align="center">
  <a href="https://github.com/bqio/netpack/releases">
    <img src="https://img.shields.io/github/downloads/bqio/netpack/total.svg">
  </a>
</p>

## For users
Download and install latest version app and double click on any .netp file.

## For developers
Download binary.zip archive.

### JSON Config
```json
{
  "Entries": [
    {
      "Path": "dist/src/hello.txt",
      "URL": "https://bqio.ru/hello.txt",
      "RunIt": true
    },
    {
      "Path": "dist/yd/hello.txt",
      "URL": "https://yadi.sk/d/cmcVnCRTC89_Wg"
    }
  ]
}
```
* **Entries** - list of all downloading files.
* **Path** - save relative path.
* **URL** - source url for download.
* **RunIt** - run that entry after all files downloaded. *

*\* - not required fields.*

### Create netpack archive
Drag & Drop your json config file on netpack-cli for creating netpack archive.

### Open netpack archive
Drag & Drop your .netp file on netpack-cli for downloading.

### Supported link formats
* Source URL, ex. (https://bqio.ru/hello.txt)
* Yandex Disk URL, ex. (https://yadi.sk/d/cmcVnCRTC89_Wg)
