# ToF AHK flex v3.6

AHK скрипт для Tower of Fantasy

🙏 Полный отказ от ответственности, использование скриптов может привести к блокировке учетной записи, использовать на свой страх и риск.

[__✨Boosty✨__](https://boosty.to/kramar1337)

[Подробное описание](https://github.com/Kramar1337/Tower-of-Fantasy-AHK-flex/wiki) (Заполнено на 99%)

__🚀Функционал:🚀__

- Бинд на интерактивную карту
- Оверлей с разной инфой
- Автоходьба
- Скип диалогов
- Фастлут
- Бесконечное скалолазание
- Макросы:
  + Bhop (50ms)
  + AutoAttack (70ms)
  + InventoryClicker (15ms)
  + AutoFly (FlyHack)
  + Huma combo
  + Frigg ShiftClick
  + Nemesis Air AA
  + SHIRO Chakram
  + Karasuma drill
  + Diluc Vertical Flight
- AFK фермерство
  + AFK фермерство, фарм монет дружбы (Test)
  + AFK фермерство, ферма опыта и материалов для маунтов в Frontier (Test)
- AFK фермерство. Работает даже когда окно игры не активно ( ͡° ͜ʖ ͡°)
  + AFK фермерство, спам "F"
  + AFK фермерство на Хильде, спам "Click" каждые 3 сек
  + AFK ачивка сёрфера, залипание кнопки "W" и "A"
  + AFK фермерство, спам "F" залипание кнопки "W" и "A". (Например на Phosphogranate: -75, -845)
  + AFK фермерство, спам "F" ходьба вперед - назад

__🛴Возможности:🛴__

- Полуавтоматическое обновление (находится в трей меню, возможны ложные срабатывания AV)
- Импорт настроек скрипта при обновлении
- Безопасность: Name changer, Hash changer, WindowNameChanger

__⚠️Требования к правильной работе скрипта:⚠️__

- Правильная установка Autohotkey!!! 
- Fullscreen или Borderless режим
- Запуск от имени Администратора

:memo:__Показания к применению:__:memo:

1. Скачать и установить [Autohotkey.com](https://www.autohotkey.com/download/ahk-install.exe)

  "Custom installation" => "Unicode 64" => All checkboxes => "Install"
![hippo](https://media.giphy.com/media/LerrohpjasApOHH9G1/giphy.gif)

2. Скачать репозиторий (Code > [Download Zip👌](https://github.com/Kramar1337/Tower-of-Fantasy-AHK-flex/archive/main.zip))

3. Настроить "TOFu\data\tofuConfig.ini" по необходимости

3. Запустить "TOFu.ahk"

:musical_keyboard:__Горячие клавиши:__:musical_keyboard:
```
AHK
F1 - *Карта
F2 - *Оверлей
F3 - *Автоходьба
F9 - Автоприниматель лобби
Z - Скип диалогов
F - Фаст лут
X - Бесконечное скалолазание
4 - Абузный полет (планер в конфиге "key_flyhackGajetKey")
V - Macro Key

Numpad 0 - Off
Numpad 1 - AutoAttack(70ms)
Numpad 2 - InventoryClicker(15ms)
Numpad 3 - AutoFlyHack (первый клик - вкл, повторный клик - выкл)
Numpad 4 - Huma combo t1
Numpad 5 - Huma combo t2
Numpad 6 - FRIGG Shift+LButton (Test)
Numpad 7 - Bhop 50ms (Jetboard Jumping) (Кататься на доске для серфа по земле)
Numpad 8 - Samir Dash
Numpad 9 - Nemesis Air hold (Находясь в воздухе удерживать "Macro Key")
NumpadAdd - Diluc Vertical Flight (Экипировать и забиндить джетпак)
Alt + Numpad 1 - SHIRO Chakram
Alt + Numpad 2 - Karasuma drill (Test) (Экипировать и забиндить джетпак)

F4 - *Слот под спец макросы (Настраивать отдельно в "tofuConfig.ini")
Переключить: Alt + Up и Alt + Down
0 - Отключить
1 - AFK фермерство, спам "F" каждые 2 сек
2 - AFK ачивка сёрфера, залипание кнопки "W" и "A"
3 - AFK фермерство на Хильде, спам "Click" каждые 5 сек
4 - AFK фермерство, спам "F" залипание кнопки "W" и "A". Гранатная ферма(-75, -845)
5 - AFK фермерство, спам "F" ходьба кругами "W" и "S", 5 секунд вперед, 5 секунд назад
6 - AFK фермерство SendInput, Фарм монет дружбы, для работы нужно < 30 смолы
7 - AFK фермерство SendInput, Фарм Frontier (Дружба, опыт, материалы. Для работы нужно потратить ходки в Frontier и потратить ходки в рифт)

Esc - Остановить потоки
End - Завершить работу AHK
PgUp - Приостановить - возобновить работу AHK
Left - Переключить оверлей
Right - Переключить оверлей
```

<details>
<summary>==Список изменений==</summary>

Изменения: 04.09.2022

 - 7 - AFK фермерство SendInput, Фарм Frontier (Дружба, опыт. Для работы нужно потратить ходки и потратить рифт)
  
Изменения: 03.09.2022
 - 6 - AFK фермерство SendInput, Фарм монет дружбы, для работы нужно < 30 смолы
 - 3 - AFK фермерство на Хильде, спам "Click" каждые 3 сек

Изменения: 30.08.2022
 - Macro Key не блокируется вне игры
 - Исправление VLC, фильтры окна "GroupAdd"
 - Фарм ходить по кругу. 5 - AFK фермерство, спам "F" ходьба кругами "W" и "S", 5 секунд вперед, 5 секунд назад

Изменения: 27.08.2022
 - Alt + Up переключить спец макрос (F4)
 - Alt + Down переключить спец макрос (F4)
 - Автоприниматель пропускает кнопку "пойти в данж если нет смолы?"
 - Фокусировка карты, исправления
 - AFK фермерство, спам "F" каждые 2 сек (было 5, рероллерам привет)
 - Пропуск диалогов 180ms

Изменения: 21.08.2022
 - Alt + Numpad 1 - SHIRO Chakram
 - Alt + Numpad 2 - Karasuma drill (Test) (Экипировать и забиндить джетпак)

Изменения: 19.08.2022
 - Перенос служебных кнопок Pgup End и тд в "tofuConfig.ini"
 - Оверлей материалы на пушки
 - Numpad 9 - Nemesis Air hold (Находясь в воздухе удерживать "Macro Key")
 - Микроподкрутки
 - 4 - AFK фермерство Controlclick, спам "F" залипание кнопки "W" и "A". Гранатная ферма(-75, -845)

Изменения: 16.08.2022
 - Numpad 4 - Huma combo t1
 - Numpad 5 - Huma combo t2

Изменения: 14.08.2022
 - Автоходьба сквозь свернутое окно
 - Ренеймер
 - Обновлятор с импортером настроек
 - Фикс переключателя карты
 - Центрирование мышки при переключении карты в tofuConfig.ini "MouseCenterMapVar = 1"
 - Тайминги скипера диалогов
 - F4 - *Слот под специфические макросы (Настраивать отдельно в "tofuConfig.ini")
 - 1 - AFK фермерство, спам "F" каждые 5 сек
 - 2 - AFK ачивка сёрфера, залипание кнопки "W" и "A"
 - 3 - AFK фермерство на Хильде, спам "vk1" каждые 5 сек

Изменения: 10.08.2022
 - Работает на глобал и китай клиенте
 - Numpad 0 - Off
 - Numpad 1 - AutoAttack(70ms)
 - Numpad 2 - InventoryClicker(15ms)
 - Numpad 3 - AutoFlyHack (первый клик - вкл, повторный клик - выкл)
 - Numpad 4 - Meril Air Attack v1 (Test) (Прыгнуть и удерживать "Macro Key")
 - Numpad 5 - Meril Air Attack v2 (Test) (Прыгнуть и удерживать "Macro Key")
 - Numpad 6 - FRIGG Shift+LButton (Test)
 - Numpad 7 - Bhop 50ms (Jetboard Jumping) (Кататься на доске для серфа по земле)
 - Numpad 8 - Samir Dash Attack Cancels (Быстрое передвижение рывками)
 - Numpad 9 - Samir Vertical Flight (Экипировать и забиндить джетпак)
 - NumpadAdd - Diluc Vertical Flight (Экипировать и забиндить джетпак)

Изменения: 22.07.2022
 - Оверлей

Изменения: 11.07.2022
 - Автоприниматель

Изменения: 04.07.2022
 - Оверлей фулл: Данжи, Чипы, Боссы, Готовка

Изменения: 29.06.2022
 - Скип диалогов фулл
 - Оптимизация
 - Пустой оверлей
 - Пустые слоты
 - Автоходьба

==Конец списка==

</details>
