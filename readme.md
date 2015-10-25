﻿# Техническое задание на вёрстку

* Название сайта: Барбершоп «Бородинский»
* Домен: пока нет

——

## Общие технические требования

— Стандарты вёрстки: HTML5, CSS3, прогрессивное улучшение.
— Сетка: определена в макете.
— Адаптивность вёрстки: нет.
— Используемые фреймворки: нет.
— Кроссбраузерность: IE10+, Chrome, Firefox, Opera, Safari.
— Типографика: частично определена в макете (прочее — на усмотрение разработчика).
— Используемые шрифты: PT Sans Narrow (есть на google.com/fonts).
— С макетом предоставлен styleguide.psd, содержащий прорисовку состояний элементов интерфейса. При любых расхождениях с макетами он должен иметь наивысший приоритет.

### Пояснения для учащихся:

— Часть макетов не включена в задание, дабы не усложнять его. Когда упомянуты страницы или элементы, отсутствующие в макетах, даны пояснения «макета нет, не делать». Такие элементы (модальное окно с фотографией, страница новостей и прочие) верстать не нужно.
— В макетах есть скрытые слои с всплывающими окнами. Такие слои в блоке слоёв фотошопа выделены красным цветом.
— Макеты верстаются постепенно, не нужно сразу выполнять все требования.

### Пожелания к поведению блоков

Все макеты:

— Контентная область центрируется и не может быть уже макетной ширины.
— По клику на ссылку «вход» открывается модальное окно авторизации (смотрите папку слоёв «log in form» в barbershop-index.psd).
— В блоке с хлебными крошками активная страница (последний пункт) не является ссылкой и не реагирует на наведение.
— В пагинации активная страница не является ссылкой и не реагирует на наведение.
— Нижняя часть страницы: предусмотрите появление ещё одной социальной кнопки.
— Все кнопки в покое чёрные, по наведению меняют фоновый цвет — смотрите styleguide.psd.

barbershop-index.psd:

— Логотип не является ссылкой.
— Новостей может быть больше двух.
— Картинки в фотогалерее — это ссылка, по клику открывается модальное окно с фотографией (макета нет, не делать).

barbershop-price.psd:

— Добавление текста в контентные блоки не должно ломать страницу.

barbershop-shop.psd:

— Фильтр (блоки «Производители» и «Группы товаров») верстать с помощью формы, кнопка «Показать» отвечает за отправку формы, при выключенном JavaScript должен осуществляться переход на отдельную страницу (отдельную страницу верстать не нужно).
— Количество товаров в правом блоке может быть любым, оно не должно ломать страницу.
— Карточка товара: изображение товара — это ссылка на страницу товара.
— Карточка товара: название товара — это ссылка на страницу товара (название состоит из 2 строк, но по сути является одним блоком).
— Карточка товара: кнопка «Купить» — по клику товар добавляется в корзину (макета корзины нет, не делать).

barbershop-item.psd:

— При клике по миниатюре в галерее изображений большая фотография меняться не должна.

#TODO
— Make snippet for "section" tag - start/end comments
— Tune "Reformat Code" in phpstorm for html
