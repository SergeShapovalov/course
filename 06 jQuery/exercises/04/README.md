# Игра Жизнь

![Game of Life](http://www.diga.me.uk/LifeAnimation.gif)

Вам надо реализовать браузерную версию [игры Жизнь](https://ru.wikipedia.org/wiki/%D0%96%D0%B8%D0%B7%D0%BD%D1%8C_%28%D0%B8%D0%B3%D1%80%D0%B0%29). Визуализация органичивается только вашей фантазией([коллекция реализаций игры для вдохновения](http://codepen.io/collection/BHedk/)).

Правила игры:
- в пустой (мёртвой) клетке, рядом с которой ровно 3 живые клетки, зарождается жизнь;
- если у живой клетки есть 2 или 3 живые соседки, то эта клетка продолжает жить;
- если соседей меньше 2 или больше 3, клетка умирает («от одиночества» или «от перенаселённости»)

Игра прекращается, если
- на поле не останется ни одной «живой» клетки;
- при очередном шаге ни одна из клеток не меняет своего состояния.

Требования к реализации:
- игровое поле 20 на 20 клеток;
- начальное состояние клетки можно менять кликнув по ней;
- кнопки Start/Pause(запускает или останавливает игру), Clear(останавливает и очищает поле);
- выбор из нескольких готовых фигур([планер](https://ru.wikipedia.org/wiki/%D0%9F%D0%BB%D0%B0%D0%BD%D0%B5%D1%80_(%D0%BA%D0%BE%D0%BD%D1%84%D0%B8%D0%B3%D1%83%D1%80%D0%B0%D1%86%D0%B8%D1%8F_%D0%BA%D0%BB%D0%B5%D1%82%D0%BE%D1%87%D0%BD%D0%BE%D0%B3%D0%BE_%D0%B0%D0%B2%D1%82%D0%BE%D0%BC%D0%B0%D1%82%D0%B0)), [пасека](https://upload.wikimedia.org/wikipedia/commons/b/bf/Conways_game_of_life_honey_farm.png)) и [крест](https://ru.wikipedia.org/wiki/%D0%9E%D1%81%D1%86%D0%B8%D0%BB%D0%BB%D1%8F%D1%82%D0%BE%D1%80_(%D0%BA%D0%BE%D0%BD%D1%84%D0%B8%D0%B3%D1%83%D1%80%D0%B0%D1%86%D0%B8%D1%8F_%D0%BA%D0%BB%D0%B5%D1%82%D0%BE%D1%87%D0%BD%D0%BE%D0%B3%D0%BE_%D0%B0%D0%B2%D1%82%D0%BE%D0%BC%D0%B0%D1%82%D0%B0));
- счетчик количества поколений;
- уведомление о прекращении игры.

Плюсом будет
- возможность изменить размеры игрового мира;
- если вы придумаете, как оптимизировать хранение вселенной для игры очень большого размера;
- визуализация с помощью [canvas](https://habrahabr.ru/post/111308/).
