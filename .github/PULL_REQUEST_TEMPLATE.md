# Добавление точки «Medium» в публичный список

В том случае, если вы уже являетесь оператором действующей точки «Medium», вы можете создать новый [PR](https://github.com/medium-isp/medium/pulls) на добавление её в публичный список всех точек сети.

Структура реестра выглядит следующим образом: [номер региона]/[название города латиницей]/README.md.

Список кодов субъектов Российской Федерации можно найти [здесь](https://ru.wikipedia.org/wiki/%D0%9A%D0%BE%D0%B4%D1%8B_%D1%81%D1%83%D0%B1%D1%8A%D0%B5%D0%BA%D1%82%D0%BE%D0%B2_%D0%A0%D0%BE%D1%81%D1%81%D0%B8%D0%B9%D1%81%D0%BA%D0%BE%D0%B9_%D0%A4%D0%B5%D0%B4%D0%B5%D1%80%D0%B0%D1%86%D0%B8%D0%B8).

[Пример оформления](https://pastebin.com/raw/pPa0VQJA)

| Номер узла | Доступность | Широта  | Долгота | URL |
|:----------:|:-----------:|:-------:|:-------:|:---:|
| 1         | ![](https://img.shields.io/badge/доступен-success.svg)   | 54.860651 | 38.536462 | [Google Maps](https://www.google.com/maps/place/54°51'38.3"N+38°32'11.3"E)

Чтобы PR был одобрен, необходимо соблюсти следующие условия:

* Заполнено поле **Номер узла**, которое отвечает за порядковый номер точки в списке
* Правильно указан статус в поле **Доступность** (доступна — доступна в данный момент, недоступна — была доступна ранее, но в настоящий момент недоступна; обновляется — будет доступна в ближайшее время)
* Заполнены поля **Широта** и **Долгота**
* Добавлена прямая ссылка на [Google Maps](https://maps.google.com) или [Yandex Maps](https://maps.yandex.ru) в поле **URL**

Вы также можете добавить запись `medium.i2p,mediumsqsqgxwwhioefin4qu2wql4nybk5fff7tgwbg2f6bgkboa.b32.i2p ([addresshelper](http://medium.i2p/?i2paddresshelper=dLJzgrK601vSbtNZGQ~R8V0ruRsdeG35gaIdH0RkXzoFioASVww8YociZfrgLsnHmKmMfA46fFv6goHkWYLMcWCDqoNc1X1bUzJwNxGHDcJJ1svKCuMGJDm5Ve~UMkdqEWofeT4tc4F14dJE48ff10jM4Y3Zc1tJCBuXKwtwa~mAdSacDlowXABP3kQ76kpMqQZ6dAithyAi53u-USvTmpK0Lc4uvZsWQL32m~qGMEiNrrlAhHZY2ttPbPUq8ig1bhEoBkN9CEYDdEgH3mw9CNmIhUrQThD9Hp~Wlsvd1x0815U-DDPqQvbwj2KgVRRt4z0uvZ-Ol0gpJwSgXfovVmuGj-PjbzFlfe-oGB-hQWEM~rTvIGdoS09nyWZtzzEQMnOwxv72fEM7HVQbMzSQ3B2UMHDWcXaY~lmQNnXcvNPMZiWA9Qt0ogUdWzDMyz1OvK5hsUPOLEYJMQ7GS272Mx3E6fqGct2EJ20IDIY8MfMVvCzYOK58lvTqeEsAz-fRBQAEAAcAAA==)) в адресную книгу своего I2P маршрутизатора, чтобы ваши клиенты имели возможность проверить соединение с сетью I2P путём посещения сайта [medium.i2p](http://medium.i2p).

Чтобы запретить пользователям добавлять произвольные addresshelper-адреса, в настройках туннеля (http://127.0.0.1:7657/i2ptunnelmgr), в раздел `custom options` добавьте следующую строку: `i2ptunnel.httpclient.disableAddressHelper = true`.

В том случае, если вы используете i2pd, добавьте `addresshelper = false` в `i2pd.conf`.
