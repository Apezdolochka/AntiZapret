# AntiZapret
Обход блокировки Discord'а, Youtube'а, Steam'а, Twitch'а и др.

## Руководство
Скачайте файл из репозитория, разархивируйте в отдельную папку по пути `C:\Program Files\AntiZapret`.

Запустите **от имени администратора** то, что вам нужно:

## Запуск в виде приложения (одно на выбор):
- **`1_antizapret.cmd`** - для обхода блокировки Discord'а, Youtube'а, Steam'а, Twitch'а и др.
- **`1_discord.cmd`** - для обхода блокировки только Discord'а.

## Установка в виде службы antizapret (одну на выбор):
- **`2_service_antizapret_install.cmd`** - для обхода блокировки Discord'а, Youtube'а, Steam'а, Twitch'а и др.
- **`2_service_discord_install.cmd`** - для обхода блокировки только Discord'а.
- **`2_service_goodbye_discord_install.cmd`** - для обхода блокировки только Discord'а, если у вас уже установлена служба **goodbyedpi**. ВНИМАНИЕ: Первый раз goodbyedpi может вылететь - просто перезапустите ПК!

## Удаление службы antizapret, ранее установленной выше
- **`3_service_remove.cmd`** - остановить и удалить службу antizapret.

## Не работает?
- Проверьте, запускаете ли вы файлы от имени администратора.
- Не работает служба? Проверьте, чтобы в пути до файла **не было пробелов** и русских символов. Также отключите программы, которые могут мешать созданию службы *(Антивирусы, клинеры с доп. защитой)*.
- Не работает вместе с VPN? Отключите функцию **TUN** (Tunneling) в настройках VPN.
- Не работает `2_service_goodbye_discord_install.cmd`? Удостовертесь, что служба goodbyedpi запущена и имеет название GoodbyeDPI. После снова запустите `2_service_goodbye_discord_install.cmd` и перезапустите устройство.

### Дополнительные адреса заблокированных сайтов можно добавить в список list-general.txt (для `1_antizapret.cmd` и `2_service_antizapret_install.cmd`). После добавления, службу antizapret надо перезапустить
