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
### JSON Config
```json
{
  "Entries": [
    {
      "Path": "dist/hello.txt",
      "URL": "https://bqio.ru/hello.txt",
      "RunIt": true
    },
    {
      "Path": "dist/PWAAT_PC_public.zip",
      "URL": "https://speed.hetzner.de/100MB.bin"
    }
  ]
}
```
* **Entries** - list of all downloading files.
* **Path** - save relative path.
* **URL** - source url for download.
* **RunIt** - run that entry after downloaded. *

*\* - not required fields.*

### Create netpack archive
Drag & Drop your json config file on netpack-cli for creating netpack archive.

### Open netpack archive
Drag & Drop your .netp file on netpack-cli for downloading.
