# @dwstyle/icons

Official Icons Library For dWeb dApps, dSites and other dWeb-related projects.

## Usage

```js
const dwebIcons = require('@dwstyle/icons')
var el = dwebIcons()
document.body.appendChild(el)
```

Make sure to include this sprite in your page as the first element after the `<body>` opening tag.

Icons can later be referenced like so:

```html
<svg><use xlink:href="#dwebicon-happy-face"></use></svg>
```

### dWeb Icon Description

| dWeb Icon  | Class |
| ------------- | ------------- |
| <img width="30px" src="http://cdn.dwebs.io/dweb-icons/clipboard.svg"> | `dwebicon-clipboard` |
| <img width="30px" src="http://cdn.dwebs.io/dweb-icons/dpack.svg"> | `dwebicon-new-dpack` |
| <img width="30px" src="http://cdn.dwebs.io/dweb-icons/download.svg"> | `dwebicon-download` |
| <img width="30px" src="http://cdn.dwebs.io/dweb-icons/edit.svg"> | `dwebicon-edit` |
| <img width="30px" src="http://cdn.dwebs.io/dweb-icons/file.svg"> | `dwebicon-file` |
| <img width="30px" src="http://cdn.dwebs.io/dweb-icons/folder.svg"> | `dwebicon-folder` |
| <img width="30px" src="http://cdn.dwebs.io/dweb-icons/happy-face.svg"> | `dwebicon-happy-face` |
| <img width="30px" src="http://cdn.dwebs.io/dweb-icons/dweb-download.svg"> | `dwebicon-dweb-download` |
| <img width="30px" src="http://cdn.dwebs.io/dweb-icons/hexagon-outlines.svg"> | `dwebicon-hexagon-outlines` |
| <img width="30px" src="http://cdn.dwebs.io/dweb-icons/dweb-pause.svg"> | `dwebicon-dweb-pause` |
| <img width="30px" src="http://cdn.dwebs.io/dweb-icons/dweb-resume.svg"> | `dwebicon-dweb-resume` |
| <img width="30px" src="http://cdn.dwebs.io/dweb-icons/dweb-upload.svg"> | `dwebicon-dweb-uload` |
| <img width="30px" src="http://cdn.dwebs.io/dweb-icons/dweb-exit.svg"> | `dwebicon-dweb-exit` |
| <img width="30px" src="http://cdn.dwebs.io/dweb-icons/dweb-import.svg"> | `dwebicon-dweb-import` |
| <img width="30px" src="http://cdn.dwebs.io/dweb-icons/link.svg"> | `dwebicon-link` |
| <img width="30px" src="http://cdn.dwebs.io/dweb-icons/loading.svg"> | `dwebicon-loading` |
| <img width="30px" src="http://cdn.dwebs.io/dweb-icons/letter.svg"> | `dwebicon-letter` |
| <img width="30px" src="http://cdn.dwebs.io/dweb-icons/lock.svg"> | `dwebicon-lock` |
| <img width="30px" src="http://cdn.dwebs.io/dweb-icons/menu.svg"> | `dwebicon-menu` |
| <img width="30px" src="http://cdn.dwebs.io/dweb-icons/network.svg"> | `dwebicon-network` |
| <img width="30px" src="http://cdn.dwebs.io/dweb-icons/open-in-desktop.svg"> | `dwebicon-open-in-desktop` |
| <img width="30px" src="http://cdn.dwebs.io/dweb-icons/open-in-finder.svg"> | `dwebicon-open-in-finder` |
| <img width="30px" src="http://cdn.dwebs.io/dweb-icons/plus.svg"> | `dwebicon-plus` |
| <img width="30px" src="http://cdn.dwebs.io/dweb-icons/question.svg"> | `dwebicon-question` |
| <img width="30px" src="http://cdn.dwebs.io/dweb-icons/sad-face.svg"> | `dwebicon-sad-face` |
| <img width="30px" src="http://cdn.dwebs.io/dweb-icons/favorite.svg"> | `dwebicon-favorite` |
| <img width="30px" src="http://cdn.dwebs.io/dweb-icons/edit.svg"> | `dwebicon-edit` |
| <img width="30px" src="http://cdn.dwebs.io/dweb-icons/info.svg"> | `dwebicon-info` |
| <img width="30px" src="http://cdn.dwebs.io/dweb-icons/gear.svg"> | `dwebicon-gear` |
| <img width="30px" src="http://cdn.dwebs.io/dweb-icons/search.svg"> | `dwebicon-search` |



## Build dWeb Icons

```shell
npm install
npm run build-dweb-icons
```
