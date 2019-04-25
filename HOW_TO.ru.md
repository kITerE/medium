# Добавление точки «Medium» в публичный список

В том случае, если вы уже являетесь оператором действующей точки «Medium», вы можете создать новый [PR](https://github.com/medium-isp/medium/pulls) на добавление её в публичный список всех точек сети.

Структура реестра выглядит следующим образом: [номер региона]/[название города латиницей]/README.md.

Список кодов субъектов Российской Федерации можно найти [здесь](https://ru.wikipedia.org/wiki/%D0%9A%D0%BE%D0%B4%D1%8B_%D1%81%D1%83%D0%B1%D1%8A%D0%B5%D0%BA%D1%82%D0%BE%D0%B2_%D0%A0%D0%BE%D1%81%D1%81%D0%B8%D0%B9%D1%81%D0%BA%D0%BE%D0%B9_%D0%A4%D0%B5%D0%B4%D0%B5%D1%80%D0%B0%D1%86%D0%B8%D0%B8).

[Пример оформления](https://pastebin.com/raw/41MMD4Km)

| Point No. | Availability | Latitude  | Longitude | URL
| --------- | ------------ | --------- | --------- | ---
| 1         | ![](https://img.shields.io/badge/status-available-success.svg)            | 53.211639 | 50.157554 | [Google Maps](https://www.google.com/maps/place/53°12'41.9"N+50°09'27.2"E)

Чтобы PR был одобрен, необходимо соблюсти следующие условия:

* Заполнено поле **Point No.**, которое отвечает за порядковый номер точки в списке
* Правильно указан статус в поле **Availability** (available — доступна в данный момент, unavailable — была доступна ранее, но в настоящий момент недоступна; pending — будет доступна в ближайшее время)
* Заполнены поля **Latitude** (широта) и **Longitude** (долгота)
* Добавлена прямая ссылка на [Google Maps](https://maps.google.com) / [Yandex Maps](https://maps.yandex.ru) / etc.

Вы также можете добавить запись `medium.i2p,f26brxp77ydqc7cnjctnj75ktcgjhh3tqqvrgf4a6l25aqk3vp3a` ([addresshelper](http://medium.i2p/?i2paddresshelper=M0qaNrIGMMyK4WQmtU3D1hxfUhfaWme7ofEvB3B4Lh8tHUnSUwh57JF8FBnGm6kbrYW7zUxqxMs1VLyFIkEF6fBN9vCE4HS~G35e45-GB9O-n1wbfURAkRFYEuIOmpgNWXvbK~zRkXl2eAixDeNT2oW~VC0g385ZWLnq0MZxNKjoQBdB2zpzYNdYON7QGCQWk~l9plmtIevwQCUmlKEpgNt-qB9-MR8ckLGF0ONwnG~vZXA2-m~WcIPrUPgsmIjxO79mR9NvO0pE8qxKkrkhGIFCsFahTESrF2i2G6uuUPk5CRhz~Kc9lCJPIAsWHdjABUDUulM4EBUQPVG00ayzgvYbsxMdSI9PShK0hdvWonWtAjMwPWoZB3PW3m0l1jylPRnAYmwwQVjM6nq~XuRveEeDkgvx0Eq9cdTvP5p5doKPy3A7BN9GvJxrWe8uFcB32aU-HBCIsUQWaF7UVudeTJGcFTuMrxl00Crs2JdDANZpj59ufry57cHt8UcMFARBBQAEAAcAAA==)) в адресную книгу своего I2P маршрутизатора, чтобы ваши клиенты имели возможность проверить соединение с сетью I2P путём посещения сайта [medium.i2p](http://medium.i2p).

Чтобы запретить пользователям добавлять произвольные addresshelper-адреса, в настройках туннеля (http://127.0.0.1:7657/i2ptunnelmgr), в раздел `custom options` добавьте следующую строку: `i2ptunnel.httpclient.disableAddressHelper = true`.

В том случае, если вы используете i2pd, добавьте `addresshelper = false` в `i2pd.conf`.
