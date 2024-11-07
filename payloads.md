# Payloads для gruyere

[100% не рикролл](https://clck.ru/3EMU7t)

## Payload 1

При создании нового сниппета можно написать в нём `<a onmouseover="alert(document.cookie) href='#'">text</a>`, который будет выводит куки при наведении, что позволяет лутать данные.

## Payload 2

При изменении цвета профиля можно задать цвету атрибуты onmouseover `black' onmouseover='alert(682)'`, который при наведении на него будет выводить alert. 

## Payload 3

При изменении профиля можно написать url в icon `https://google-gruyere.appspot.com/509870841862400053734264954502968465848/deletesnippet?index=0 `, который позволяет удалять сниппеты.

## Payload 4

В приват сниппет можно написать любой html тег например `<img src=x onerror=alert('XSS')>`, что выведит alert на странице.

## Payload 5

В изменении иконки профиля можно вставить html тег img `<img%20src="javascript:alert(document.cookie);"></img>` - alert вывелся.

## Payload 6

В изменении профиля можно указать ссылку на homepage, но туда еще можно картинку запихнуть умом `<img src=x onerror=alert(1)>` и за место вывода алерта(1) можно вывести куки файлы или что еще похуже.
