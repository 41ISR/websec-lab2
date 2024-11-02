# Cross Site Scripting (XSS)

## Срок выполнения задания

07.11.2024 00:00

## Алгоритм выполнения

1. Создайте форк репозитория в организации `41ISR` с названием `websec-lab2-вашафамилия`
2. Используя ветку `wip` измените файл `payloads.md`, где будут указываться методы по эксплуатации XSS
3. Зафиксируйте изменения в вашем репозитории
4. Когда задание будет выполнено - создайте пул реквест из ветки `wip` на ветку `main` и укажите меня ([ktkv419](https://github.com/ktkv419)) как reviewer

## Задание

1. Перейти на ресурс [gruyer](https://google-gruyere.appspot.com/start) и запустить сервис по кнопке `Agree and start`

2. Найти все XSS уязвимосте на портале

_Оцениваться будет полнота описания уязвимости, а также их количество_

## Подсказки

<details> 
  <summary>HINT1: </summary>
    Вы можете загружать HTML-файлы, а HTML-файлы могут содержать script тэг
</details>

<details> 
  <summary>HINT2: </summary>
    Интересно, а как выглядит страница 404?
</details>

<details> 
  <summary>HINT3: </summary>
    Snippet - хорошее место для хранения вашего HTML кода
</details>

<details> 
  <summary>HINT4: </summary>
    Посмотрите на то, как задается код цвета. Можно ли выбраться из строки указания цвета и написать свои атрибуты?
</details>
