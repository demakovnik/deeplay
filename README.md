# Тестовое задание Deeplay

### 1. Задание №1
Имеется лог файл log.txt

Необходимо при помощи любых локальных инструментов (bash, python ...) получить отсортированный список всех значений sid в строках с IP=10.1.192.38

Значения sid должны быть без ограничивающих символов '/', кроме тех, что находятся внутри значения.

В папке task1 находятся 2 файла: script и log.txt. Необходимо перейти в папку task1 и запустить файл script с ключом log.txt (предварительно нужно убедиться на то, что скрипт имеет права на запуск (sudo chmod +x script)). Команда для проверки скрипта:
```
p<>.$ ./script log.txt 
```


### 2. Задание №2
Имеется app.jar файл.

Для его запуска используется команда java -jar app.jar some_out_file "Service is working!"

Напишите простой демон для systemd (Linux), который будет поддерживать работу приложения и перезапускать его в случае выхода из строя процесса.

Необходимо сделать защиту от зацикливания перезапусков, когда процесс постоянно выходит из строя.
