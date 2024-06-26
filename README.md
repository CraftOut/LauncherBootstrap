# LauncherBootstrap

Программа для предзагрузки лаунчера написанного на Java (sashok724's/KeeperJerry/Gravit) со встроенной загрузкой Java.

## Настройка

Настройка происходит в файле `lib/config.dart`. Рассмотрим опции настроек:
- `launcherJarUrl` - URL адрес до jar версии вашего лаунчера.
- `projectDirectoryName` - Название директории в которой будут храниться лаунчер с Java (Она будет создана в `AppData\Roaming` или `/home/user`).

## Сборка

Сборка происходит в автоматически при любых изменениях в репозитории. Бинарные файлы загружаются во вкладку `Releases`. 
