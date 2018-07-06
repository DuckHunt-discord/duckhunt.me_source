---
title: "Список команд"
date: 2002-01-00T00:00:00+00:00
draft: false

categories: []
tags: []
---
В примерах команды приведены с универсальным префиксом `dh!`.

Администраторы могут устанавливать свой префикс на своих серверах (`!` по умолчанию).
 
Если параметр находится между `<>`, значит он обязательный, если между `[]`, значит его можно не указывать.
При использований команд использовать `<>` и `[]` не надо  :)
 
Для указания конкретного пользователя можно использовать его ID или @упомянуть его.
   
   
Ниже описаны все команды, как те, которые могут использовать все, так и команды для настройки DuckHunt на вашем сервере (их могут использовать только администраторы).
 
Для получения дополнительной информации о некоторых командах посетите [список товаров](https://duckhunt.me/shop-items/) и [список параметоров](https://duckhunt.me/bot-settings/).

## Команды для игры (могут использовать все)

{{< table >}}
|Команда|Описание|
|--- |--- |
|dh!bang|Используйте, чтобы выстрелить. Иногда что-то может пойти не так и вы можете промахнуться по утке... и попасть в кого-то ещё.|
|dh!reload|Используйте, чтобы перезарядить ружьё. У вас должен быть хотя бы один запасной магазин для перезарядки. Какждый день их раздают бесплатно (см. команду dh!freetime), их также можно купить в магазине.|
|dh!help|Используйте, чтобы получить справку о работе бота.|
|dh!wiki|Используйте, чтобы получить ссылку на этот сайт.|
|dh!stats [игрок]|Используйте, чтобы узнать свою или чужую статистику.|
|dh!shop <номер предмета> [параметр]|Используйте для совершения покупок в магазине. Для получения дополнительной информации посетите список предметов (см. dh!shop list).|
|dh!top --sort-by [time/missed/exp/killed]|Используйте, чтобы просмотреть список лучших охотников канала. Можно выбрать, по какому критерию сортировать (time — время, missed — промахи, exp — кол-во очков опыта, killed — кол-во убитых уток).|
|dh!send_exp <игрок> <количество>|Используйте, чтобы отправить другому охотнику некоторое кол-во очков опыта. В зависимости от настроек сервера может быть наложена комиссия.|
|dh!freetime|Используйте, чтобы посмотреть, когда произойдёт ближайшая раздача вещей.|
|dh!settings list|Используйте, чтобы просмотреть список параметров.|
|dh!settings modified|Используйте, чтобы просмотреть значения у параметров, которые были изменены.|
|dh!ping|Используйте, чтобы проверить пинг.|
|dh!uptime|Используйте, чтобы узнать аптайм бота.|
{{< /table >}}

## Команды для администраторов

{{< table >}}
|Команда|Описание|
|--- |--- |
|dh!setup|This is the first command you should use after inviting DuckHunt to a server. It create the server settings and have a configuration wizard to make it easier for you.|
|dh!add_channel|After using dh!setup, use this command on the channels you want ducks to appear in.|
|dh!del_channel|This disables a channel added by dh!add_channel.|
|dh!del_user|This removes an user from the database.|
|dh!del_user_id|This removes an user from the database. This comment is meant to be used on players that left the server.|
|dh!add_admin|Set another server administrator as an admin. Note that users with the Administrator permission in discord are considered Administrators too.|
|dh!del_admin|Deletes a server admin from the admins list.|
|dh!coin [--super-duck] [--life <life-points>]|Forces a duck to spawn.|
|dh!ducks|Shows the number of ducks that will spawn today, and the list of ducks that are on the channel. It can be considered as a cheat.|
|dh!give_exp <player> <amount>|Gives a player some exp points. This is a cheat, not to be confused with dh!send_exp.|
|dh!settings set <parameter> <value>|Modify server settings. You can go to the Bot Settings page to learn more about this command.|
|dh!settings reset <parameter>|Resets a parameter to the default value. Use this command and not dh!settings set to reset parameters, as it won't cause issues with bot upgrades.|
|dh!game_ban <player>|Bans a player from the game. You can't ban admins, so please don't try :)|
|dh!game_unban <player>|Unbans a player from the game. They will be able to play again.|
|dh!remove_all_scores_and_stats_on_this_channel|Deletes a channel scores and stats. Please be sure you really want to do this. You cannot undo this.|
{{< /table >}}



