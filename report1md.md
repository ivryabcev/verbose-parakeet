## Отчёт Лабораторная работа № 1
# Основы информационной безопасности
Рябцев Илья Витальевич
НКАбд-03-22

---
# Содержание

# 1	Цель работы
Лабораторная работа подразумевает установку на виртуальную машину
VirtualBox (https://www.virtualbox.org/) операционной системы Linux
(дистрибутив Rocky (https://rockylinux.org/)).

---
# 2	Задание
Установка на виртуальную машину
VirtualBox (https://www.virtualbox.org/) операционной системы Linux
(дистрибутив Rocky (https://rockylinux.org/)).

---
# 3	Теоретическое введение
В этой лабораторной работе нам нужно будет установить Rocky Linux на VirtualBox и проверить некоторые команды

---
# 4	Выполнение лабораторной работы
Выполнение:

Шаг 1: В виртуал бокс создаем новую машину,освобождаем место на жестком диске и выделяем его под виртуальную систему.

Шаг 2: Качаем образ и загружаем его в папку виртуал бокса

Шаг 3: Устанавливаем образ на виртуальную машину и перезапускаем после установки

Шаг 4: Настраиваем ОС

Шаг 5: Проверяем команды.

---
# 5	Выводы
Вспомнил как устанавливать операционную систему на виртуальную машину.

---
# 6	Ответы на контрольные вопросы
Учётная запись пользователя содержит следующую информацию:

Имя пользователя (username)
Идентификатор пользователя (UID)
Группа пользователя (primary group и secondary groups)
Домашний каталог пользователя
Оболочка (shell), которую использует пользователь при входе в систему
Пароль (зашифрованный в /etc/shadow)
Команды терминала:

Для получения справки: man <команда> (например, man ls для справки по команде ls)
Для перемещения по файловой системе: cd <путь> (например, cd /home/user)
Для просмотра содержимого каталога: ls (или ls <путь>)
Для определения объёма каталога: du -h <каталог> (например, du -h /var/log)
Для создания каталогов / файлов: mkdir <имя_каталога> и touch <имя_файла>
Для удаления каталогов / файлов: rmdir <имя_каталога> и rm <имя_файла>
Для задания прав на файл / каталог: chmod <права> <файл> (например, chmod 755 file)
Для просмотра истории команд: history
Файловая система - это способ организации, хранения и управления файлами и данными на устройстве хранения. Примеры:

ext4: Распространённая файловая система для Linux, обеспечивает хорошую производительность и надёжность.
NTFS: Файловая система, используемая в операционных системах Windows.
HFS+: Файловая система для macOS.
Посмотреть подмонтированные файловые системы:

df -h
Удаление зависшего процесса:

Использовать команду kill или kill -9 с идентификатором процесса (PID). Например, kill -9 <PID>.
Рекомендуется также обратить внимание на дополнительную информацию в указанных источниках [1—8; 15—18].







```python

```
