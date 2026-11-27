+++
title = "Быстрый старт"
weight = 1
description = "С чего начать: открыть приложение, выбрать источники данных и поля, построить таблицу и выгрузить результат."
+++

JoinSheets — браузерный конструктор таблиц: он объединяет плоские таблицы по
ключу и собирает из них отображение, которое Вам нужно.

Короткий путь от запуска программы до первого результата укладывается всего в три экрана,
между которыми Вы можете переключаться кнопками главного меню.

{{< mermaid >}}
%%{init: {'block': {'padding': 40}}}%%
block-beta
columns 3
D("Данные") F("Поля") T("Таблица")
X("Excel или CSV"):3
D --> F
F --> D
F --> T
T --> F
T --> X
X --> D
classDef stage fill:#f2f5f7,stroke:#141010,stroke-width:2px,color:#141010
classDef io fill:#6e6e73,stroke:#141010,stroke-width:2px,color:#ffffff
class D,F,T stage
class X io
{{< /mermaid >}}

<div style="height:2rem"></div>

1. [Запуск приложения](01-open-the-app/)
2. [Экран «Данные»](02-data-screen/)
3. [Экран «Поля»](03-fields-screen/)
4. [Экран «Таблица» и работа с данными](04-table-screen/)
5. [Сохраните результат](05-save-preset/)
