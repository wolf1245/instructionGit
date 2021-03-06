## Создание Git-репозитория

LICENSE: [MIT](./license.md)

![git-logo](./assets/logo.svg)

### **Текст**

---

#### Создание репозитория:

В командной строке вводим:

для Windows:

`$ cd C:/Users/user/my_project`

а затем выполните команду:

`$ git init`

#### Клонирование существующего репозитория

Клонирование репозитория осуществляется командой `git clone <url>`. Например, если вы хотите клонировать библиотеку `libgit2`, вы можете сделать это следующим образом:

`$ git clone https://github.com/libgit2/libgit2`

Эта команда создаёт директорию libgit2, инициализирует в ней поддиректорию .git, скачивает все данные для этого репозитория и извлекает рабочую копию последней версии. Если вы зайдёте в новую директорию `libgit2`, то увидите в ней файлы проекта, готовые для работы или использования. Для того, чтобы клонировать репозиторий в директорию с именем, отличающимся от `libgit2`, необходимо указать желаемое имя, как параметр командной строки:

`$ git clone https://github.com/libgit2/libgit2 mylibgit`

Эта команда делает всё то же самое, что и предыдущая, только результирующий каталог будет назван `mylibgit`.

***Читать полностью***[&#10149;](https://git-scm.com/book/ru/v2/%D0%9E%D1%81%D0%BD%D0%BE%D0%B2%D1%8B-Git-%D0%A1%D0%BE%D0%B7%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5-Git-%D1%80%D0%B5%D0%BF%D0%BE%D0%B7%D0%B8%D1%82%D0%BE%D1%80%D0%B8%D1%8F)

Более детально можно ознакомиться в видео:

[#4 Уроки Git+GitHub - Учим команды git clone, git status, git add, git commit и другие](https://www.youtube.com/watch?v=Pl0xwUicJDc&list=PLuY6eeDuleIOMB2R_Kky05ZfiAx2_pbAH&index=4&ab_channel=ITDoctor)

Видео взято с канала [ITDoctor](https://www.youtube.com/channel/UC2Ev-rDSHBov0ZMChesLfrg) в ознакомительных целях.

---

[вернуться &#8634;](./basics.md)

Git logo by http://git-scm.com/downloads/logos,
license: [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/)