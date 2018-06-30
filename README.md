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

- <img width="16px" src="http://cdn.dwebs.io/icons/clipboard.svg"> `dwebicon-clipboard`
- <img width="16px" src="http://cdn.dwebs.io/icons/create-new-dat.svg"> `dwebicon-new-dpack`
- <img width="16px" src="http://cdn.dwebs.io/icons/delete.svg"> `dwebicon-delete`
- <img width="16px" src="http://cdn.dwebs.io/icons/download.svg"> `dwebicon-download`
- <img width="16px" src="http://cdn.dwebs.io/icons/edit.svg"> `dwebicon-edit`
- <img width="16px" src="http://cdn.dwebs.io/icons/file.svg"> `dwebicon-file`
- <img width="16px" src="http://cdn.dwebs.io/icons/folder.svg"> `dwebicon-folder`
- <img width="16px" src="http://cdn.dwebs.io/icons/happy-face.svg"> `dwebicon-happy-face`
- <img width="16px" src="http://cdn.dwebs.io/icons/dweb-download.svg"> `dwebicon-dweb-download`
- <img width="16px" src="http://cdn.dwebs.io/icons/hexagon-outlines.svg"> `dwebicon-hexagon-outlines`
- <img width="16px" src="http://cdn.dwebs.io/icons/dweb-pause.svg"> `dwebicon-dweb-pause`
- <img width="16px" src="http://cdn.dwebs.io/icons/dweb-resume.svg"> `dwebicon-dweb-resume`
- <img width="16px" src="http://cdn.dwebs.io/icons/dweb-upload.svg"> `dwebicon-dweb-upload`
- <img width="16px" src="http://cdn.dwebs.io/icons/dweb-exit.svg"> `dwebicon-dweb-exit`
- <img width="16px" src="http://cdn.dwebs.io/icons/import.svg"> `dwebicon-import`
- <img width="16px" src="http://cdn.dwebs.io/icons/link.svg"> `dwebicon-link`
- <img width="16px" src="http://cdn.dwebs.io/icons/loading.svg"> `dwebicon-loading`
- <img width="16px" src="http://cdn.dwebs.io/icons/letter.svg"> `dwebicon-letter`
- <img width="16px" src="http://cdn.dwebs.io/icons/lock.svg"> `dwebicon-lock`
- <img width="16px" src="http://cdn.dwebs.io/icons/menu.svg"> `dwebicon-menu`
- <img width="16px" src="http://cdn.dwebs.io/icons/network.svg"> `dwebicon-network`
- <img width="16px" src="http://cdn.dwebs.io/icons/open-in-desktop.svg"> `dwebicon-open-in-desktop`
- <img width="16px" src="http://cdn.dwebs.io/icons/open-in-finder.svg"> `dwebicon-open-in-finder`
- <img width="16px" src="http://cdn.dwebs.io/icons/plus.svg"> `dwebicon-plus`
- <img width="16px" src="http://cdn.dwebs.io/icons/question.svg"> `dwebicon-question`
- <img width="16px" src="http://cdn.dwebs.io/icons/sad-face.svg"> `dwebicon-sad-face`
- <img width="16px" src="http://cdn.dwebs.io/icons/star.svg"> `dwebicon-star`
- <img width="16px" src="http://cdn.dwebs.io/icons/edit.svg"> `dwebicon-edit`
- <img width="16px" src="http://cdn.dwebs.io/icons/info.svg"> `dwebicon-info`
- <img width="16px" src="http://cdn.dwebs.io/icons/gear.svg"> `dwebicon-gear`
- <img width="16px" src="http://cdn.dwebs.io/icons/search.svg"> `dwebicon-search`


## Build dWeb Icons

```shell
npm install
npm run build-dweb-icons
```
