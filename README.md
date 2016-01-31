'About This App' window for [Electron](https://github.com/atom/electron) apps
=============================================================================

[This package](https://www.npmjs.com/package/about-window) provides 'About This App' window for [Electron](https://github.com/atom/electron) applications.

- [x] Create 'About This App' window from given parameters
  - [x] Icon path
  - [x] Copy right
  - [x] App name and Versions
  - [ ] Description
- [ ] Gather package information from package.json
- [ ] Adjust window size to its contents automatically

You can check [example app](example) to know how to use this package.

```sh
$ git clone https://github.com/rhysd/about-window.git
$ cd about-window
$ npm start
```

You can install this module via [npm](https://www.npmjs.com/).

```sh
$ npm install about-window
```

Only one function is exported as default.  Please see [TypeScript type definition](index.d.ts).

```typescript
export default function openAboutWindow({
    icon_path: string,
    copy_right: string,
    homepage: string,
    user_opt?: BrowserWindowOptions,
}): BrowserWindow
```

### Linux

![Linux screenshot](https://raw.githubusercontent.com/rhysd/ss/master/about-window/about-window-linux.png)

### OS X

![OS X screenshot](https://raw.githubusercontent.com/rhysd/ss/master/about-window/about-window-os-x.png)

### Windows

![Windows screenshot](https://raw.githubusercontent.com/rhysd/ss/master/about-window/about-window-windows.jpg)

## License

[MIT License](/LICENSE.txt).

