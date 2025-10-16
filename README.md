Обновил 16.10.25 ВАЖНО: запускать, когда дота запущена, но поиск игры ещё не начат.

https://mega.nz/file/JGVh2QoQ#1vEhsb0X2KyJv8tuUYxAs0J5YFHKnH60EwkRJWIjff0

​ВБЕ только для героев:

        if (strcmp(localHeroName, "npc_dota_hero_clinkz") == 0)
            gVisuals.modificIndex = 863;
        else if (strcmp(localHeroName, "npc_dota_hero_viper") == 0)
            gVisuals.modificIndex = 672;
        else if (strcmp(localHeroName, "npc_dota_hero_warlock") == 0)
            gVisuals.modificIndex = 686;
        else if (strcmp(localHeroName, "npc_dota_hero_witch_doctor") == 0)
            gVisuals.modificIndex = 696;
        else if (strcmp(localHeroName, "npc_dota_hero_crystal_maiden") == 0)
            gVisuals.modificIndex = 86;

1) Вернул кнопку рисовать кольцо вокруг героя и радиус джема врага.
2) Чит отправляет HWID на север чита, хочу узнать количество активных пользователей.

форум: https://yougame.biz/threads/342491/

telegram: @dota2pasta_bot

!!!WITHOUT humanizer and bypass VAC!!!

!!!БЕЗ обхода античита и корректировки камеры!!!

Функционал:
1) отдаление камеры
2) вас видит враг
3) частицы в тумане
4) автоматика: сценарии, уклонение
5) внешняя дополнительная информация

видео пример как создать свой сценарий: https://youtu.be/Y5Di6EUOpas
dota2 camera zoom patcher dota2pasta ver.1.1.4 BETA

1) требуется директ икс 11

2) инжектить, когда карта прогружена

3) примеры сценариев в папке: "\d2p280224\source\heros\clinkz\Standart.json"

4) сценарии требуют, чтобы враг был под курсором

Инструкция по созданию сценариев:

1) автоматика - Сценарии - Настройка сценариев

2) выбрать героя

3) ввести имя нового сценария

4) поставить галку "Активный"

5) выбрать горячую клавишу

6) нажать кнопку "добавить действие"

7) ОБЯЗАТЕЛЬНО заполнить все поля: cast, item or ability

enemy целью будет враг

local hero целью будет ваш герой для предметов или способностей, которые требуют указания цели, например плащ невидимка

no target - целью будет ваш герой для предметов или способностей, которые НЕ требуют указания цели, например бкб

position - целью будет область, сетка или главная способность загадки 

армлет: https://imgur.com/rWCF78N

акс: https://imgur.com/a/v8IBXPt

https://youtu.be/iIa62zmNjaw



