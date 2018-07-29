# AriaNg
[AriaNg](https://github.com/mayswind/AriaNg), a modern web frontend making [aria2](https://github.com/aria2/aria2) easier to use. http://ariang.mayswind.net

[![License](https://img.shields.io/github/license/mayswind/AriaNg.svg)](https://github.com/mayswind/AriaNg/blob/master/LICENSE) [![Lastest Release](https://img.shields.io/github/release/mayswind/AriaNg.svg)](https://github.com/mayswind/AriaNg/releases)

[![Layers](https://images.microbadger.com/badges/image/leonismoe/ariang.svg)](https://microbadger.com/images/leonismoe/ariang) [![Latest Version](https://images.microbadger.com/badges/version/leonismoe/ariang.svg)](https://microbadger.com/images/leonismoe/ariang)

## Introduction
[AriaNg](https://github.com/mayswind/AriaNg) is a modern web frontend making [aria2](https://github.com/aria2/aria2) easier to use. AriaNg is written in pure html & javascript, thus it does not need any compilers or runtime environment. You can just put AriaNg in your web server and open it in your browser. AriaNg uses responsive layout, and supports any desktop or mobile devices.

## Supported architectures
* `x86_64`, `amd64`
* `i386` (Tags are prefixed by `i386-`)

## Run
``` sh
docker run -d --name ariang -p 6080:80 leonismoe/ariang
```

## Features
1. Pure Html & Javascript, no runtime required
2. Responsive design, supporting desktop and mobile devices
3. User-friendly interface
    * Sort tasks (by name, size, progress, remain time, download speed, etc.), files, peers
    * Search tasks
    * Adjust download order by dragging task
    * More information of tasks (health percentage, client infomation of bt peers, etc.)
    * Filter files of tasks in file types (by videos, audios, pictures, documents, applications, archives, etc.)
    * Download/upload history chart of global or task
    * Full support of aria2 settings
4. Url command line api support
5. Download finished notification
6. Multi-languages support
7. Multi aria2 RPC host support
8. Less bandwidth usage, only requesting incremental data

## Screenshots
#### Desktop
![AriaNg](https://raw.githubusercontent.com/mayswind/AriaNg-WebSite/master/screenshots/desktop.png)
#### Mobile Device
![AriaNg](https://raw.githubusercontent.com/mayswind/AriaNg-WebSite/master/screenshots/mobile.png)

#### Usage Notes
Since AriaNg loads language resources asynchronously, you may not open index.html directly on the local file system to run AriaNg. It is recommended that you deploy AriaNg in a web container or download [AriaNg Native](https://github.com/mayswind/AriaNg-Native) that does not require a browser to run.

## Documents
1. [English](http://ariang.mayswind.net)
2. [Simplified Chinese (简体中文)](http://ariang.mayswind.net/zh_Hans)

## Demo
Please visit [http://ariang.mayswind.net/latest](http://ariang.mayswind.net/latest)

## License
[MIT](https://github.com/mayswind/AriaNg/blob/master/LICENSE)
