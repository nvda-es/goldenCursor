# Golden Cursor #

* Автор: salah atair, Joseph Lee
* Загрузить [стабильную версию][1]
* Совместимость с NVDA: 2023.3.4 и выше

Это дополнение позволит перемещать мышь с помощью клавиатуры и сохранять
позиции мыши для приложений.

## Комбинации клавиш

* Control+NVDA+L: просмотреть сохранённые положения мыши для приложения,
  если таковые имеются. Вы также можете назначить жесты для этих положений в
  этом диалоге. При нажатии на назначенный жест сохранённого положения будет
  выполнен щелчок левой кнопки мыши.
* Shift+NVDA+l: сохранить тег или метку для текущего положения мыши в
  текущем приложении в фокусе.
* Windows+NVDA+C: изменить единицу перемещения мыши.
* Windows+NVDA+R: переключить ограничение мыши.
* Windows+NVDA+S: включить или выключить объявления позиций мыши в пикселях.
* Windows+NVDA+J: переместить мышь в определённое положение по осям x и y.
* Windows+NVDA+P: сообщить положение мыши.
* Windows+NVDA+M: Включить или выключить стрелки мыши.
* Windows+NVDA+стрелки (или просто клавиши стрелок, если включены стрелки
  мыши): перемещение мыши.

Примечание: эти жесты могут быть переназначены в диалоге жестов ввода в
категории Golden Cursor .

## Примечания

* При предоставлении позиционирования (тэгов), каждая сторона должна
  использовать одинаковое Разрешение дисплея.
* Для максимальной совместимости, вы должны развернуть окна, нажав клавиши
  Windows+стрелка вверх.
* При совместном позиционировании, существующие метки позиций должны быть
  переименованы.
* Форматы положения мыши версий 1.x и 2.x несовместимы.
* Для выполнения функций, требующих использования клавиш стрелок, сначала
  отключите стрелки мыши.
* При удалении сохранённых положений, если сохраненных положений не
  осталось, положения для приложения будут удалены.

## Версия 6.2

* Требуется NVDA 2022.4 и выше.
* Совместимо с NVDA 2023.1.

## Версия 6.1

* Требуется NVDA 2021.3 и выше.
* Теперь вы можете назначить горячие клавиши для сохраненных положений из
  списка. При нажатии на горячую клавишу для положения будет выполнен щелчок
  левой кнопкой мыши.

## Версия 5.0

* Обновлен исходный код дополнения, чтобы сделать его совместимым с NVDA
  2021.1.
* Устранены многие проблемы со стилем кодирования и потенциальные ошибки с
  помощью Flake8.

## Версия 4.0

* Требуется NVDA 2019.3 и выше.
* Диалог настроек Golden Cursor было заменено панелью настроек Golden
  Cursor.

## Версия 3.3

* Внутренние изменения для поддержки будущих выпусков NVDA.

## Версия 3.2

* Дополнение совместимо с NVDA 2018.3 (wxPython 4).

## Версия 3.0

* При использовании NVDA 2018.2 настройки дополнения будут доступны на новом
  экране настроек для нескольких категорий в категории "Golden Cursor".

## Версия 2.1

* Исправлена ошибка декодирования в юникоде при попытке удалить название
  тега.
* Предотвращено Многократное Использование При Открытии различных Диалогов
  дополнений.
* Улучшен внешний вид списка положений мыши и диалогов перехода к
  положениям.

## Версия 2.0

* Требуется NVDA 2017.3 и выше.
* Формат файла положения несовместим с версиями 1.x. Если найден формат
  положения 1.x, старые положения будут перенесены в новый формат во время
  установки.
* Добавлен новый диалог настроек Golden Cursor в меню настроек NVDA для
  настройки единицы перемещения мыши и объявления положения мыши при её
  перемещении.
* Изменились различные сообщения дополнения.
* При переключении различных настроек звуковой сигнал переключения больше не
  будет слышен.
* Теперь вы можете перейти в режим стрелок мыши, в котором вы можете
  перемещать мышь, нажимая только клавиши стрелок.
* Изменения в диалоге списка положений, включая новое название (теперь оно
  называется положениями мыши) и макет, отображение координат мыши для
  надписи и отображение названия активного приложения в качестве части
  заголовка.
* В диалоге "Положение мыши" нажатие клавиши Enter на сохраненной метке
  приведет к перемещению мыши в сохраненное местоположение.
* При переименовании положения мыши будет показан диалог с сообщением об
  ошибке, если существует метка с тем же именем, что и новое имя.
* При удалении или очистке положений мыши теперь вы должны ответить "Да",
  прежде чем положения будут удалены и/или очищены.
* Изменения в функции перемещения мыши, включая новое название (теперь оно
  называется "Новое положение мыши") и возможность вводить координаты X и Y
  отдельно или с помощью клавиш стрелок вверх или вниз.
* В диалоге, отображаемом при сохранении текущего положения мыши, теперь
  отображаются координаты её текущего положения.
* При сохранении позиций устранена проблема, из-за которой NVDA может
  воспроизводить звуковые сигналы ошибки, если папка позиций не существует.

## Версия 1.4

* Удалена зависимость от win32api, чтобы сделать ее совместимой с
  предыдущими и будущими версиями NVDA.

## Версия 1.0

* Первоначальный выпуск.

[[!tag stable dev]]

[1]: https://www.nvaccess.org/addonStore/legacy?file=goldenCursor
