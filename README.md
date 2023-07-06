# Overlocking for Kefir

[Группа в телеграме](https://t.me/kefir_switch/238091)

**ВНИМАНИЕ! Разгон консоли не приводит к необратимым последствиям. Однако, он представляет риск для данных в виду особенностей Horison OS. Поэтому настоятельно рекомендуется использовать оверлокинг исключительно в emuMMC и делать резервные копии перед его использованием**

## Установка

1. Установить [Kefir](https://codeberg.org/rashevskyv/kefir/releases) и загрузиться в систему после установки для инициализации конфигов.
2. Сделать резервные сохранения всех сохранений игр для избежания возможной потери данных. Используйте `DBI`, входящий в состав `Kefir`.
3. Распакуйте архив с [OS Suite](https://github.com/snupt/Switch-OC-Suite-Bundle/raw/main/OCS.zip) в корень SD карты с заменой файлов. В MacOS нужно выбрать не замену, а слияние. Делать это нужно на компьютере через карт ридер, либо через `Hekate` по USB.
4. Обновление продукты и установка модов происходят через Homebrew приложение `All-in-One Switch Updater`.


## Использование

1. Вход в `Tesla` меню (так же как и выход из `Status Monitor`) осуществляется комбинацией `ZR + ZL + Вниз`.
2. Разгон осуществляется путем выставления параметров в оверлей меню `Switch-OC-Suite`.
3. Для поднятия уровня разгона используйте оверлей `UltraHand`, пакет `Overlock Booster`.
4. Чем ниже уровень, тем безопасней разгон и тем меньше побочных эффектов. Выбирайте с умом!
5. Рекомендованные параметры разгона для портативного режима и игре от батареи: CPU `1020 - 1428`, GPU `844 - 921`, Memory на максимум. Чем ниже параметры, тем дольше вы сохраните заряд батареи.

## Философия

Правило по которому нужно руководствоваться используя разгон консоли — отсутствие побочных эффектов. Консоль должна работать без крашей Атмосферы, без внезапных вылетов из игр, без отключения по перегреву. Добившись этого результата вы получите стабильную консоль,  производительность в играх и меньшее энергопотребление при более высокой мощности.

## Состав проекта

- [Kefir](https://codeberg.org/rashevskyv/kefir/releases)
- [OC Suite](https://github.com/hanai3Bi/Switch-OC-Suite)
- [SaltyNX](https://github.com/masagrator/SaltyNX)
- [ReverseNX-RT](https://github.com/masagrator/ReverseNX-RT)
- [InfoNX](https://github.com/renA21/InfoNX)
- [Ultrahand](https://github.com/ppkantorski/Ultrahand-Overlay)
- [Status Monitor](https://github.com/ppkantorski/Status-Monitor-Overlay)
- [Sys ftpd light](https://github.com/cathery/sys-ftpd)
- [AIO Switch Updater](https://github.com/HamletDuFromage/aio-switch-updater)
