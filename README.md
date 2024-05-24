# CyberSecurity


# 1) Network Packet Sniffer (PacketSniffer)


## Використання
```
sniffer.py [-h] [-d]

Network Packet Sniffer

optional arguments:
  -h, --help            Показати цей рядок допомоги і вийти
  -d, --data            Видавати дані пакетів під час захоплення пакетів.
```

# 2) Keylogger

## Інсталяція

```
  pip3 install -r requirements.txt
```

## Запуск

Запустивши команду `nohup python3 keylogger.py &`, вона почне реєструвати ваші натискання:
Значення nohup означає «без зависання».
Коли команда nohup використовується з «&», вона не повертається до командного рядка оболонки після виконання команди у фоновому режимі.
```
$~/Keylogger/linux$ nohup python3 keylogger.py &
[1] 12529 //this is the keylogger's PID (process ID)
$:~/Keylogger/linux$ fg

```
`kill {PID}` наприклад `kill 12529`

---

