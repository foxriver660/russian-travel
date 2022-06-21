## #Учебный проект №2: Russian-travel
Сайт доступен по ссылке: **https://foxriver660.github.io/russian-travel/**

В ходе данного учебного проекта подготовлен веб-сайт с отзывчиво-адаптивной функциональностью.

- все элементы страницы хранятся в родительском блоке с установленноймаксимальной шириной.
- CSS файлы разбитые по соответвующим блокам загружаются на файл **_index.css_** при помощи директивы **_@import_**.
- локано использованы шрифты семейства **"inter"**
- веб-сайт состоит из 7 семантических секций, каждая из которых является независимым блоком.
- реализована адаптация веб-страницы по брейкпоинтам в соответствии с дизайн-макетом на точках (1280px, 1024px, 768px, 320px), в промежуточных значениях происходит пропорциональное сжатие блоков и изображений.
- все ссылки на сайте являются активными и перенаправляют на заданные интернет-ресурсы.

---

Использованные технологии:

- файловая структура построена в соотвествии с **_методологией БЭМ_** с применением схемы организации файловой структуры проекта **_Nested_**.
- использована технология **_CSS Flexboх_** и **_CSS Grid_** для создания гибких макетов. С помощью данных технологий созданный веб-сайт обладает отзывчиво-адаптивным дизайном.
- все имеющиеся на сайте ссылки интерактивны и анимированы с помощью **_transition_**.
- все изображения из дизайн-макета выгружены в формате JPEG и сжаты с использованием стороненного ресурса https://tinypng.com/, векторые изображения (SVG) с использованием https://jakearchibald.github.io
- в секции **Cover** реализовано абсолютное позиционирование c использованием псевдоэлемента для реализации полность активной ссылки по клику на изображение.
