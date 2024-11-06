# Payloads для gruyere

## Payload 1

При переходе по ссылке `https://https://google-gruyere.appspot.com/584100228911668795158296871158315456069/newaccount.gtl`. Параметр `newaccount.gtl` можно заменить на пейлоад `<script>alert('XSS')</script>` для вывода окна с надписью XSS

## Payload 2

При переходе по ссылке `https://https://google-gruyere.appspot.com/584100228911668795158296871158315456069/newaccount.gtl`. Параметр `newaccount.gtl` можно заменить на пейлоад `<h1>xss script</h1>` для на странице с надписью 
xss script

## Payload 3

Если изменить ссылку `https://google-gruyere.appspot.com/491477625358089430594825549379028845597/newsnippet2?snippet=snippet` на `https://google-gruyere.appspot.com/491477625358089430594825549379028845597/newsnippet2?snippet=update+snippet`, то добавится новый сниппет

## Payload 4

При регистрации с последующим входом, на странице Home в адресной строке видно имя пользователя и его пароль. `https://google-gruyere.appspot.com/442299778806942197550060258560642440457/login?uid=lolo&pw=123`

## Payload 5

При загрузке на сайт фала .html с кодом `<script>document.cookie = "user=John"</script> <script>alert(document.cookie)</script>` сайт показывает файлы куки `user=John; GRUYERE=105914550|lolo||author; GRUYERE_ID=442299778806942197550060258560642440457`

## Payload 6

В редактировании профиля в поле "цвет профиля" вставить red' onload='alert(1)' onmouseover='alert("2"), то  на домашней странице при наведении имя пользователя выводится окно со значением 2


