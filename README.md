<p align="center">
  <img src="https://user-images.githubusercontent.com/2182637/53611918-54c1ff80-3c24-11e9-9917-66ac3cef513d.png" alt="react beautiful dnd logo" />
</p>
<h1 align="center">react-beautiful-dnd</h1>

<div align="center">

**Красивый** и **доступный** drag and drop разработанный с помощью библиотеки [`React`](https://facebook.github.io/react/)

[![CircleCI branch](https://img.shields.io/circleci/project/github/atlassian/react-beautiful-dnd/master.svg)](https://circleci.com/gh/atlassian/react-beautiful-dnd/tree/master)
[![npm](https://img.shields.io/npm/v/react-beautiful-dnd.svg)](https://www.npmjs.com/package/react-beautiful-dnd)

![quote application example](https://user-images.githubusercontent.com/2182637/53614150-efbed780-3c2c-11e9-9204-a5d2e746faca.gif)

[Поиграйте с примерами, если хотите!](https://react-beautiful-dnd.netlify.com/iframe.html?selectedKind=board&selectedStory=simple)

</div>

## Основные характеристики

- Красивое и [естественное движение](/docs/about/animations.md) элементов 💐
- [Доступность](/docs/about/accessibility.md): мощная поддержка клавиатуры и программ экранного доступа ♿️
- [Чрезвычайная производительность](/docs/support/media.md) 🚀
- Чистое и мощное API, с которым легко начать работу
- Прекрасно взаимодействое с бразуером
- [Дополнительное стилизование необязательно](/docs/guides/preset-styles.md)
- Нет необходимости создавать лишние обертки - отлично взаимодействует с flexbox и focus.

## Начало работы 👩‍🏫

Мы создали [бесплатный курс на `egghead.io` 🥚](https://egghead.io/courses/beautiful-and-accessible-drag-and-drop-with-react-beautiful-dnd) чтобы помочь вам начать работу с `react-beautiful-dnd` как можно быстрее.

[![course-logo](https://user-images.githubusercontent.com/2182637/43372837-8c72d3f8-93e8-11e8-9d92-a82adde7718f.png)](https://egghead.io/courses/beautiful-and-accessible-drag-and-drop-with-react-beautiful-dnd)

## Поддерживаемые функции на данный момент ✅

- Вертикальные списки ↕
- Горизонтальные списки ↔
- Передвижение между списками (▤ ↔ ▤)
- [Объединение элементов](/docs/guides/combining.md)
- Поддержка мыши 🐭, клавиатуры 🎹♿️ и тач скрина 👉📱 (на мобильном, планшетном и других устройствах)
- [Поддержка multi grag](/docs/patterns/multi-drag.md)
- Incredible screen reader support ♿️ - we provide an amazing experience for english screen readers out of the box 📦. We also provide complete customisation control and internationalisation support for those who need it 💖
- [Conditional dragging](/docs/api/draggable.md#optional-props) and [conditional dropping](/docs/api/droppable.md#conditionally-dropping)
- Multiple independent lists on the one page
- Flexible item sizes - the draggable items can have different heights (vertical lists) or widths (horizontal lists)
- [Add and remove items during a drag](/docs/guides/changes-while-dragging.md)
- Compatible with semantic `<table>` reordering - [table pattern](/docs/patterns/tables.md)
- [Auto scrolling](/docs/guides/auto-scrolling.md) - automatically scroll containers and the window as required during a drag (even with keyboard 🔥)
- Custom drag handles - you can drag a whole item by just a part of it
- Compatible with [`ReactDOM.createPortal`](https://reactjs.org/docs/portals.html) - [portal pattern](/docs/patterns/using-a-portal.md)
- 🌲 Tree support through the [`@atlaskit/tree`](https://atlaskit.atlassian.com/packages/core/tree) package
- A `<Droppable />` list can be a scroll container (without a scrollable parent) or be the child of a scroll container (that also does not have a scrollable parent)
- Independent nested lists - a list can be a child of another list, but you cannot drag items from the parent list into a child list
- Server side rendering (SSR) compatible - see [resetServerContext()](/docs/api/reset-server-context.md)
- Прекрасно работает с [вложенными интерактивными элементами](/docs/api/draggable.md#interactive-child-elements-within-a-draggable-) по-умолчанию

## Мотивация 🤔

`react-beautiful-dnd` разработан для создания красивых перетаскиваний элементов списка/списков. Их может использовать любой, даже люди, у которых проблемы со зрением. Для получения большей информации и мотивации по использованию проекта вы можете взглянуть на внешние ресурсы:

- 📖 [Rethinking drag and drop](https://medium.com/@alexandereardon/rethinking-drag-and-drop-d9f5770b4e6b)
- 🎧 [React podcast: fast, accessible and beautiful drag and drop](https://reactpodcast.simplecast.fm/17)

## Не для всех ✌️

There are a lot of libraries out there that allow for drag and drop interactions within React. Most notable of these is the amazing [`react-dnd`](https://github.com/react-dnd/react-dnd). It does an incredible job at providing a great set of drag and drop primitives which work especially well with the [wildly inconsistent](https://www.quirksmode.org/blog/archives/2009/09/the_html5_drag.html) html5 drag and drop feature. `react-beautiful-dnd` is a higher level abstraction specifically built for lists (vertical, horizontal, movement between lists, nested lists and so on). Within that subset of functionality `react-beautiful-dnd` offers a powerful, natural and beautiful drag and drop experience. However, it does not provide the breadth of functionality offered by `react-dnd`. So `react-beautiful-dnd` might not be for you depending on what your use case is.

## Документация 📖

### Описание 👋

- [Установка](/docs/about/installation.md)
- [Примеры](/docs/about/examples.md)
- [Начало работы](https://egghead.io/courses/beautiful-and-accessible-drag-and-drop-with-react-beautiful-dnd)
- [Дизайн принципы](/docs/about/design-principles.md)
- [Анимации](/docs/about/animations.md)
- [Доступность](/docs/about/accessibility.md)
- [Поддержка браузерами](/docs/about/browser-support.md)

### Сенсоры 🔉

> Способы, с помощью которых можно использовать drag and drop

- [Перетаскивание мышью 🐭](/docs/sensors/mouse.md)
- [Перетаскивание тачем 👉📱](/docs/sensors/touch.md)
- [Перетаскивание клавиатурой 🎹♿️](/docs/sensors/keyboard.md)

### API 🏋️‍

![диаграмма](https://user-images.githubusercontent.com/2182637/53607406-c8f3a780-3c12-11e9-979c-7f3b5bd1bfbd.gif)

- [`<DragDropContext />`](/docs/api/drag-drop-context.md) - _Wraps the part of your application you want to have drag and drop enabled for_
- [`<Droppable />`](/docs/api/droppable.md) - _An area that can be dropped into. Contains `<Draggable />`s_
- [`<Draggable />`](/docs/api/draggable.md) - _What can be dragged around_
- [`resetServerContext()`](/docs/api/reset-server-context.md) - _Utility for server side rendering (SSR)_

### Руководства 🗺

- [`<DragDropContext />`](/docs/guides/responders.md) - _`onDragStart`, `onDragUpdate`, `onDragEnd` и `onBeforeDragStart`_
- [Комбинация `<Draggable />`s](/docs/guides/combining.md)
- [Общие возможные проблемы с настройкой](/docs/guides/common-setup-issues.md)
- [Используя `innerRef`](/docs/guides/using-inner-ref.md)
- [Предупреждения для разработчика и как их отключить](/docs/guides/developer-warnings.md)
- [Правила для `draggableId` и `droppableId`s](/docs/guides/identifiers.md)
- [Кастомизация и пропуск анимации "отбрасывания"](/docs/guides/drop-animation.md)
- [Авто-скроллинг](/docs/guides/auto-scrolling.md)
- [Контроль скрин программ экранного доступа](/docs/guides/screen-reader.md)
- [Использование html5 `doctype`](/docs/guides/doctype.md)
- [`TypeScript` и `flow`](/docs/guides/types.md)
- [Dragging `<svg>`](/docs/guides/dragging-svgs.md)
- [Неочевидные предустановленные стили](/docs/guides/preset-styles.md)
- [Как мы обнаруживаем скролл-контейнеры](/docs/guides/how-we-detect-scroll-containers.md)
- [Как мы используем события dom](/docs/guides/how-we-use-dom-events.md) - _Полезно, если вы решили построить что-то поверх `react-beautiful-dnd`_
- [Добавление `<Draggable />`s в момент передвижения](/docs/guides/changes-while-dragging.md) - _⚠️ Продвинутый уровень_

### Паттерны 👷‍

- [Мульти драг](/docs/patterns/multi-drag.md)
- [Таблицы](/docs/patterns/tables.md)
- [Используя порталы (`ReactDOM.createPortal`)](/docs/patterns/using-a-portal.md)

### Поддержка 👩‍⚕️

- [Разработка](/docs/support/engineering-health.md)
- [Сообщество и аддоны](/docs/support/community-and-addons.md)
- [Информация о релизах и логи изменений](https://github.com/atlassian/react-beautiful-dnd/releases)
- [Обновления](/docs/support/upgrading.md)
- [План](https://github.com/atlassian/react-beautiful-dnd/issues)
- [Медиа](/docs/support/media.md)

## Читать документацию на других языках 🌎

- [![us](https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/United-States.png) **English**](https://github.com/atlassian/react-beautiful-dnd)
- [![kr](https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/South-Korea.png) **한글/Korean**](https://github.com/LeeHyungGeun/react-beautiful-dnd-kr)
- [![china](https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/China.png) **中文/Chinese**](https://github.com/chinanf-boy/react-beautiful-dnd-zh)

## Автор ✍️

Alex Reardon [@alexandereardon](https://twitter.com/alexandereardon)

## Контрибьюторы 🤝

- Bogdan Chadkin [@IAmTrySound](https://twitter.com/IAmTrySound)
- Luke Batchelor [@alukebatchelor](https://twitter.com/alukebatchelor)
- Jared Crowe [@jaredjcrowe](https://twitter.com/jaredjcrowe)
- Many other [@Atlassian](https://twitter.com/Atlassian)'s!
