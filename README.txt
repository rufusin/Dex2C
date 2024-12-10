Включение поддержки длинных путей
В Windows 10 1607+ можно включить поддержку длинных путей. Выполните команду от имени администратора и перезагрузитесь.

reg add "HKLM\SYSTEM\CurrentControlSet\Control\FileSystem" /v LongPathsEnabled /t REG_DWORD /d 1