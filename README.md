Сайт для строительной компании с показом недвижки в наличии, поиском с фильтрами, скорее всего с регистрацией, саппорт, акциями

# 1. Цель проекта 
Создать сайт для строительной компании. Где компания сможет выставлять свои проекты на просмотр для клиентов и если клиент заинтересован он сможет записаться на прием 
от работников компании (далее админ). На сайте будет возможность проконсультироваться с админами. Также будут предусмотрены акции и система лоялности для постоянных и 
привелегиозных клиентов. 

# 2. Описание системы
Система будет состоять из этих основных функционалов:
1. Функционал главной страницы
2. Функционал регистрации и авторизации
3. Фукнционал для админов
4. Функционал для клинетов 
5. Функционал системы лояльности
6. Функционал для консультаций

## 2.0. Типы пользователей
Всего будет 3 вида пользователей:
1. Админ
2. Клиент
3. Гость

Админ - это работник строительной компании занимающийся сайтом.

Клиент - это пользователь зарегистрированный в системе и возможно имеет какую то степень лояльности.

Гость - это пользователь который еще не зарегистрирован и хочет посмотреть что компания предлагает клинетам.

Единственное отличие гостей от клиентов это то что клинеты имеют личный кабинет и имеют право оставить запрос 

## 2.1. Функционал главной страницы
Главная страница будет состоять из следующих элементов:
1. Страница проектов
2. Страница для акций
3. Страница для описания компании
### 2.1.1. Страница проектов
Данная страница будет заполнена листом кратких описаний проектов которые компания предоставляет для клиентов:
1. Фото проекта
2. Название
3. Количество планировок
4. Начальная цену
5. Средняя цена за определенный тип планировок 

Эта информация будет представляться в виде коробки и на ней будут кнопки ведущие в большее описание проекта.

Также для этих боксов будет свой фильтр в котором будет сортировка по:
1. Городу постройки
2. Типу недвижимости
3. Количеству комнат
4. Цене

### 2.1.2. Страница акций
В данной странице будут выставлены различного рода акции компании. Например, сезонные скидки, акции для определенного города, типа недвижимости или проекта и тд.

Эта страница будет также будет заполнена листом боксов которые будут кнопками перекидывающие на страницу акции, в которой будет полное описание акции.

### 2.1.3. Страницв описания компании
Эта страница будет описывать цель, ценности, краткое описание компании и описание системы лояльности установленной для постоянных клиентов.

## 2.2. Функционал регистрации и авторизации
В этой части система будет запрашивать пользователя ввести номер телефона или электронную почту. Если номер телефона или электронная почта имеется в базе данных, то 
система запросит пароль, в обратном случае выдаст ошибку и попросит зарегистрироваться в системе. 

При регистрации система запросит номер телефона, если номер телефона есть в базе данных то система даст ошибку и попросит авторизоваться, далее будет отправлено СМС на
предоставленный номер телефона и попросит гостя ввести код чтобы подтвердить номер телефона. Далее система попросит следующюю информацию:
1. Имя
2. Фамилия
3. Электронная почта
4. Придуманный пароль
5. Подтверждение пароля

После сохранения в базе данных данной информации регистрация прошла успешно.

## 2.3. Функционал для админов
После авторизации админы будут иметь доступ к:
1. Редактированию существующих проектов 
2. Добавлению новых проектов
3. Всем записям от клинетов чтобы выходить на связь с ними
4. Всем чатам консультации в которых клиенты просят помощь у работников компании

## 2.4. Функционал для клиента
У клиентов на сайте будет свой личный кабинет в котором они могут увидеть и редактировать свои данные. 
Клиенты на сайте смогут просматривать все интересующие их предложения которые компания предлагает для них. 
Они смогут помечать проекты приглянувшиеся им и позже смотреть список этих проектов в отдельной странице.
В страницах проектов в конце будет возможность оставить заявку, после чего с ними свяжутся работники компании. 

## 2.5. Функционал системы лояльности
Постоянные клиенты будут получать определенные привилегии как: скидки, кэшбек, приоритет в случае если мест ограничено. 

## 2.6. Функционал службы поддержки 
Служба поддержки будет состоять из часто задаваемых вопросов и из чата между админами и клиентами.
