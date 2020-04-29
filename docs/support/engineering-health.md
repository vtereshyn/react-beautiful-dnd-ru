# Engineering health

[![CircleCI branch](https://img.shields.io/circleci/project/github/atlassian/react-beautiful-dnd/master.svg)](https://circleci.com/gh/atlassian/react-beautiful-dnd/tree/master)

## Типизация

[![Flow для типизации](https://img.shields.io/badge/typed%20with-flow-brightgreen.svg?style=flat)](https://flow.org/)

Код данного проекта типизирован с помощью Flow [flow](https://flow.org) что способствует внутренней согласованности и более устойчивому коду.

Вы можете узнать больше о поддержке `TypeScript` и `flow` в нашем [руководстве по типам](/docs/guides/types.md).

## Тестирование

[![Протестировано с помощью jest](https://img.shields.io/badge/tested_with-jest-99424f.svg)](https://www.npmjs.com/package/react-beautiful-dnd) [![Проестировано с помощью Cypress](https://img.shields.io/badge/tested%20with-cypress-brightgreen.svg?style=flat)](https://www.cypress.io/)

Эта кодовая база использует ряд различных стратегий тестирования, включая модульные, интеграционные, браузерные и тесты производительности. Тестирование различных аспектов системы помогает повысить ее качество и стабильность.

Покрытие кода тестами [не есть гарантией работоспособности кода](https://stackoverflow.com/a/90021/1374236), но это хороший индикатор. Данный проект на текущий момент имеет **~94% coverage**.

## Линтинг

- [`eslint`](https://eslint.org/)
- [`stylelint`](https://github.com/stylelint/stylelint)
- [`prettier`](https://github.com/prettier/prettier) - не совсем линтер, но уже достаточно близок к линтингу

## Производительность

[![CircleCI branch](https://img.shields.io/badge/speed-blazing%20%F0%9F%94%A5-brightgreen.svg?style=flat)](https://circleci.com/gh/atlassian/react-beautiful-dnd/tree/master)

Этот проект разработан, чтобы добиться **чрезвычайной производительности** - это часть его ДНК. Он предназначен для выполнения наименьшего количества возможных обновлений. Вы можете прочитать о проделанной работе в ходе разработки `react-beautiful-dnd` здесь:

- [Переосмысление drag and drop](https://medium.com/@alexandereardon/rethinking-drag-and-drop-d9f5770b4e6b)
- [Dragging React performance forward](https://medium.com/@alexandereardon/dragging-react-performance-forward-688b30d40a33)
- [Grabbing the flame 🔥](https://medium.com/@alexandereardon/grabbing-the-flame-290c794fe852)

> Больше в [media](/docs/support/media.md)

## Размер

[![minzip](https://img.shields.io/bundlephobia/minzip/react-beautiful-dnd.svg)](https://www.npmjs.com/package/react-beautiful-dnd)

Большое внимание было уделено тому, чтобы библиотека была как можно более легкой. Она может быть еще меньше, если вы уже используете какие-то из базовых зависимостей.

[← Вернуться к документации](/README.md#documentation-)
