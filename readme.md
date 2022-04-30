# Исправления 
## YAGNI
* Удалена анимация кнопок при нажатии
## KISS
* Параметры <iframe> перенесены в CSS (строки 103 и 448 HTML). 
* Удален класс .decortion__fix-container (стока 291 HTML). Используем вложенность элементов в класс.
## DRY
* Удалено свойство "color" из нескольких классов (.header-tel, .header-menu__link, .home-content, .title, .header-logo - удален) избегаем повторения. Вместо этого для окраски текста, там где требуется используются отдельные классы "white-text" или "yellow-text"
## BEM
* Переимнованы, например,  кнопки: 
   button_request на header__button , т.к. это элемент
   buttom-main на main__button, т.к. это элемент
   button-transparent на main__button_transporent, т.к. это состояние эл-та
## W3C
* Изменены устаревшие атрибуты <iframe>
* Ссылкам добавлены атрибуты "alt"
## Линтеры
* Сделано форматирование HTML и CSS по Beautify 