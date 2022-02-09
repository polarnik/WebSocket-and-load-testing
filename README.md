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
</details>

### Fiddler Classic + Custom Script
<details>
</details>

### Charles Proxy
<details>
</details>

### Fiddler Everywhere
<details>
</details>

## 2. Инструменты отправки и чтения сообщений WebSocket

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
