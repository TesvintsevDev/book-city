Vanilla JS Book App

# Book City

Vanilla JS Book App

## Установка

В первую очередь убедитесь, что у вас установлен [Node.js](https://nodejs.org/en/).

1. Клонируйте репозиторий:

   
bash
   git clone https://github.com/TesvintsevDev/book-city
   

2. Перейдите в директорию проекта:

   
bash
   cd book-city
   

3. Установите зависимости:

   
bash
   npm install
   

## Использование

У вас должен быть установлен live server глобально.
Чтобы запустить разработческий сервер, выполните следующую команду:

bash
npm live-server


Это запустит приложение в вашем браузере по умолчанию и автоматически обновит его при внесении изменений в код.

Для сборки приложения для продакшена используйте следующую команду:

bash
npm run build


Это сгенерирует оптимизированные и минифицированные файлы в директории dist.

## Зависимости

- [@rollup/plugin-node-resolve](https://www.npmjs.com/package/@rollup/plugin-node-resolve) - Разрешение модулей Node.js в браузере
- [eslint](https://www.npmjs.com/package/eslint) - Линтер JavaScript
- [rollup](https://www.npmjs.com/package/rollup) - Модульный бандлер
- [rollup-plugin-import-css](https://www.npmjs.com/package/rollup-plugin-import-css) - Импорт CSS-файлов в Rollup

## Разработка

- [on-change](https://www.npmjs.com/package/on-change) - Отслеживание изменений объектов и выполнение функций при изменении
