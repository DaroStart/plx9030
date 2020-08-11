# plx9030

Linux driver for PCI controller plx9030

1. Небоходимо добавить строчку "plx9030" в /etc/modules для загрузки драйвера при включении
2. Добавить правило в udev: /etc/udev/rules.d/10-plxdev.rules "KERNEL=="plxdev[0-9]*", MODE="0666". Позволит использовать устройство всем пользователям
