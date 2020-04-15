# NeuroStartUp
NeuroStartUp — динамически развивающийся стартап, специализирующийся на поиске с использованием новейших технологий искусственного интеллекта. 
Наши преимущества:

* Высокая точность поиска
* Высокая скорость поиска
* Низкая цена

![NeurostartUp_logo](https://camo.githubusercontent.com/c6727c717cad1e4820481abb87524f90782445c5/68747470733a2f2f692e696d6775722e636f6d2f495a4f525769492e706e67)



## Начало работы

Чтобы получить копию проекта для запуска на локальном ПК:
* Открываем консольный клиент.
* На Windows после установки клиента появляется пункт Git Bash в контекстом меню папки. Достаточно перейти в желаемую папку и воспользоваться этим пунктом меню. Open Git Bash in Windows
* На Unix системах достаточно открыть терминал и перейти в нужную директорию. При стандартной установке консольного клиента будет доступна команда git без дополнительных усилий.
* Выполняем команду git clone с ссылкой на репозиторий. Полную https ссылку на репозиторий для его выкачивания можно также найти на странице самого репозитория на github. После этого в текущей папке появится новая папка с именем %repo_name%, содержащая копию удаленного (remote) репозитория.
* Переходим в свежесозданную папку репозитория и настраиваем его:
1. git config user.name ivan.ivanov
1. git config user.email ivanov@example.com

### Prerequisites
Для работы необходимо установить:
* Git
* Браузер (Рекомендуется: Mozilla Firefox/ Google Chrome)
* Текстовый редактор
По желанию (для дальнейшей работы):
* GitKraken
* Интегрированная среда разработки (NetBeans/PyCharm/Microsoft Visual Studio)


### Установка и запуск

Пошаговая установка Git на Windows:


1.Начать установку Git нужно с загрузки установочного файла с официального сайта. [URL для скачивания с оф.сайта](https://git-scm.com/downloads) и выбираем версию под  Windows.

2.Далее выбираем версию, которая подходит под Ваш процессор и делаем загрузку.

3.Запускаем скачанный установочный файл, читаем лицензию и жмем Next.

4.Следующий шаг – выбор места установки. Можно указать или по умолчании, или кликнуть на Browse и выбрать необходимое расположение. После выбора жмем Next.

5.Выбираем компоненты, какие хотите установить. Для добавления ярлыка на рабочий стол, напротив On the Desktop ставим галочку. Далее жмем Next.

6.Вводим имя директории для Start Menu. Дополнительно можно кликнуть на кнопку Browse и изменяем  путь. И жмем Next.

7.Выбираем редактор для Git, по умолчанию выбран текстовый редактор, можно выбрать любой другой нажав на галочку. После выбора жмем Next.

8.Указываем способ использования Git.
* Use Git from Git Bash only – использовать только командную строку Bash.
* Git from the command line and also from 3rd-party software – использовать Git из Git Bash или из командной строки Windows.
* Use Git and optional Unix tools from the Command Prompt – использовать утилиты  Unix з командной строки Windows.          

9.Выберем библиотеку, которая будет использоваться при HTTPS соединении после выбора жмем Next.
* Use the OpenSSL – сертификаты сервера проверяются с помощью ca-bundle.crt.
* Use the Windows Secure Channel library – проверка сертификатов сервера  библиотеками Windows.

10.Выбираем как будут обрабатываться окончания строк. С первым вариантом Git изменит все окончания строк в ваших файлах с Windows-стиля (\ r \ n) на Unix-стиль (\ r) непосредственно перед фиксацией в Вашем репозитории. Когда Git извлекает файлы из Вашего репозитория, он меняет все окончания строк с Unix-стиля (\ r) на Windows-стиль (\ r \ n). Со вторым вариантом Git изменит все окончания строк В ваших файлах с Windows-стиля (\ r \ n) на Unix-стиль (\ r) непосредственно перед фиксацией в вашем репозитории; однако, когда Git извлекает файлы из вашего репозитория, он не меняет окончания строк. С последним вариантом Git не будет изменять окончание строк при фиксации или извлечении.
11.Выбор эмулятора терминала по умолчанию для Git Bash.
* Use MinTTY – терминал Unix, выбираем если Вы знакомы с командной строкой Linux.
* Use Windows default console window – использовать окно консоли Windows по умолчанию. Жмем Next.
12.Выбор дополнительного функционала.

* Enable file system caching – кэширование файлов.
* Enable Git Credential Manager – возможность доступа к некоторым Git-репозиториям, используя Вашу учетную запись Microsoft вместо ключей HTTPS / SSH.
* Enable symbolic links – поддерживать символические ссылки. После выбора жмем Next.

12.Выбор экспериментальных вариантов, которые  находятся в разработке. Нажмите Install  и Git начнет установку.

13.Последний шаг – жмем Finish, чтобы завершить установку.

Пошаговая установка Git на MacOs:

1.В некоторых версиях MacOs, Git является предустановленной утилитой, поэтому в первую очередь необходимо проверить, не установлен ли он у вас уже. Для этого запускаем программу под названием Terminal и набираем команду git --version (это обращение к некой команде Git с просьбой показать текущую версию). Нажимаем Enter.

2.После этого, если у вас не установлен Git, тогда Mac покажет вспомогательное окно, где содержится информация, что команда Git требует специальных средств разработки. 

3.Нажимаем Install, для того, чтобы запустить скачивание и установку в автоматическом режиме, участие больше не требуется.

4.Если окно с предложением установки не появляется, тогда необходимо написать спец команду - xcode-select --install

5.После этого появляется специальное окно с предложением по установке. Далее соглашаемся и ждем установку.

6.Если по каким-то причинам данный сценарий вам не подходит, тогда вы также можете проследовать по [ссылке для скачивания на официальном сайте](https://sourceforge.net/projects/git-osx-installer/files/git-2.23.0-intel-universal-mavericks.dmg/download?use_mirror=autoselect)


## Лицензия

Бесплатная программа