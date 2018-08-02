<p align="center">
  <a href="http://ant.design">
    <img width="230" src="https://gw.alipayobjects.com/zos/rmsportal/KDpgvguMpGfqaHPjicRK.svg">
  </a>
</p>

# Ant Design

[![](https://img.shields.io/travis/ant-design/ant-design/master.svg?style=flat-square)](https://travis-ci.org/ant-design/ant-design)
[![Codecov](https://img.shields.io/codecov/c/github/ant-design/ant-design/master.svg?style=flat-square)](https://codecov.io/gh/ant-design/ant-design/branch/master)
[![Dependencies](https://img.shields.io/david/ant-design/ant-design.svg)](https://david-dm.org/ant-design/ant-design)
[![DevDependencies](https://img.shields.io/david/dev/ant-design/ant-design.svg)](https://david-dm.org/ant-design/ant-design?type=dev)

[![npm package](https://img.shields.io/npm/v/antd.svg?style=flat-square)](https://www.npmjs.org/package/antd)
[![NPM downloads](http://img.shields.io/npm/dm/antd.svg?style=flat-square)](http://www.npmtrends.com/antd)
[![Percentage of issues still open](http://isitmaintained.com/badge/open/ant-design/ant-design.svg)](http://isitmaintained.com/project/ant-design/ant-design "Percentage of issues still open")
[![Gitter](https://badges.gitter.im/ant-design/ant-design-english.svg)](https://gitter.im/ant-design/ant-design-english?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge) (English)
[![Join the chat at https://gitter.im/ant-design/ant-design](https://img.shields.io/gitter/room/ant-design/ant-design.svg?style=flat-square)](https://gitter.im/ant-design/ant-design?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)（中文）

Интерфейсная библиотека корпоративного класса на React.

[中文 README](README-zh_CN.md) | [English README](README.md)

## Версия 3.0 вышла! :tada::tada::tada:

[Announcing Ant Design 3.0](https://medium.com/ant-design/announcing-ant-design-3-0-70e3e65eca0c)

## Возможности

- Дизайн-система корпоративного класса для настольных приложений.
- Набор высококачественных React-компонентов "из коробки".
- Написан на TypeScript с предсказуемыми статическими типами.
- Полный пакет из кода, дизайн-ресурсов и инструментов.

## Поддержка сред

* Современные браузеры и Internet Explorer 9+ (с [polyfills](https://ant.design/docs/react/getting-started#Compatibility))
* Рендеринг на стороне сервера
* [Electron](http://electron.atom.io/)

| [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png" alt="IE / Edge" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>IE / Edge | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png" alt="Firefox" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Firefox | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png" alt="Chrome" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Chrome | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari/safari_48x48.png" alt="Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Safari | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/opera/opera_48x48.png" alt="Opera" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Opera | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/electron/electron_48x48.png" alt="Electron" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Electron |
| --------- | --------- | --------- | --------- | --------- | --------- |
| IE9, IE10, IE11, Edge| последние 2 версии| последние 2 версии| последние 2 версии| последние 2 версии| последние 2 версии

## Давайте вместе сделаем antd лучше [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

Прочитайте нашу [инструкцию по распространению](https://ant.design/docs/react/contributing).

## Установка

```bash
npm install antd --save
```

## Использование

```jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
```

Импортируйте стили вручную:

```jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
```

Или [импортируйте компоненты по запросу](https://ant.design/docs/react/getting-started#Import-on-Demand)

### TypeScript

Смотрите [Использование TypeScript](https://ant.design/docs/react/use-in-typescript)

## Мультиязычность

Смотрите [i18n](http://ant.design/docs/react/i18n).

## Ссылки

- [Домашняя страница](http://ant.design/)
- [Компоненты](http://ant.design/docs/react/introduce)
- [Ant Design Pro](http://pro.ant.design/)
- [История изменений](CHANGELOG.en-US.md)
- [Scaffold Market](http://scaffold.ant.design)
- [rc-components](http://react-component.github.io/)
- [Мобильный UI](http://mobile.ant.design)
- [Ant Motion](https://motion.ant.design)
- [Документация разработчика](https://github.com/ant-design/ant-design/wiki/Development)
- [Информация по релизам](https://github.com/ant-design/ant-design/wiki/%E8%BD%AE%E5%80%BC%E8%A7%84%E5%88%99%E5%92%8C%E7%89%88%E6%9C%AC%E5%8F%91%E5%B8%83%E6%B5%81%E7%A8%8B)
- [FAQ](https://github.com/ant-design/ant-design/wiki/FAQ)
- [Шаблон CodeSandbox](https://u.ant.design/codesandbox-repro) для фиксации багов
- [Awesome Ant Design](https://github.com/websemantics/awesome-ant-design)
- [Кастомизация тем](http://ant.design/docs/react/customize-theme)

## Разработка

```bash
$ git clone git@github.com:ant-design/ant-design.git
$ cd ant-design
$ npm install
$ npm start
```

Откройте ваш брайзер и перейдите по ссылке http://127.0.0.1:8001 , читайте дополнительно в [Разработка](https://github.com/ant-design/ant-design/wiki/Development).

## Распространение

Мы приветствуем любые варианты распространения. Почитайте [CONTRIBUTING.md](https://github.com/ant-design/ant-design/blob/master/.github/CONTRIBUTING.md) для начала. Вы можете отправлять любые идеи через [pull-реквесты](https://github.com/ant-design/ant-design/pulls) или [GitHub issues](https://github.com/ant-design/ant-design/issues). Если вы хотите усовершенствовать код, изучите [Документацию разработчика](https://github.com/ant-design/ant-design/wiki/Development) и проведите хорошо время! :)
