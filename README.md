# TEST-SPA

login: test@mail.ru
password: TestPassword123_

SPA должно содержать следующие элементы:
1. Форму логина с валидацией полей(проверка мейла, проверка пароля(не менее 7 символов, содержащих только латинские буквы верхнего и нижнего регистров и цифры, но без спец. символов, кроме "_"). В форме логина показ сообщения об ошибках не должен приводить к ресайзу формы.

2. Вкладку "Курсы валют" с возможностью добавить любую валютную пару/пары в "Избранное". Такая валютная пара/пары должны попасть наверх списка в риал-тайм.

3. Вкладку "Конвертер" с возможностью рассчитать, какое количество одной валюты можно купить за другую в рамках имеющихся валютных пар.

4. Вкладку "История" по заданным ниже критериям.
   На вход попадает 100 сделок. Отобразить столько страниц, сколько получится из того набора данных, которые попадают на вход согласно приведённым ниже критериям и по 10 сделок истории на странице.
   В каждой десятке должно быть:
   - не больше 2-х убыточных сделок;
   - сделки отсортированы по дате и времени закрытия в контексте всей истории(вверху ближайшая сделка к текущей даты и времени, и так далее)
   - хотя бы 1-2 сделки с прибыльностью больше 100 долларов
   - не более двух одинаковых активов
Приложение должно быть респонсивным и иметь максимальную скорость работы(как при загрузке приложения, так и при конвертировании валют).
