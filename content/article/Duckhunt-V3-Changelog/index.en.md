---
title: "Duckhunt V3 changelog"
date: 2018-03-14T20:00:00+02:00
draft: false

categories: ['Changelog']
tags: []
---

Многое изменилось и это ещё не конец! :)
 
Снизу вы найдёте полный список изменений. Если найдёте баг, просим сообщить о нём.

<!--more-->
 
Если вы хотите мне помочь, то вы можете это сделать одним из следующих способов:

*   Локализация (много текста изменилось, на данный момент локализация не закончена)
*   Оформление сайта. Вы классный дизайнер? Тогда нам очень нужна ваша помощь!
*   Создание раздела ЧаВо. От вас не требуются навыки в программировании
*   Материальная помощь: [http://ko-fi.com/duckhunt](http://ko-fi.com/duckhunt "http://ko-fi.com/duckhunt")

Если хотите помочь, получить помощь или поговорить насчёт бота, то пишите мне в ЛС или в канал #support_english: [https://discord.gg/G4skWae](https://discord.gg/G4skWae) Перейдём к списку изменений.

*   Для игроков:
    *   Добавлены события. Чтобы проверить, есть ли сейчас активное событие, используйте dh!event. События происходят на всех серверах сразу, во время событий происходят некоторые изменения (активность уток и т. д.).
    *   Добавлена поддержка общих эмодзи
    *   Добавлены подсказки, связанные с частыми вопросами
    *   Теперь команды нечувствительны к регистру: !BaNg или !SHOOt теперь работают
    *   Теперь вам не нужно запоминать номера предметов в магазине: используйте !shop charger, !shop bullet и т. д.
    *   Добавлены пасхалки
    *   Теперь бот собирает больше данных
    *   У нас появился ещё один сайт https://duckhunt.me. На нём есть обновлённый список команд, параметров, а также новый раздел ЧаВо.
*   Для администраторов:
    *   The coin command allows the user to choose the life and the super-duck status of a spawned duck
    *   Duckplanning has been updated to show the current ducks in the channel
    *   New setup command to replace the !claimserver one (!setup)
    *   Users with the administrator permission are now admins by default
    *   global_scores has been removed, as it was rarely used
    *   settings list and setting modified now show the settings in-chat
    *   send_exp is now taxed by default
    *   emoji_ducks is now enabled by default
*   For developers:
    *   The bot now uses discord.py rewrite
    *   There is no json file anymore (As a result, the bot is faster)
    *   The bot is sharded (Can support more than 2500 servers)
    *   Hastebin support was replaced by long messages support
    *   The ping command is clearer now
    *   Bugs have been added too
*   For self-hosters (if you don't know what that is, you aren't one):
    *   A migration script for the json file has been provided, and the new database scheme will be available soon

With löve, Arthur
