# Скрипты для Микротика
Разложены по следующим папкам:
## DHCP-server
Описание:         Отправка уведомлений в телеграм при появлении и исчезновении устроства в локальной сети. 
                   Скрипт при обнаружении выдачи DHCP сервером нового IP адреса записывает в Netwatch два скрипта UP, DOWN), 
                   которые в свою очередь, отправляют уведомления о появлении и исчезновении данного IP адреса в сети.
                   Иконки ГОСТЬ - зеленый квадрат и рукопожатие при входе, серый квадрат и машущая ладонь при выходе.
                   Отправляет 10 пингов, сообщает среднюю скорость ответа и потери пакетов.


