# Заметки про пройденному курсу

## Стилизация

Все так же как и в обычном реакте, можно использовать modules.

## Маршрутизация

Маршрутизация выполняется с помощью папок и подпапок.
К примеру содержимое папки `app/dashboard` в браузере 
открываем по такому url 
```code
  http://192.168.0.103:3000/dashboard/
```

В папках должен обязательно быть файл page.tsx чтобы папка стала маршрутом.
Дополнительно может находиться файл `layout.tsx` - это что-то типа обертки 
для всех подстраниц. То есть все что у них общее выводим сюда.

## Навигация

Используя обычную ссылку тега `<a>` происходит полное обновление страницы!
Для плавного перехода используем компонент `<Link/>` он выполняет навигацию 
на стороне клиента.

## Настройка вашей базы данных