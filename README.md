# WebSocket и тесты производительности

## Описание
<details>  
Протокол WebSocket добавил интерактивности веб-приложениям и стал встречаться всё чаще и чаще в работе инженера. С разными сочетаниями протоколов и форматов, например, STOMP + JSON или свой протокол + protobuf.

Я расскажу про инструменты работы с WebSocket.

Как посмотреть отправляемые и получаемые сообщения. Как удобнее измерять длительность процесса, который использует WebSocket. Как изучать взаимосвязи запросов и ответов. Как работать с WebSocket из инструментов нагрузки. Как реализовать поддержку нескольких подключений одновременно.

Вы узнаете про преимущества и недостатки инструментов работы с WebSocket из моего опыта, опыта аудитории и сможете поделиться своей историей
</details>

## 1. Инструменты просмотра и перехват сообщений WebSocket
<details>
  
- Browser / Developer tools / Network 
  - Mozilla Firefox
  - Google Chrome
- Fiddler Classic + WebSocket plugin
- Fiddler Classic + Custom Script
- Charles Proxy
- Fiddler Everywhere

</details>

### Mozilla Firefox / Developer tools / Network
<details>
</details>

### Google Chrome / Developer tools / Network
<details>
</details>

### Fiddler Classic + WebSocket plugin
<details>
  
  - https://github.com/Nezrahm/FiddlerWebSocket (2017)
  - Free
  - Windows, .NET
  
</details>

### Fiddler Classic + Custom Script
<details>
  
  - https://docs.telerik.com/fiddlercore/api/fiddler.websocket
  - https://github.com/polarnik/Fiddler.4.OnWebSocketMessage
  - https://github.com/engineforce/InspectWebSocket
  - Free
  - Windows, .NET
  
</details>

### Charles Proxy
<details>
  
  - https://www.charlesproxy.com/
  - $70 = $60 (one licence) + $10 (tax, 20% NDS)
  
</details>

### Fiddler Everywhere
<details>
  
  - https://www.telerik.com/download/fiddler-everywhere
  - $12 per month = $10 per month (one licence) + $2 (tax, 20% NDS)
  
</details>

### Proxyman
<details>
  
  - https://proxyman.io/
  - $69 = $59 (one standard licence) + ~$10 (tax, 20% NDS)
  
</details>

### Сводная таблица
<details>
</details>

## 2. Замер длительности сценария вручную


## 3. Инструменты отправки и чтения сообщений WebSocket

### Apache.JMeter 5.4.1 + WebSocket plugin by Peter Doornbosch 1.2.8

<details>
  
#### Подключение к WebSocket в Apache.JMeter

#### Отправка сообщения

#### Чтение сообщения

#### ! Ожидание нужного ответа

#### ! Пропуск ненужных ответов

#### Поддержка подключения Ping/Pong

#### Закрытие подключения клиентом

#### ! Обработка ошибки неожиданного закрытия подключения сервером
  
</details>


### Apache.JMeter 5.4.1 + WebSocket plugin by Peter Doornbosch 1.2.8 (с поддержкой нескольких подключений)

<details>

#### ! Сборка плагина

#### ! Добавление плагина в проект с jmeter-maven-plugin 2.9.*

#### Активация поддержки нескольких подключений

#### Указание имени подключения

#### Подключение к WebSocket с указанием имени сокета

#### Отправка сообщения с указанием имени сокета

#### Чтение сообщения с указанием имени сокета

</details>

### Gatling 3.7.4

<details>

#### Подключение к WebSocket с указанием имени сокета

#### Отправка сообщения с указанием имени сокета

#### Чтение сообщения с указанием имени сокета

</details>


## 4. Автоматизация записи сценария с WebSocket

<details>
</details>

  
## 5. Итоги

<details>
</details>

## Поговорить

- Web Application Firewall + WebSocket
- WSS WebSocket Security
