# Ветвление

<strong>Ветвление</strong> - отклонение от основной линии разработки и продолжение работы независимо от неё, не вмешиваясь в основную линию.

Основные команды для работы с ветками:</br>
**Git branch [name]**- команда, которая создает новую ветку в репозитории.</br>
**Git checkout [name]** - команда переключает на определнноую ветку в репозитории.</br>
**Git checkout -b [name]** - команда, которая переключает на определнную ветку (оюъединение двух первых команд).</br>

Команды для объединения веток:</br>
**Git merge [name]** - команда вносит [коммиты](./gitCommit.md) из другой ветки в текущую.</br>
**Git rebase [name]** - [коммиты](./gitCommit.md) текущей ветки накладываются поверх текущего состояния указанной ветки.</br>
