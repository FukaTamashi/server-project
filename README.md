# server_project

__1 Введение__

Цель проекта разработака сервера на локальном хосте для обхода и редактирования файлов.

__1.1 Назначение__

Предполагается что данная программа будет использоваться пользователями для удалённого доступа к серверу.Автоматизированная система позволит перемещаться по директориям, а также редактировать файлы в режиме реального времени.

__1.2 Требования__

Внедрение программы закрывает некоторые потребности пользователя.Предствим ситуацию когда нет возможности взять,например пк с собой,рабочий или домашний и у вас есть ноутбук и вам нужно просмотреть имеющиеся файлы или отредактировать файл, но вам потребуется сделать это из другого места,для таких ситуаций и предназначена данная программа с серверной и клиентской частью.

### 2 Требования пользователя
_____________________________

__2.1 Программный интерфейс__

В качестве программного интерфейса будет выступать окно терминала

__2.2 Интерфейс пользователя__

Клиентское окно терминала:


![S](https://github.com/FukaTamashi/server-project/blob/master/images/%D0%9E%D0%BA%D0%BD%D0%BE%20%D0%BA%D0%BB%D0%B8%D0%BD%D1%82%D0%B0.png)

Серверное окно терминала:


![S](https://github.com/FukaTamashi/server-project/blob/master/images/%D0%9E%D0%BA%D0%BD%D0%BE%20%D1%81%D0%B5%D1%80%D0%B2%D0%B5%D1%80%D0%B0.png)

__2.3 Характеристика пользователей__

Целевая аудитория данной программы - люди которым часто приходиться работать удалённо от своего рабочего компьютера:уменик пользоваться окном терминала, поверхстное умение работы с файлами.

### 3 Системные требования
__________________________
Для работы с программой необходимо:
ОС Linux

__3.1 Функциональные требования__

Система должна обеспечивать возможность выполнения следующих функций:
* Обход большиства директорий
* Взаимодействие с файлами

__3.2 Требование к безопастности__
Надежное функционирование системы должно быть обеспечено выполнением организационно-технических мероприяитий, таких как:
* организация бесперебойного питания путем использования блоков бесперебойного питания;
* Загрузка программы не должна превышать 7 секунд
