# js-react-eslint-prettier-husky

Базовая настройка окружения для React-проекта на чистом JS. Версия ноды - 18.19.0 LTS

## Начало работы

```
yarn install
npx mrm@2 lint-staged
```

Удалить из package.json команду с флагом --cache:

```
"lint-staged": "*.{js,jsx,ts,tsx}": "eslint --cache --fix"
```

## Запуск проекта

```
yarn start
```
