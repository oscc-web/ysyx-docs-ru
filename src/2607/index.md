---
sidebarDepth: 3
sidebar: auto
pageClass: "ysyx-index"
---

**# Главная страница курса «One Student One Chip» v26.07**

\* Время занятий: будет определено позже

\* Если вы обнаружили ошибки в лабораторных руководствах или материалах либо у вас есть вопросы или предложения по экспериментам, пожалуйста, свяжитесь с Yu Zihao по электронной почте (yuzihao#ict.ac.cn).

    \* Поскольку всё больше студентов отправляют в качестве предложений по исправлению неверные ответы, сгенерированные ИИ, если в течение одной недели на письмо не поступил ответ, по умолчанию считается, что предложение не было принято.

**## Учебные ресурсы**

\* Столбец \`Time\` показывает примерное время выполнения в часах.

  \* Материалы с оценочным временем выполнения \`2\` обычно не содержат заданий по программированию,

    а состоят из 2 часов видеолекций, предназначенных для дополнения соответствующих знаний.

  \* Поскольку уровень подготовки студентов различается, эти оценки рассчитаны на учащихся «среднего уровня».

    Этот «средний уровень» не означает «набирать более 80% на курсах по программированию»,

    а означает «иметь правильное отношение к обучению, самостоятельно написать хотя бы одну программу объёмом более 500 строк кода и понимать отладку».

  \* Если вы абсолютный новичок, рассчитывайте потратить на обучение в 2–3 раза больше указанного времени.

    Не расстраивайтесь — как говорится, «кто-то учится раньше, кто-то позже». Другие студенты продвигаются быстрее в основном потому, что уже вложили усилия, чтобы преодолеть начальный этап.

\* Нажимайте на значки, чтобы перейти к соответствующим ресурсам

\* Полные конспекты лекций доступны через панель навигации в правом верхнем углу

\* Материалы курса созданы с помощью [reveal.js][reveal.js] и могут быть экспортированы в PDF — см. [это руководство][reveal.js export pdf]

\* Конспекты этапа S всё ещё coming soon™. 🕊

[reveal.js]: https\://revealjs.com

[reveal.js export pdf]: https\://revealjs.com/pdf-export/

\`C\` = язык C ( программы / эмуляторы / системное ПО ) | \`R\` = набор инструкций RISC-V | \`P\` = проектирование процессора | \`T\` = инструменты

\<style scoped type="text/css">

    @media (max-width: 719px) {

        table {

            font-size: 3vw

        }

    }

    @media (min-width: 720px) {

        [task] {

            width: 20em

        }

    }

    table {

        display: table;

        vertical-align: center;

    }

    table > \* {

        min-width: 100%;

    }

    td {

        vertical-align: center;

        text-align: center;

    }

    table [\_],

    table [x] {

        padding: 0;

        width: 3.6em;

    }

    [stage-title] {

        /\* word-break\:break-all; \*/

        padding: 1em;

    }

    thead {

        position: sticky;

        /\* Не забудьте это: требуется для закрепления элемента \*/

        top: var(--navbar-height);

        /\* Стили \*/

        padding-top: 0.5em;

        padding-bottom: 0.5em;

        backdrop-filter: contrast(0.5) blur(4px) brightness(120%);

    }

    [task] {

        padding-left: 0.8em;

        padding-right: 0.8em;

        text-align: left;

    }

    /\* Поместить галочку внутри \<td x> (сокращение для \<td xked>) \*/

    td[x]::before {

        content: '✓';

    }

    td[x] {

        background-color: hsla(var(--hue), calc(2 \* var(--saturation)), 50%, 0.1) !important;

    }

    /\* Окрашивание по стилю \*/

    .Achievement td {

        font-weight: bold;

        line-height: 1em;

        background-color: hsla(100, 100%, 30%, 0.3) !important;

        /\* border-left: 12px Green solid; \*/

    }

    tbody > tr {

        \--hue: 0;

        \--saturation: 50%;

        background-color: hsla(var(--hue), var(--saturation), 50%, 0.1) !important;

    }

    .Stage-F { --hue: 000; }

    .Stage-E { --hue: 050; }

    .Stage-D { --hue: 100; }

    .Stage-C { --hue: 150; }

    .Stage-B { --hue: 200; }

    .Stage-A { --hue: 250; }

    .Stage-S { --hue: 300; }

    .Other-Topic { --saturation: 0%; }

\</style>

\<table id="schedule-table">

    \<thead>

        \<tr>

            \<th \_>Этап\</th> \<th>Номер\</th>

            \<th>Задание\</th> \<th>Время\</th> \<th>Конспект курса\</th> \<th>Слайды\</th> \<th>Видео\</th>

            \<th \_>C\</th> \<th \_>R\</th> \<th \_>P\</th> \<th \_>T\</th>

        \</tr>

    \</thead>

    \<tbody>

        \<tr class="Stage-F">

            \<td stage-title rowspan="6">Этап F\</td>

            \<td>F1\</td> \<td task>Как правильно задавать вопросы\</td> \<td>2\</td>

            \<td \_>\<a href="2607/f/1.html" target="\_blank">📚\</a>\</td>

            \<td \_>\<a href="https\://ysyx.oscc.cc/slides/2407/01.html#/" target="\_blank">📰\</a>\</td>

            \<td \_>\<a href="https\://www\.bilibili.com/video/BV1WvHazNEsk/" target="\_blank">🎬\</a>\</td>

            \<td \_>\</td> \<td \_>\</td> \<td \_>\</td> \<td \_>\</td>

        \</tr>

        \<tr class="Stage-F">

            \<td>F2\</td> \<td task>Установка и использование Logisim\</td> \<td>2\</td>

            \<td \_>\<a href="2607/f/2.html" target="\_blank">📚\</a>\</td>

            \<td \_> - \</td>

            \<td \_> - \</td>

            \<td \_>\</td> \<td \_>\</td> \<td \_>\</td> \<td x>\</td>

        \</tr>

        \<tr class="Stage-F">

            \<td>F3\</td> \<td task>Основы цифровых логических схем\</td> \<td>20\</td>

            \<td \_>\<a href="2607/f/3.html" target="\_blank">📚\</a>\</td>

            \<td \_>\<a href="https\://ysyx.oscc.cc/slides/2407/02.html#/" target="\_blank">📰Ч.1\</a>\<br>

                  \<a href="https\://ysyx.oscc.cc/slides/2407/03.html#/" target="\_blank">📰Ч.2\</a>\</td>

            \<td \_>\<a href="https\://www\.bilibili.com/video/BV19nWNz2EZC" target="\_blank">🎬Ч.1\</a>\<br>

                  \<a href="https\://www\.bilibili.com/video/BV1xentzxED7" target="\_blank">🎬Ч.2\</a>\</td>

            \<td \_>\</td> \<td \_>\</td> \<td x>\</td> \<td \_>\</td>

        \</tr>

        \<tr class="Stage-F">

            \<td>F4\</td> \<td task>Модель конечного автомата компьютерных систем\</td> \<td>5\</td>

            \<td \_>\<a href="2607/f/4.html" target="\_blank">📚\</a>\</td>

            \<td \_>\<a href="https\://ysyx.oscc.cc/slides/2407/04.html#/" target="\_blank">📰\</a>\</td>

            \<td \_>\<a href="https\://www\.bilibili.com/video/BV17Lx6zREH6" target="\_blank">🎬\</a>\</td>

            \<td x>\</td> \<td x>\</td> \<td x>\</td> \<td \_>\</td>

        \</tr>

        \<tr class="Stage-F">

            \<td>F5\</td> \<td task>Простой процессор с поддержкой суммирования последовательности\</td> \<td>5\</td>

            \<td \_>\<a href="2607/f/5.html" target="\_blank">📚\</a>\</td>

            \<td \_>\<a href="https\://ysyx.oscc.cc/slides/2407/05.html#/" target="\_blank">📰\</a>\</td>

            \<td \_>\<a href="https\://www\.bilibili.com/video/BV1YgxCzdEvq" target="\_blank">🎬\</a>\</td>

            \<td \_>\</td> \<td x>\</td> \<td x>\</td> \<td \_>\</td>

        \</tr>

        \<tr class="Stage-F">

            \<td>F6\</td> \<td task>Простой базовый ввод-вывод\</td> \<td>5\</td>

            \<td \_>\<a href="2607/f/6.html" target="\_blank">📚\</a>\</td>

            \<td \_> - \</td>

            \<td \_> - \</td>

            \<td \_>\</td> \<td \_>\</td> \<td x>\</td> \<td \_>\</td>

        \</tr>

        \<tr class="Achievement">

            \<td colspan="11">\<a href="2607/f/7.html" target="\_blank">\<i class="fa fa-flag">\</i> Подготовка к tapeout этапа F\</a>\</td>

        \</tr>

        \<tr class="Stage-E">

            \<td stage-title rowspan="8">Этап E\</td>

            \<td>E1\</td> \<td task>Язык описания аппаратуры\</td> \<td>20\</td>

            \<td \_>\<a href="2607/e/1.html" target="\_blank">📚\</a>\</td>

            \<td \_> - \</td>

            \<td \_> - \</td>

            \<td \_>\</td> \<td \_>\</td> \<td x>\</td> \<td \_>\</td>

        \</tr>

        \<tr class="Stage-E">

            \<td>E2\</td> \<td task>Программирование на языке C\</td> \<td>20\</td>

            \<td \_>\<a href="2607/e/2.html" target="\_blank">📚\</a>\</td>

            \<td \_> - \</td>

            \<td \_> - \</td>

            \<td x>\</td> \<td \_>\</td> \<td \_>\</td> \<td \_>\</td>

        \</tr>

        \<tr class="Stage-E">

            \<td>E3\</td> \<td task>Установка Linux и основы использования системы\</td> \<td>10\</td>

            \<td \_>\<a href="2607/e/3.html" target="\_blank">📚\</a>\</td>

            \<td \_>\<a href="https\://ysyx.oscc.cc/slides/2407/06.html#/" target="\_blank">📰\</a>\</td>

            \<td \_>\<a href="https\://www\.bilibili.com/video/BV1wD4xzbEpU" target="\_blank">🎬\</a>\</td>

            \<td \_>\</td> \<td \_>\</td> \<td \_>\</td> \<td x>\</td>

        \</tr>

        \<tr class="Stage-E">

            \<td>E4\</td> \<td task>Симуляция и верификация процессора\</td> \<td>5\</td>

            \<td \_>\<a href="2607/e/4.html" target="\_blank">📚\</a>\</td>

            \<td \_> - \</td>

            \<td \_> - \</td>

            \<td x>\</td> \<td x>\</td> \<td x>\</td> \<td x>\</td>

        \</tr>

        \<tr class="Stage-E">

            \<td>E5\</td> \<td task>Полнофункциональный мини-процессор RISC-V\</td> \<td>5\</td>

            \<td \_>\<a href="2607/e/5.html" target="\_blank">📚\</a>\</td>

            \<td \_> - \</td>

            \<td \_> - \</td>

            \<td x>\</td> \<td x>\</td> \<td x>\</td> \<td \_>\</td>

        \</tr>

        \<tr class="Stage-E">

            \<td>E6\</td> \<td task>Простая среда выполнения\</td> \<td>5\</td>

            \<td \_>\<a href="2607/e/6.html" target="\_blank">📚\</a>\</td>

            \<td \_> - \</td>

            \<td \_> - \</td>

            \<td x>\</td> \<td \_>\</td> \<td \_>\</td> \<td \_>\</td>

        \</tr>

        \<tr class="Stage-E">

            \<td>E7\</td> \<td task>Простая шина и SoC\</td> \<td>5\</td>

            \<td \_>\<a href="2607/e/7.html" target="\_blank">📚\</a>\</td>

            \<td \_> - \</td>

            \<td \_> - \</td>

            \<td \_>\</td> \<td \_>\</td> \<td x>\</td> \<td \_>\</td>

        \</tr>

        \<tr class="Stage-E">

            \<td>E8\</td> \<td task>Синтез и физическое проектирование\</td> \<td>5\</td>

            \<td \_>\<a href="2607/e/8.html" target="\_blank">📚\</a>\</td>

            \<td \_> - \</td>

            \<td \_> - \</td>

            \<td \_>\</td> \<td \_>\</td> \<td x>\</td> \<td \_>\</td>

        \</tr>

        \<tr class="Achievement">

            \<td colspan="11">\<a href="2607/e/9.html" target="\_blank">\<i class="fa fa-flag">\</i> Подача заявки на защиту предварительного обучения\</a>\</td>

        \</tr>

        \<tr class="Stage-D">

            \<td stage-title rowspan="13">Этап D\</td>

            \<td rowspan="2">D1\</td> \<td task>От C к бинарному коду\</td> \<td rowspan="2">10\</td>

            \<td \_ rowspan="2">\<a href="2607/d/1.html" target="\_blank">📚\</a>\</td>

            \<td \_>\<a href="https\://ysyx.oscc.cc/slides/2407/07.html#/" target="\_blank">📰\</a>\</td>

            \<td \_>\<a href="https\://www\.bilibili.com/video/BV1TtWYz2Eun" target="\_blank">🎬\</a>\</td>

            \<td x>\</td> \<td x>\</td> \<td \_>\</td> \<td \_>\</td>

        \</tr>

        \<tr class="Stage-D">

            \<td task>Выполнение C-программы\</td>

            \<td \_>\<a href="https\://ysyx.oscc.cc/slides/2407/08.html#/" target="\_blank">📰\</a>\</td>

            \<td \_>\<a href="https\://www\.bilibili.com/video/BV189svz8ET5" target="\_blank">🎬\</a>\</td>

            \<td x>\</td> \<td \_>\</td> \<td \_>\</td> \<td \_>\</td>

        \</tr>

        \<tr class="Stage-D">

            \<td>D2\</td> \<td task>Простой инструмент отладки, SDB\</td> \<td>20\</td>

            \<td \_>\<a href="2607/d/2.html" target="\_blank">📚\</a>\</td>

            \<td \_>\<a href="https\://ysyx.oscc.cc/slides/2407/15.html#/" target="\_blank">📰\</a>\</td>

            \<td \_>\<a href="https\://www\.bilibili.com/video/BV1bc2YB9Ehi" target="\_blank">🎬\</a>\</td>

            \<td x>\</td> \<td \_>\</td> \<td \_>\</td> \<td x>\</td>

        \</tr>

        \<tr class="Stage-D">

            \<td>D3\</td> \<td task>Архитектура набора инструкций RISC-V\</td> \<td>5\</td>

            \<td \_>\<a href="2607/d/3.html" target="\_blank">📚\</a>\</td>

            \<td \_>\<a href="https\://ysyx.oscc.cc/slides/2407/16.html#/" target="\_blank">📰\</a>\</td>

            \<td \_>\<a href="https\://www\.bilibili.com/video/BV1RVmMBaEC6" target="\_blank">🎬\</a>\</td>

            \<td x>\</td> \<td x>\</td> \<td x>\</td> \<td \_>\</td>

        \</tr>

        \<tr class="Stage-D">

            \<td>D4\</td> \<td task>Машинно-уровневое представление программы\</td> \<td>4\</td>

            \<td \_>\<a href="2607/d/4.html" target="\_blank">📚\</a>\</td>

            \<td \_>\<a href="https\://ysyx.oscc.cc/slides/2306/09.html#/" target="\_blank">📰Ч.1\</a>\<br>

                  \<a href="https\://ysyx.oscc.cc/slides/2306/10.html#/" target="\_blank">📰Ч.2\</a>\</td>

            \<td \_>\<a href="https\://www\.bilibili.com/video/BV1ow411275B" target="\_blank">🎬Ч.1\</a>\<br>

                  \<a href="https\://www\.bilibili.com/video/BV19H4y1d7Yi" target="\_blank">🎬Ч.2\</a>\</td>

            \<td x>\</td> \<td x>\</td> \<td \_>\</td> \<td \_>\</td>

        \</tr>

        \<tr class="Stage-D">

            \<td>D5\</td> \<td task>Среда выполнения Abstract Machine\</td> \<td>5\</td>

            \<td \_>\<a href="2607/d/5.html" target="\_blank">📚\</a>\</td>

            \<td \_>\<a href="https\://ysyx.oscc.cc/slides/2306/11.html#/" target="\_blank">📰\</a>\</td>

            \<td \_>\<a href="https\://www\.bilibili.com/video/BV1Vu4y1s73Y" target="\_blank">🎬\</a>\</td>

            \<td x>\</td> \<td \_>\</td> \<td \_>\</td> \<td \_>\</td>

        \</tr>

        \<tr class="Stage-D">

            \<td rowspan="5">D6\</td> \<td task>От RTL-кода до GDS\</td> \<td rowspan="5">20\</td>

            \<td \_ rowspan="5">\<a href="2607/d/6.html" target="\_blank">📚\</a>\</td>

            \<td \_>\<a href="https\://ysyx.oscc.cc/slides/2407/10.html#/" target="\_blank">📰\</a>\</td>

            \<td \_>\<a href="https\://www\.bilibili.com/video/BV1ho1ZBbETt" target="\_blank">🎬\</a>\</td>

            \<td x>\</td> \<td \_>\</td> \<td x>\</td> \<td \_>\</td>

        \</tr>

        \<tr class="Stage-D">

            \<td task>Логический синтез\</td>

            \<td \_>\<a href="https\://ysyx.oscc.cc/slides/2407/11.html#/" target="\_blank">📰\</a>\</td>

            \<td \_>\<a href="https\://www\.bilibili.com/video/BV1SyyFBtE7R" target="\_blank">🎬\</a>\</td>

            \<td \_>\</td> \<td \_>\</td> \<td x>\</td> \<td \_>\</td>

        \</tr>

        \<tr class="Stage-D">

            \<td task>Семантика RTL-синтеза Verilog\</td>

            \<td \_>\<a href="https\://ysyx.oscc.cc/slides/2407/12.html#/" target="\_blank">📰\</a>\</td>

            \<td \_>\<a href="https\://www\.bilibili.com/video/BV1PjyFBmE3Z" target="\_blank">🎬\</a>\</td>

            \<td \_>\</td> \<td \_>\</td> \<td x>\</td> \<td \_>\</td>

        \</tr>

        \<tr class="Stage-D">

            \<td task>Библиотека standard cells\</td>

            \<td \_>\<a href="https\://ysyx.oscc.cc/slides/2407/13.html#/" target="\_blank">📰\</a>\</td>

            \<td \_>\<a href="https\://www\.bilibili.com/video/BV1XAU6BpECX" target="\_blank">🎬\</a>\</td>

            \<td \_>\</td> \<td \_>\</td> \<td x>\</td> \<td \_>\</td>

        \</tr>

        \<tr class="Stage-D">

            \<td task>Физическое проектирование\</td>

            \<td \_>\<a href="https\://ysyx.oscc.cc/slides/2407/14.html#/" target="\_blank">📰\</a>\</td>

            \<td \_>\<a href="https\://www\.bilibili.com/video/BV15ZUzBoEf6" target="\_blank">🎬\</a>\</td>

            \<td \_>\</td> \<td \_>\</td> \<td x>\</td> \<td \_>\</td>

        \</tr>

        \<tr class="Stage-D">

            \<td>D7\</td> \<td task>Инструменты и инфраструктура\</td> \<td>5\</td>

            \<td \_>\<a href="2607/d/7.html" target="\_blank">📚\</a>\</td>

            \<td \_>\<a href="https\://ysyx.oscc.cc/slides/2306/12.html#/" target="\_blank">📰\</a>\</td>

            \<td \_>\<a href="https\://www\.bilibili.com/video/BV1RM411Q7Au" target="\_blank">🎬\</a>\</td>

            \<td \_>\</td> \<td \_>\</td> \<td \_>\</td> \<td x>\</td>

        \</tr>

        \<tr class="Stage-D">

            \<td>D8\</td> \<td task>Добавьте в NPC поддержку RV32E\</td> \<td>5\</td>

            \<td \_>\<a href="2607/d/8.html" target="\_blank">📚\</a>\</td>

            \<td \_>\<a href="https\://ysyx.oscc.cc/slides/2306/13.html#/" target="\_blank">📰\</a>\</td>

            \<td \_>\<a href="https\://www\.bilibili.com/video/BV1rc411f7mK" target="\_blank">🎬\</a>\</td>

            \<td \_>\</td> \<td \_>\</td> \<td x>\</td> \<td x>\</td>

        \</tr>

        \<tr class="Achievement">

            \<td colspan="11">\<a href="2607/d/9.html" target="\_blank">\<i class="fa fa-flag">\</i> Подготовка к tapeout этапа D\</a>\</td>

        \</tr>

        \<tr class="Stage-C">

            \<td stage-title rowspan="5">Этап C\</td>

            \<td>C1\</td> \<td task>ELF-файлы и компоновка\</td> \<td>2\</td>

            \<td \_>\<a href="2607/c/1.html" target="\_blank">📚\</a>\</td>

            \<td \_>\<a href="https\://ysyx.oscc.cc/slides/2306/14.html#/" target="\_blank">📰\</a>\</td>

            \<td \_>\<a href="https\://www\.bilibili.com/video/BV1Ly4y1w7hn" target="\_blank">🎬\</a>\</td>

            \<td x>\</td> \<td x>\</td> \<td \_>\</td> \<td \_>\</td>

        \</tr>

        \<tr class="Stage-C">

            \<td>C2\</td> \<td task>Устройства и ввод-вывод\</td> \<td>10\</td>

            \<td \_>\<a href="2607/c/2.html" target="\_blank">📚\</a>\</td>

            \<td \_>\<a href="https\://ysyx.oscc.cc/slides/2306/15.html#/" target="\_blank">📰\</a>\</td>

            \<td \_>\<a href="https\://www\.bilibili.com/video/BV1sb4y1g7Xu" target="\_blank">🎬\</a>\</td>

            \<td x>\</td> \<td x>\</td> \<td x>\</td> \<td \_>\</td>

        \</tr>

        \<tr class="Stage-C">

            \<td>C3\</td> \<td task>Советы по отладке\</td> \<td>2\</td>

            \<td \_>\<a href="2607/c/3.html" target="\_blank">📚\</a>\</td>

            \<td \_>\<a href="https\://ysyx.oscc.cc/slides/2306/16.html#/" target="\_blank">📰\</a>\</td>

            \<td \_>\<a href="https\://www\.bilibili.com/video/BV1Vz4y1A7Rt" target="\_blank">🎬\</a>\</td>

            \<td \_>\</td> \<td \_>\</td> \<td \_>\</td> \<td x>\</td>

        \</tr>

        \<tr class="Stage-C">

            \<td>C4\</td> \<td task>Шина\</td> \<td>10\</td>

            \<td \_>\<a href="2607/c/4.html" target="\_blank">📚\</a>\</td>

            \<td \_>\<a href="https\://ysyx.oscc.cc/slides/2306/18.html#/" target="\_blank">📰\</a>\</td>

            \<td \_>\<a href="https\://www\.bilibili.com/video/BV1gj411s7ah" target="\_blank">🎬\</a>\</td>

            \<td \_>\</td> \<td x>\</td> \<td x>\</td> \<td \_>\</td>

        \</tr>

        \<tr class="Stage-C">

            \<td>C5\</td> \<td task>Компьютерная система SoC\</td> \<td>30\</td>

            \<td \_>\<a href="2607/c/5.html" target="\_blank">📚\</a>\</td>

            \<td \_>\<a href="https\://ysyx.oscc.cc/slides/2306/19.html#/" target="\_blank">📰Ч.1\</a>\<br>

                  \<a href="https\://ysyx.oscc.cc/slides/2306/20.html#/" target="\_blank">📰Ч.2\</a>\</td>

            \<td \_>\<a href="https\://www\.bilibili.com/video/BV1NC4y1u7K3" target="\_blank">🎬Ч.1\</a>\<br>

                  \<a href="https\://www\.bilibili.com/video/BV1FC4y1k7mP" target="\_blank">🎬Ч.2\</a>\</td>

            \<td x>\</td> \<td x>\</td> \<td x>\</td> \<td \_>\</td>

        \</tr>

        \<tr class="Achievement">

            \<td colspan="11">\<a href="2607/c/6.html" target="\_blank">\<i class="fa fa-flag">\</i> Подготовка к tapeout этапа C\</a>\</td>

        \</tr>

        \<tr class="Stage-B">

            \<td stage-title rowspan="4">Этап B\</td>

            \<td>B1\</td> \<td task>Обработка исключений и простые операционные системы\</td> \<td>15\</td>

            \<td \_>\<a href="2607/b/1.html" target="\_blank">📚\</a>\</td>

            \<td \_>\<a href="https\://ysyx.oscc.cc/slides/2306/17.html#/" target="\_blank">📰\</a>\</td>

            \<td \_>\<a href="https\://www\.bilibili.com/video/BV1734y1w7ro" target="\_blank">🎬\</a>\</td>

            \<td x>\</td> \<td x>\</td> \<td x>\</td> \<td \_>\</td>

        \</tr>

        \<tr class="Stage-B">

            \<td>B2\</td> \<td task>Анализ и оптимизация временных характеристик\</td> \<td>5\</td>

            \<td \_>\<a href="2607/b/2.html" target="\_blank">📚\</a>\</td>

            \<td \_> - \</td>

            \<td \_> - \</td>

            \<td \_>\</td> \<td \_>\</td> \<td x>\</td> \<td \_>\</td>

        \</tr>

        \<tr class="Stage-B">

            \<td>B3\</td> \<td task>Оптимизация производительности и простой кэш\</td> \<td>20\</td>

            \<td \_>\<a href="2607/b/3.html" target="\_blank">📚\</a>\</td>

            \<td \_>\<a href="https\://ysyx.oscc.cc/slides/2306/21.html#/" target="\_blank">📰\</a>\</td>

            \<td \_>\<a href="https\://www\.bilibili.com/video/BV1xr421F7ZP" target="\_blank">🎬\</a>\</td>

            \<td x>\</td> \<td \_>\</td> \<td x>\</td> \<td x>\</td>

        \</tr>

        \<tr class="Stage-B">

            \<td>B4\</td> \<td task>Конвейерный процессор\</td> \<td>20\</td>

            \<td \_>\<a href="2607/b/4.html" target="\_blank">📚\</a>\</td>

            \<td \_>\<a href="https\://ysyx.oscc.cc/slides/2306/22.html#/" target="\_blank">📰\</a>\</td>

            \<td \_>\<a href="https\://www\.bilibili.com/video/BV1ZRtkeVEqw" target="\_blank">🎬\</a>\</td>

            \<td \_>\</td> \<td \_>\</td> \<td x>\</td> \<td x>\</td>

        \</tr>

        \<tr class="Achievement">

            \<td colspan="11">\<a href="2306/basic/1.11.html" target="\_blank">\<i class="fa fa-flag">\</i> Подготовка к tapeout этапа B\</a>\</td>

        \</tr>

        \<tr class="Stage-A">

            \<td stage-title rowspan="7">Этап A\</td>

            \<td>\</td> \<td task>Умножитель и делитель\</td> \<td>0\</td>

            \<td \_> \</td> \<td \_> \</td> \<td \_> \</td>

            \<!-- окружение       инструменты       цифровая логика        микроархитектура       ПО -->

            \<td \_>\</td> \<td \_>\</td> \<td \_>\</td> \<td \_>\</td>

        \</tr>

        \<tr class="Stage-A">

            \<td>\</td> \<td task>Системные вызовы и приложения\</td> \<td>0\</td>

            \<td \_> \</td> \<td \_> \</td> \<td \_> \</td>

            \<!-- окружение       инструменты       цифровая логика        микроархитектура       ПО -->

            \<td \_>\</td> \<td \_>\</td> \<td \_>\</td> \<td \_>\</td>

        \</tr>

        \<tr class="Stage-A">

            \<td>\</td> \<td task>Управление виртуальной памятью\</td> \<td>0\</td>

            \<td \_> \</td> \<td \_> \</td> \<td \_> \</td>

            \<!-- окружение       инструменты       цифровая логика        микроархитектура       ПО -->

            \<td \_>\</td> \<td \_>\</td> \<td \_>\</td> \<td \_>\</td>

        \</tr>

        \<tr class="Stage-A">

            \<td>\</td> \<td task>Уровни привилегий и xv6\</td> \<td>0\</td>

            \<td \_> \</td> \<td \_> \</td> \<td \_> \</td>

            \<!-- окружение       инструменты       цифровая логика        микроархитектура       ПО -->

            \<td \_>\</td> \<td \_>\</td> \<td \_>\</td> \<td \_>\</td>

        \</tr>

        \<tr class="Stage-A">

            \<td>\</td> \<td task>Загрузка Linux и Debian\</td> \<td>0\</td>

            \<td \_> \</td> \<td \_> \</td> \<td \_> \</td>

            \<!-- окружение       инструменты       цифровая логика        микроархитектура       ПО -->

            \<td \_>\</td> \<td \_>\</td> \<td \_>\</td> \<td \_>\</td>

        \</tr>

        \<tr class="Stage-A">

            \<td>\</td> \<td task>Продвинутый кэш\</td> \<td>0\</td>

            \<td \_> \</td> \<td \_> \</td> \<td \_> \</td>

            \<!-- окружение       инструменты       цифровая логика        микроархитектура       ПО -->

            \<td \_>\</td> \<td \_>\</td> \<td \_>\</td> \<td \_>\</td>

        \</tr>

        \<tr class="Stage-A">

            \<td>\</td> \<td task>Продвинутое предсказание ветвлений\</td> \<td>0\</td>

            \<td \_> \</td> \<td \_> \</td> \<td \_> \</td>

            \<!-- окружение       инструменты       цифровая логика        микроархитектура       ПО -->

            \<td \_>\</td> \<td \_>\</td> \<td \_>\</td> \<td \_>\</td>

        \</tr>

        \<tr class="Achievement">

            \<td colspan="11">\<i class="fa fa-flag">\</i> Подготовка к tapeout этапа A\</td>

        \</tr>

        \<tr class="Stage-S">

            \<td stage-title rowspan="1">Этап S\</td>

            \<td>\</td> \<td task>Продолжение следует...\</td> \<td>0\</td>

            \<td \_> \</td> \<td \_> \</td> \<td \_> \</td>

            \<!-- окружение       инструменты       цифровая логика        микроархитектура       ПО -->

            \<td \_>\</td> \<td \_>\</td> \<td \_>\</td> \<td \_>\</td>

        \</tr>

    \</tbody>

\</table>





\> **#### info::Полоса загрузки страницы зависла？**

\>

\> Если при переходе на новую страницу индикатор загрузки завис более чем на 3 секунды, вероятно, мы только что опубликовали новую версию страницы.\<br>

\> Поскольку мы всё ещё часто обновляем и исправляем документацию, в ближайшее время такие зависания при переходах могут встречаться чаще.\<br>

\> В таком случае просто выполните **\_\_\`refresh\`\_\_**, и можно продолжать обучение!



**## Другие ресурсы**

\* The RISC-V Reader: An Open Architecture Atlas — David Patterson и Andrew Wathelet

\* [Computer Systems: Based on the RISC-V + Linux Platform — под редакцией Yuan Chunfeng, Yu Zihao и Chen Lu]\(https\://product.dangdang.com/29720521.html)

\* [Digital Design and Computer Architecture - Spring 2023, Onur Mutlu\@ETH Zurich]\(https\://safari.ethz.ch/digitaltechnik/spring2023/doku.php?id=schedule)

\* [Шаблон для вопросов]\(../2205/misc/ask.md)

**## История мероприятий**

\* 2025/07/21 - [Летний воркшоп «One Student One Chip» 2025]\(https\://space.bilibili.com/2107852263/lists/5997805?type=season) 

\* 2024/07/14 - [Летний воркшоп «One Student One Chip» 2024]\(https\://space.bilibili.com/2107852263/channel/collectiondetail?sid=3416378)

\* 2023/08/25 - [Форум экосистемы технологий открытых чипов (ранее — технологический форум «One Student One Chip»)]\(../en/events/20230825-2nd-tech-forum.md)

\* 2023/07/02 - [6-я стартовая встреча «One Student One Chip»]\(https\://space.bilibili.com/2107852263/channel/collectiondetail?sid=1497409)

\* 2022/11/20 - [Открытые чипы и гибкое проектирование с точки зрения программной инженерии (Yungang Bao)]\(https\://www\.bilibili.com/video/BV1Dd4y1474D/)

\* 2022/08/28 - [Первый технический форум «One Student One Chip» и пятая стартовая встреча]\(../en/events/20220828-1st-tech-forum.md)

\* 2022/03/12 - [Возможности аппаратно-программной кооперации при проектировании чипов (Yue Jin, Bohan Hu, Zeyu Gao)]\(https\://www\.bilibili.com/video/BV1334y187zC/)