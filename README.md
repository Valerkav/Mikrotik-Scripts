# Сценарии для Микротика(RouterOS)
Разложены по следующим папкам:
## DHCP-server
Назначение:       Отправка уведомлений в телеграм при появлении и исчезновении устройства(IP-адресу) в локальной сети. 
                   Скрипт при обнаружении выдачи DHCP сервером нового IP адреса записывает в Netwatch два скрипта UP, DOWN), 
                   которые в свою очередь, отправляют уведомления о появлении и исчезновении данного IP адреса в сети.
                   Иконки ГОСТЬ - зеленый квадрат и рукопожатие при входе, серый квадрат и стрелка вниз при выходе.
                   Отправляет 10 пингов, сообщает среднюю скорость ответа и потери пакетов. Также пришлет текст из комментария в DHCP сервере микротика.
                   
                   ![image](https://github.com/user-attachments/assets/20ec5660-cd03-4d63-8ade-0893cd2408dc)

                   План карта:
                    - Добавить информацию из журнала микротика об уровне WiFi сигнала клиента(db).
                  Сделано:

                   _07.01.2025 - v2.6. моноширинный шрифт для значений, иконки, русификация._
