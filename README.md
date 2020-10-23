[![Build status](https://ci.appveyor.com/api/projects/status/09oxcrj4uh5b2rm0?svg=true)](https://ci.appveyor.com/project/AndreyKorolevich/serviceworker-homework2-front)
- deployment: <a href="https://andreykorolevich.github.io/serviceworker-homework2-front/">Github Pages</a>
### Buggy Service

#### Легенда

Вам выпала нелёгкая задача - интегрироваться с "глючным" сторонним сервисом новостей. Сервер периодически "отваливается", отвечая кодом 500. Поскольку вы уже знакомы с Service Workers, вы решили кэшировать ответы сервера, когда они всё-таки появляются и отдавать закешированные, если сервер отвечает ошибкой.

#### Описание

Вам необходимо реализовать сервер, эмулирующий эту ситуацию (достаточно выставлять правильный код в koa, как мы это делали в лекции по HTTP, либо можете дополнительно ознакомиться с [обработкой ошибок в koa](https://github.com/koajs/koa/wiki/Error-Handling)).

Общий вид интерфейса:

![](./pic/buggy.png)

Можете использовать сервер из предыдущего задания, добавив туда генерацию ошибки случайным образом.
