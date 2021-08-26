# `resetServerContext`

Функцию `resetServerContext` следует использовать при рендеринге на стороне сервера (SSR). Это гарантирует, что состояние контекста не сохраняется при нескольких отрисовках на сервере, что может привести к несоответствию разметки клиент / сервер после того, как на сервере будут отрисованы несколько запросов.

Используйте его перед вызовом метода рендеринга на стороне сервера:

```js
import { resetServerContext } from 'react-beautiful-dnd';
import { renderToString } from 'react-dom/server';

// ...

resetServerContext();
renderToString(...);
```

[← Вернуться к документации](/README.md#documentation-)
