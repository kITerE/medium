<br/>
<img align="left" src="https://i.imgur.com/M5T1BL9.png">  
<br/><br/>

[README in English](README.en.md) • [README на русском](README.ru.md) • [README en français](README.fr.md)

<h2>Что это?</h2>
Проект «Medium» изначально задумывался как <a href="https://en.wikipedia.org/wiki/Mesh_networking">Mesh-сеть</a> в <a href="https://ru.wikipedia.org/wiki/Коломенский_городской_округ">Коломенском городском округе</a>, однако спустя некоторое время сталось весьма очевидным то, что для реализации задумки недостаточно желающих принять в этом участие.
<br/><br/>
По этой причине спустя некоторое время «Medium» превратился в независимого и бесплатного поставщика услуг доступа к сети I2P — энтузиасты настраивают свои беспроводные точки доступа так, чтобы при подключении к ним становилось возможным использование ресурсов проекта I2P.
<br/><br/>
С точки зрения безопасности такой подход имеет некоторые фундаментальные недостатки — например, можно свободно прослушивать трафик между абонентом и маршрутизатором, к которому он в данный момент подключен. Следует отметить тот факт, что и <a href="https://en.wikipedia.org/wiki/Tor_(anonymity_network)">Tor</a> обладает схожей проблемой — только в отношении <a href="https://hackertarget.com/tor-exit-node-visualization/">выходных узлов</a>.
<br/><br/>
Нивелируется эта проблема использованием транспортного уровня обеспечения безопасности — <a href="https://en.wikipedia.org/wiki/Transport_Layer_Security">TLS</a>, <a href="https://ru.wikipedia.org/wiki/SSL">SSL</a>, <a href="https://en.wikipedia.org/wiki/HTTPS">HTTPS</a>, <a href="https://ru.wikipedia.org/wiki/%D0%9A%D1%80%D0%B8%D0%BF%D1%82%D0%BE%D0%B3%D1%80%D0%B0%D1%84%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B9_%D0%BF%D1%80%D0%BE%D1%82%D0%BE%D0%BA%D0%BE%D0%BB">et cetera</a> — этого вполне достаточно для того, чтобы чувствовать себя уверенным при использовании ресурсов сети. Ну и, конечно же, не следует забывать про <a href="https://en.wikipedia.org/wiki/Pretty_Good_Privacy">PGP</a> и принципы работы асимметричной криптографии при обмене сообщениями.
<br/><br/>
Благодаря использованию I2P становится невозможным вычисление не только маршрутизатора, откуда пришёл трафик (см. <a href="https://en.wikipedia.org/wiki/Garlic_routing">основные принципы работы «чесночной» маршрутизации трафика</a>), но и конечного пользователя — абонента «Medium».
<br/><br/>
Как приятный бонус — невозможность блокировки сети и доступа к вычислительным ресурсам её участников — для этого необходимо ограничить работу всего интернета на физическом уровне. Выключить и больше не включать.
<br/><br/>
С юридической точки зрения (в соответствии с <a href="www.consultant.ru/document/cons_doc_LAW_162586/">Федеральным законом № 97-ФЗ от 5 мая 2014 г.</a>), находящийся на территории РФ, «Medium» пусть бы частично и попадает под введённые законом ограничения, но здесь имеет смысл принять во внимание следующие нюансы:
<br/><br/>
<ol><li>«Medium» — не юридическое лицо; каждый участник является автономным ISP с одноимённым названием;</li>
	<li>Точки доступа к «Medium» пусть бы и открыты (не имеют пароля для подключения по умолчанию), но скрыты: человек, не знающий названия сети, подключиться к ней не будет иметь возможности;</li>
	<li>«Medium» предоставляет доступ к сети I2P, а не Интернет (хотя бы и имеется возможность выхода в сеть через outproxy — на усмотрение действующего оператора «Medium»; по этой же причине «Medium» можно смело называть ISP).</li></ol>
<h2>Зачем это?</h2>
Мы верим в то, что Интернет должен быть политически нейтральным и свободным — те принципы, исходя из которых была построена всемирная сеть, — не выдерживают никакой критики. <a href="https://www.vanityfair.com/news/2018/07/the-man-who-created-the-world-wide-web-has-some-regrets">Они устарели</a>. <a href="https://lifehacker.com/its-no-surprise-anymore-your-data-is-never-safe-onlin-1471858210">Они небезопасны</a>. Мы живём в Legacy. Любая централизованная сеть по умолчанию скомпрометирована — и это одна из тех причин, по которым мы развёртываем «Medium».
<br/><br/>
Мы верим в то, что конфиденциальность — одна из тех основ, без которых спокойная и размеренная жизнь человека невозможна.
<br/><br/>
Мы верим в то, что каждый человек имеет право на конфиденциальность и неприкосновенность своих данных.
<br/><br/>
Мы верим в то, что «Medium» сможет оказать посильное содействие развитию сети I2P — ведь с каждой новой поднятой точкой «Medium» появляется и новый транзитный узел в сети I2P.
<h2>Как это?</h2>
Суть децентрализованного ISP «Medium» — предоставить конечному пользователю возможность использования ресурсов сети I2P без непосредственной оплаты интернет-трафика.
<br/><br/>
Концепция ISP «Medium» достаточно прозаична — множество заинтересованных в этом людей поднимают свои беспроводные точки доступа к сети I2P без возможности обозревания интернет-трафика по умолчанию (возможность использования outproxy не возбраняется, но и не приветствуется: «Medium» должен способствовать росту транзитных точек и сайтов в сети I2P). Развёртывание инфраструктуры происходит на безвозмездной основе — чистой воды энтузиазм.
<br/><br/>
В самом начале становления проекта особенное внимание акцентировалось на том, чтобы пользователи могли беспрепятственно использовать ресурсы сети I2P — пусть бы и не совсем так, как задумывалось при создании концепции «невидимого интернета», но всё же в обход парадигм привычного нам интернета — что уже хорошо.
<br/><br/>
И ещё так, чтобы подключение абонента к сети не составляло особенных трудностей: возможность подключения по Wi-Fi сейчас не представляется чем-то сверхъестественным для рядового пользователя.
<br/><br/>
Что мы имеем: волонтёры (системные операторы), которым подконтрольны точки доступа в сеть «Medium» и непосредственно сами абоненты, которые пользуются ресурсами сети. Ввиду того, что I2P использует лишь малую часть пропускной способности общего канала, системным операторам не должно составить труда одновременно держать подключенными к себе до 5-10 абонентов.
<h2>Где это?</h2>
На данном этапе развития «Medium» имеет несколько точек доступа в <a href="https://github.com/medium-isp/medium/tree/master/ru/50/kolomna">Коломне</a>, <a href="https://github.com/medium-isp/medium/tree/master/ru/72/tyumen">Тюмени</a> и одну — в <a href="https://github.com/medium-isp/medium/tree/master/ru/63/samara">Самаре</a>.
<br/><br/>
Мы надеемся на активное содействие сообщества развитию проекта «Medium» — инструкции для того, чтобы поднять свою аутентичную точку, можно найти <a href="https://github.com/medium-isp/medium/blob/master/README.ru.md#%D1%8F--%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%82%D0%BE%D1%80">здесь</a>. Там же можно и отправить PR на добавление своей точки в публичный список всех точек сети.
<h2>Я хочу стать волонтёром! Что мне нужно для этого сделать?</h2>
Поднимите свою <a href="https://github.com/medium-isp/medium/blob/master/README.ru.md#%D1%8F--%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%82%D0%BE%D1%80">точку доступа</a> и присоединяйтесь к <a href="https://github.com/medium-isp/medium/issues/1">обсуждению проекта</a>. В этой ветке обсуждаются все наиболее значимые нюансы долгосрочного развития сети «Medium».
<br/><br/>
Если вы уже являетесь оператором действующей точки «Medium», не забудьте создать <a href="https://github.com/medium-isp/medium/pulls">Pull Request</a>, чтобы добавить вашу точку в публичный список всех точек сети. <a href="https://github.com/medium-isp/medium/blob/master/CONTRIBUTING.md">Здесь</a> вы можете найти полезную информацию о том, как необходимо оформлять PR.
<br/><br/>
<a href="https://github.com/medium-isp/medium/tree/master/ru">Список всех точек сети</a> • <a href="https://github.com/medium-isp/medium/blob/master/README.ru.md#%D1%8F--%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%82%D0%BE%D1%80">Инструкции по настройке своей AP</a> • <a href="https://github.com/medium-isp/medium/blob/master/CONTRIBUTING.md">Добавление своей точки в список</a>
