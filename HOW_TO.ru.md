# Добавление точки «Medium» в публичный список

В том случае, если вы уже являетесь оператором действующей точки «Medium», вы можете создать новый [PR](https://github.com/medium-isp/medium/pulls) на добавление её в публичный список всех точек сети.

[Пример оформления](https://pastebin.com/raw/41MMD4Km).

| Point No. | Availability | Latitude  | Longitude | URL
| --------- | ------------ | --------- | --------- | ---
| 1         | ![](https://img.shields.io/badge/status-available-success.svg)            | 53.211639 | 50.157554 | [Google Maps](https://www.google.com/maps/place/53°12'41.9"N+50°09'27.2"E)

Чтобы PR был одобрен, необходимо соблюсти следующие условия:

* Заполнено поле **Point No.**, которое отвечает за порядковый номер точки в списке
* Правильно указан статус в поле **Availability** (available — доступна в данный момент, unavailable — была доступна ранее, но в данный момент недоступна, pending — будет доступна в ближайшее время)
* Заполнены поля **Latitude** (широта) и **Longitude** (долгота)
* Добавлена прямая ссылка на [Google Maps](https://maps.google.com) / [Yandex Maps](https://maps.yandex.ru) / etc.
