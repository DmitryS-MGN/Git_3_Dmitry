## 1. Проверка наличия установленного Git

В терминале выполняем команду git version.
    
Если **git установлен**, то появляется **сообщение с информацией о версии файла**. **Иначе** будет **сообщение об ошибке**.

[![imageup.ru](https://imageup.ru/img208/4534243/git-version.png)](https://imageup.ru/img208/4534243/git-version.png.html)

## 2. Установка Git
 Загружаем последнюю версию с сайта - [Скачать Git](https://git-scm.com/downloads)

## 3. Настройка Git
При **первом использовании Git** необходимо **представиться**, для этого надо **ввести две команды**:

- git config --global user.name
- git config --global user.email

Для того чтобы **проверить прошла ли регистрация** надо **ввести команду**:

- git config --list

[![imageup.ru](https://imageup.ru/img282/4534257/git-config-list.jpg)](https://imageup.ru/img282/4534257/git-config-list.jpg.html)

## 4. Инициализация репозитория 

- Прописываем команду в терминал git init.

В исходной папке **появится скрытая папка** .git

[![imageup.ru](https://imageup.ru/img67/4534263/skrytaia-papka.jpg)](https://imageup.ru/img67/4534263/skrytaia-papka.jpg.html)

## 5. Проверка репозитория

- Прописываем команду в терминал git status

Если имеются **изменения**, которые **не отслеживаются в git** терминал выдаст следующее сообщение. 

[![imageup.ru](https://imageup.ru/img242/4534281/git-status.jpg)](https://imageup.ru/img242/4534281/git-status.jpg.html)

Если же **все изменения сохранены**

[![imageup.ru](https://imageup.ru/img105/4534283/git-status-2.jpg)](https://imageup.ru/img105/4534283/git-status-2.jpg.html)

## 6. Внесение изменений из рабочего каталога в раздел проиндексированных файлов.

- прописываем команду git add и имя проекта, через пробел, над которым вы работаете. 

[![imageup.ru](https://imageup.ru/img59/4534308/git-add.jpg)](https://imageup.ru/img59/4534308/git-add.jpg.html)

Если **изменения сохранены** и никаких **ошибок нет**, **будет выведена рабочая строка** терминала, как на скриншоте выше.

команда git add предшествует команде git commit.

## 7. Сохранение текущего состояния изменений 

- прописываем команду git commit -m "Записываем внесенные изменения"

[![imageup.ru](https://imageup.ru/img75/4534337/git-commit.jpg)](https://imageup.ru/img75/4534337/git-commit.jpg.html)

**git commit** можно рассматривать как команду, которая **создает контрольную точку проекта**.

## 8. Просмотр истории коммитов или журнала изменений проекта 

- прописываем команду git log

[![imageup.ru](https://imageup.ru/img47/4534345/git-log.jpg)](https://imageup.ru/img47/4534345/git-log.jpg.html)

В истории мы видим **cохраненные коммиты**, **кто и что сделал**.

Имя коммита или его номер выглядит так, **для открытия коммита достаточно использовать первые четыри символа**.

[![imageup.ru](https://imageup.ru/img142/4534349/git-log-2.jpg)](https://imageup.ru/img142/4534349/git-log-2.jpg.html)

**Для выхода из команды git log** и возврашения к рабочей строке терминала **наобходимо нажать Q**, что значит quit-выйти.

## 9. Проверка, просмотр и переключение между сохраненными коммитами 

- прописываем команду git checkout и номер коммита 

[![imageup.ru](https://imageup.ru/img113/4534352/git-checkout.png)](https://imageup.ru/img113/4534352/git-checkout.png.html)

Как мы видим, нас переключило на коммит под номером 5d87 **switching to 5d87**, это коммит более ранней версии проекта.

[![imageup.ru](https://imageup.ru/img220/4534357/git-checkout-master.jpg)](https://imageup.ru/img220/4534357/git-checkout-master.jpg.html)

**Для возврашения** к основной ветке коммита **прописываем** команду **git checkout master**