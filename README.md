# SELinux_Policy_Grabber
Этот простой скрипт предназначен для решения проблем с SELinux для деревьев устройств. 

Использование:
- Поместить скрипт в **корневую директорию пользователя**
- Поместить рядом со скриптом **log.txt** (лог файл) формата:
> logcat, dmesg, kmsg(?), last_kmsg(?)           |          (?) - тестируется
- Выполнить 
```
    bash SELinux_grabber.sh
```

- В директории **~/out/sepolicy** будут файлы с нужными правами исходя из ошибок в логе.



# SELinux_Policy_Grabber
This simple script is designed to solve problems with SELinux for device trees.

Using: 
- Place the script in the root directory of the user 
- Place next to the script log.txt (log file) format: 
> logcat, dmesg, kmsg(?), last_kmsg(?)           |          (?) - testing

- Execute
```
bash SELinux_grabber.sh
```
- In the **~/out/sepolicy** directory there are files with the necessary rights based on errors in the log.
