# Payloads для gruyere

_Пример оформления работы_

## Payload 1

При переходе по ссылке `https://https://google-gruyere.appspot.com/584100228911668795158296871158315456069/newaccount.gtl`. Параметр `newaccount.gtl` можно заменить на пейлоад `<script>alert('XSS')</script>` для вывода окна с надписью XSS

## Payload 2

При переходе по ссылке `https://https://google-gruyere.appspot.com/584100228911668795158296871158315456069/newaccount.gtl`. Параметр `newaccount.gtl` можно заменить на пейлоад `<h1>xss script</h1>` для на странице с надписью 
xss script

## Payload 3

Если изменить ссылку `https://google-gruyere.appspot.com/491477625358089430594825549379028845597/newsnippet2?snippet=snippet` на `https://google-gruyere.appspot.com/491477625358089430594825549379028845597/newsnippet2?snippet=update+snippet`, то добавится новый сниппет
