---
title: Mobile 
weight: 1
---

### Удалённое управление
------

Введите ID удалённого устройства на главной странице или выберите устройство из списка недавних подключений.
После успешной верификации вы можете управлять удалённым устройством.

| Главная страница | Успешное подключение |
| --------------- | -------------------------------------------------------- |
| ![](/docs/en/manual/mobile/images/connection_home_en.jpg?width=300px) | ![](/docs/en/manual/mobile/images/connection_en.jpg?width=300px) |


Доступны два режима ввода `mouse mode`/`touch mode` между которыми можно переключаться на нижней панели инструментов.

| Кнопка | Выбор режима |
| --------------- | -------------------------------------------------------- |
| ![](/docs/en/manual/mobile/images/touch_mode_icon_en.png?width=300px) | ![](/docs/en/manual/mobile/images/touch_mode_en.jpg?width=300px) |


### Передача файлов (Android)
------

Необходима версия RustDesk 1.1.9+.

В списке устройств на главной странице выберите нужное устройство.

Нажмите на дополнительные опции слева и выберите `File Transfer`

| Главная страница | Успешное подключение |
| --------------- | -------------------------------------------------------- |
| ![](/docs/en/manual/mobile/images/connection_home_file_en.jpg?width=300px) | ![](/docs/en/manual/mobile/images/file_connection_en.jpg?width=300px) |



- Первоначальной директорией будет домашняя папка устройства. Нажмите <i class="fas fa-home"></i> чтобы быстро вернуться в неё.
- Под заголовком указан список папок и файлов. Нажмите на нужную папку чтобы перейти в неё.
- Нажмите <i class="fas fa-arrow-up"></i> чтобы перейти в родительскую папку.
- Текущий абсолютный путь и статистика показаны внизу списка.
- Нажмите `Local` / `Remote` в сроке заголовка для переключения сторон.


#### **Как передавать файлы?**

| Режим множественного выбора | Вставка файла |
| --------------- | -------------------------------------------------------- |
| ![](/docs/en/manual/mobile/images/file_multi_select_en.jpg?width=300px) | ![](/docs/en/manual/mobile/images/file_copy_en.jpg?width=300px) |

1. **Длительное нажатие** на файл включает **режим множественного выбора**, в котором можно передавать несколько файлов.
2. После выбора файлов, переключите стороны. Вы увидите сообщение `Paste here? `, нажмите на значок вставки чтобы передать выбранные файлы в целевую папку.

### **Настройка ID-сервера/Ретранслятора**
------
Нажмите `Settings` на нижней панели, выберите `ID/Relay Server`.
После ввода и сохранения настроек, приложение автоматически переключится на нужный сервер.
Так-же вы можете отсканировать [QR code](https://rustdesk.com/docs/en/self-host/console/images/console-home.png?v2) в Web-консоли.

![](/docs/en/manual/mobile/images/id_setting_en.jpg?width=300px)


Подробнее о самостоятельном развёртывании сервера можно узнать [здесь](/docs/ru/self-host/)