<img align="left" src="https://i.imgur.com/RkjJPEr.png" width="100px">
<br/><br/><br/><br/>

Независимый децентрализованный ISP для наших друзей

## Я — пользователь
Чтобы подключиться к уже существующему узлу сети «Medium», вам необходимо [выбрать свой город](https://github.com/medium-isp/medium/tree/master/ru) и найти ближайшего к вам оператора.

Для подключения необходимо создать новое соединение со следующими параметрами: SSID — «Medium» (без кавычек), тип аутентификации — без пароля.

Будьте бдительны: сеть «Medium» по умолчанию скрыта от посторонних глаз; в списке доступных сетей она не будет отображаться до тех пор, пока Вы не создадите новое соединение с вышеприведёнными параметрами.

Чтобы проверить работоспособность сети, попробуйте посетить страницу [medium.i2p](http://medium.i2p/?i2paddresshelper=dLJzgrK601vSbtNZGQ~R8V0ruRsdeG35gaIdH0RkXzoFioASVww8YociZfrgLsnHmKmMfA46fFv6goHkWYLMcWCDqoNc1X1bUzJwNxGHDcJJ1svKCuMGJDm5Ve~UMkdqEWofeT4tc4F14dJE48ff10jM4Y3Zc1tJCBuXKwtwa~mAdSacDlowXABP3kQ76kpMqQZ6dAithyAi53u-USvTmpK0Lc4uvZsWQL32m~qGMEiNrrlAhHZY2ttPbPUq8ig1bhEoBkN9CEYDdEgH3mw9CNmIhUrQThD9Hp~Wlsvd1x0815U-DDPqQvbwj2KgVRRt4z0uvZ-Ol0gpJwSgXfovVmuGj-PjbzFlfe-oGB-hQWEM~rTvIGdoS09nyWZtzzEQMnOwxv72fEM7HVQbMzSQ3B2UMHDWcXaY~lmQNnXcvNPMZiWA9Qt0ogUdWzDMyz1OvK5hsUPOLEYJMQ7GS272Mx3E6fqGct2EJ20IDIY8MfMVvCzYOK58lvTqeEsAz-fRBQAEAAcAAA==) после подключения.

## Я — оператор
Чтобы поднять свой узел сети «Medium», вам необходимы следующие вещи:
* Доступ к сети Интернет
* Свободный маршрутизатор
* Свободное время и энтузиазм

### Шаг 1. Подключение к сети I2P
Сперва-наперво вам нужно подключиться к сети I2P. Сделать это можно при помощи [i2pd](https://github.com/PurpleI2P/i2pd/wiki/Using-i2pd).

### Шаг 2. Раздача слонов
После того, как будет произведено подключение, вам необходимо сконфигурировать ваш беспроводной маршрутизатор таким образом, чтобы весь трафик шёл через прокси, расположенный на сервере, где был поднят сервис i2pd. Предполагается, что он развёрнут в локальной домашней сети. Например, 192.168.0.1:4444.

Обратите особое внимание на то, что для аутентичности сеть должна обладать следующими параметрами: SSID — Medium, пароля нет, сеть скрыта.

### Шаг 3. Блокировка трафика
В зависимости от модели вашего маршрутизатора, запретите любой трафик, который так или иначе относится ко внешнему Интернету.

### Шаг 4. Добавление точки в публичный список
После завершения настройки вашей точки доступа и проверки её работоспособности вы можете добавить её в [публичный список](https://github.com/medium-isp/medium/blob/master/CONTRIBUTING.md).
