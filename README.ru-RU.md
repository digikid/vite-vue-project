<div align="center">
  <img alt="Vite + Vue Project" src="https://github.com/digikid/vite-vue-project/raw/main/public/images/logo.svg" height="117" />
  <h1>Vite + Vue Project</h1>
  <p>Стартовый шаблон для сборки приложения на Vue и TypeScript</p>
  <p>
    <a href="https://github.com/digikid/vite-vue-project/blob/main/README.md">English</a> | <b>Русский</b></p>
  <img src="https://img.shields.io/github/release/digikid/vite-vue-project.svg?style=flat-square&logo=appveyor" alt="Release version">
  <img src="https://img.shields.io/github/languages/top/digikid/vite-vue-project.svg?style=flat-square&logo=appveyor" alt="TypeScript">
  <img src="https://img.shields.io/github/license/digikid/vite-vue-project.svg?style=flat-square&logo=appveyor" alt="MIT License">
</div>

## О шаблоне

Этот шаблон позволяет без предварительной настройки начать разработку в [Vite]( https://vitejs.dev/) с использованием [Vue](https://vuejs.org/), [TypeScript](https://www.typescriptlang.org/) и набора современных UI инструментов.

## Что включено

### CSS фреймворк

CSS-фреймворк, предлагающий обширный каталог классов и инструментов для облегчения стилизации сайта или приложения.

- [Tailwind CSS](https://tailwindcss.com/)

### CSS плагины

Этот шаблон также включает набор плагинов, необходимых для работы [Tailwind UI](https://tailwindui.com/):

- [forms](https://github.com/tailwindlabs/tailwindcss-forms)
- [typography](https://github.com/tailwindlabs/tailwindcss-typography)
- [line-clamp](https://github.com/tailwindlabs/tailwindcss-line-clamp)
- [aspect-ratio](https://github.com/tailwindlabs/tailwindcss-aspect-ratio)

Утилита нового поколения для добавления префиксов к экспериментальным свойствам из CSS 3 на основе [Can I Use](https://caniuse.com/).

- [Autoprefixer](https://github.com/postcss/autoprefixer)

### UI компоненты

Полностью не стилизованные компоненты, разработанные для интеграции с Tailwind CSS.

- [Headless UI](https://headlessui.com/)

### Шрифты

Шрифт, разработанный специально для экранов компьютеров и рекомендуемый к использованию разработчиками Tailwind CSS.

- [Inter var](https://github.com/rsms/inter) (self-hosted)

### Проверка кода

Линтер с открытым исходным кодом, который помогает находить и устранять проблемы с JavaScript кодом.

- [ESLint](https://eslint.org/) + [Airbnb Config](https://github.com/airbnb/javascript)

Мощный современный линтер, который помогает избежать ошибок и обеспечить соблюдение соглашений в файлах стилей.

- [Stylelint](https://stylelint.io/) + [Standard Config](https://github.com/stylelint/stylelint-config-standard)

## Использование

### Шаблон GitHub

[Создайте репозиторий из этого шаблона на GitHub](https://github.com/digikid/vite-vue-project/generate)

### Локальная установка

```sh
npx degit digikid/vite-vue-project my-project
cd my-project
npm i
```

## Псевдонимы путей (Path aliases)

По умолчанию все псевдонимы путей, объявленные в файле `tsconfig.json`, импортируются в конфигурацию Vite, поэтому вам не нужно объявлять их дважды.

## Поддержка браузерами

Поддерживаются только последние версии основных браузеров (Chrome, Firefox, Safari, Edge и т.д.).

<img src="https://github.com/digikid/vite-vue-project/raw/main/public/images/chrome.svg" width="64" height="64" alt="Chrome"> <img src="https://github.com/digikid/vite-vue-project/raw/main/public/images/firefox.svg" width="64" height="64" alt="Firefox"> <img src="https://github.com/digikid/vite-vue-project/raw/main/public/images/edge.svg" width="64" height="64" alt="Edge"> <img src="https://github.com/digikid/vite-vue-project/raw/main/public/images/safari.svg" width="64" height="64" alt="Safari"> <img src="https://github.com/digikid/vite-vue-project/raw/main/public/images/opera.svg" width="64" height="64" alt="Opera">

**Ни одна версия IE не поддерживается.**

## Лицензия

[The MIT License (MIT)](LICENSE)
