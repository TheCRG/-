# Установка CentOS на VMware Workstation и первоначальная настройка.
VMware Wokstation создает полностью изолированные безопасные виртуальные машины. Уровень виртуализации VVMware сопоставляет ресурсы физического оборудования с ресурсами виртуальной машины. Таким образом, каждая виртуальная машина получает собственные ЦП, память, диски и устройства ввода-вывода и является полным эквивалентом стандартного компьютера x86.
Centos является дистрибутивом GNU/Linux, основанном на свободных исходных текстах коммерческого дистрибутива Red Hat Enterprise Linux компании Red Hat.
    
Для того, чтобы установить CentOS на виртуальную машину, будет использован образ стандартного дистрбутива CD, который можно скачать с официального сайта CentOS https://www.centos.org/. Я буду исползьовать CentOS 7 mininal, который является самой простой версией данной операционной системы.
    
# Установка.
Теперь, когда скачан образ CentOS 7 minimal, и установлен VMware Workstation, можно преступить непосредственно к созданию виртуальной машины и установки на нее CentOS.Для начала откроем VMware Workstation и выберем пункт "Создать новую виртуальную машину". ![](http://s7.hostingkartinok.com/uploads/images/2015/07/a721eb021bf7d5656e205e260539bdc8.jpg)

После указываем путь к своему образу CentOS 7 minimal, который вы скачали ранее.![](http://s7.hostingkartinok.com/uploads/images/2015/07/935d239383a343a228da8a51213cb995.jpg)

Теперь необходима указать данные учетной записи, из которой будет производиться работа в нашей новой системе.![](http://s7.hostingkartinok.com/uploads/images/2015/07/35cb485b0b2a5f5cd799f9f5db749851.jpg)

Далле выбираем дириекторию, куда будет произведена установка системы, а в следующем окне максимальное количество места, которое может занимать система на жестком диске.
И наконец, в последнем окне мы можем выбрать сколько ресурсов будет отведено нашей системе.![](http://s7.hostingkartinok.com/uploads/images/2015/07/0d4e402133d8a59814cd3146a8c89912.jpg)
После чего нажимем "Finish" и ждем конца установки.![](http://s7.hostingkartinok.com/uploads/images/2015/06/3883a3c3afce5673970acd3d49a99582.jpg)

# Вход в систему и подключение в сети.
При запуске системы
