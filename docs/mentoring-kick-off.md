# Менторинг. Регистрация и получение студентов

## 1. Регистрация в менторы
#### 1.1. Регистрация в RS APP
1. Чтобы стать ментором, необходимо заполнить форму - [app.rs.school/registry/mentor](https://app.rs.school/registry/mentor).
2. Через какое-то время после регистрации (от недели до нескольких месяцев) ментор получает ассаймент на курс.
На указанную вами почту (и/или телеграм аккаунт) придет сообщение с просьбой подтвердить регистрацию и приглашением на организационный вебинар.
Во время подтверждения регистрации менторы могут указать:
    - Пожелания по локации студентов (ваш город, страна, или рандомная локация).
    - Количество студентов, которое ментор хочет менторить.
    - Знакомых/друзей/коллег, которых ментор хочет менторить. Cледует помнить, что corejs interview, интервью в epam jslab они будут проходить у другого ментора / интервьювера, а некоторые задания проверяются через cross-check, jury и т.д. Если знакомого нет в списке, попросите его зарегистрироваться на курс - [app.rs.school/registry/student](https://app.rs.school/registry/student).
3. После подтверждения регистрации вы получите:
  - Доступ к менторскому чату
  - Информацию о вводном занятии для менторов

#### 1.2. Каналы для общения
- Telegram канал для менторов. Ссылку на канал вы получаете после подтверждения регистрации
- Еженедельный митинг для менторов. Проходит раз в неделю. Продолжительность 30 минут. Участие по желанию. Митинг записывается, конспект митинга сбрасывается в telegram. 
- [Чаты в которых общаются студенты. Discord и Telegram](https://docs.rs.school/#/rs-school-chats) 
- Закрытая группа активистов и менторов в Discord. Тут обсуждаем учебный процесс, платформу и все что связано с обучением в RS School. Как получить доступ к группе указано ниже.
- Получение роли ментора в Discord
  1. Открыть - https://app.rs.school/profile
  2. Авторизоваться через discord в блоке `Discord Integration`  
  3. Добавить название вашего Github в Discord ник https://docs.rs.school/#/rs-school-chats?id=discord
  4. Написать сообщение в Discord канал [#mentoring](https://discord.gg/fBvpUURPVm). Пример сообщения: "Hi everyone, my name is Juan and I'm a mentor from Colombia"

#### 1.3. Получение доступа к приватным студенческим репозиториям.
1. Все студенты работают с приватными репозиториями GitHub RS School https://github.com/rolling-scopes-school
2. Все менторы добавляются в отдельный GitHub Team.
Свой инвайт можно проверить тут - https://github.com/orgs/rolling-scopes-school/invitation
3. У менторов есть доступ ко всем репозиториям студентов этого курса.
4. По умолчанию ментора подписаны на все изменения в студенческих репозитория. Отписаться можно в настройках github (Profile>Settings>Notifications>Automatically watch repositories) или используя скрипт - https://github.com/Shastel/runsubscribe

#### 1.4. Знакомство с учебной программой и расписанием
Курс состоит из 4х этапов: подготовительного и трех основных. Ментора помогают студентам во время прохождения второго и третьего этапа. На каждый этап менторинга необходимо регистрироваться отдельно.  
Программа обучения:  
  - [Подготовительный этап. Студенты обучаются без помощи менторов.](https://github.com/rolling-scopes-school/tasks/tree/master/stage0)
  - [Первый этап обучения. Студенты обучаются без помощи менторов.](https://github.com/rolling-scopes-school/tasks/tree/master/stage1)
  - [Второй этап обучения. Менторинг.](https://github.com/rolling-scopes-school/tasks/tree/master/stage2)
  - Третий этап обучения. Менторинг. Студенты выбирают фреймворк:  
     - [React](https://github.com/rolling-scopes-school/tasks/tree/master/react)
     - [Angular](https://github.com/rolling-scopes-school/tasks/tree/master/angular)

## 2. Получение студентов
### 2.1. Алгоритм распределения студентов по менторам
#### Шаг #1 Ментора подтверждают регистрацию на курс
- Ментор подтверждает регистрацию на курс - https://app.rs.school/course/mentor/confirm?course={courseId}. 
- Во время подтверждения регистрации ментор: 
    - может записать к себе в группу знакомых/друзей/коллег, которых он хочет менторить.
    - указывает количество студентов, которое хочет менторить
    - оставляет пожелание по локации студентов
    - при необходимости, ментор может изменить данные параметры сабмитнув форму подтверждения повторно
#### Шаг #2 Выделение резерва менторов
- Происходит в день распределения студентов
- 20% менторов из числа подтвердивших регистрацию 
- Ментора выбираются рандомно
#### Шаг #3 Рандомное распределяем студентов по менторам
- Происходит в день распределения студентов
- Если у ментора остались свободные места, он получает рандомных студентов. 
    1. Если осталось одно свободное место - 2 рандомных студента
    2. Если осталось два или более мест - желаемое количество студентов плюс два.
- Для каждого ментора назначается минимум 4 интервью
- Учитываются пожелания менторов по локации студентов
	- Ментор и студенты из одного города 
	- Ментор и студенты из одной страны 
- Студенты разного уровня подготовки. (Например, первый по score, N по score,  2N по score и т.д.)
#### Шаг #4 Technical screening
1. Публикуем распределение. 
2. Студенты связываются с менторами. 
3. Ментора проводят Technical screening в течении двух недель со дня распределения студентов
#### Шаг #5 Troubleshooting
- Возможность для ментора сдать лишних студентов. Например, все оказались толковые, но всех учить он их не может
- Координаторы по локациям проверяют, что все активные студенты получили менторов 
- Возможность для ментора добрать студентов, вместо тех, кто не пришел на интервью 
- Студент передумал продолжать обучение или ушёл на short track после того, как рандомное распределение произошло
- После рандомного распределения, ментор написал, что не может принять участие в менторинге
- Обмен студентами между менторами. Например, по причине тайм зоны и т.д.
#### Шаг #6 Повторное распределение
Проводим распределение для менторов из резерва и тех менторов, которые присоединились к курсу после рандомного распределения

### 2.2. Добор студентов из листа ожидания.
1. Открываете https://app.rs.school/ 
2. Нажимаете "Interviews"
3. Нажимаете "Available students"
4. Нажимаете "Want To Interview"
5. Связываетесь со студентом сами (нотификаций они не получают). 
6. Если готовы брать студента без собеседования - сабмитаете пустую [фидбек форму](https://app.rs.school/course/mentor/interview-technical-screening?course=js-fe-2021Q3), в секции Resume выбирая "Yes, I do."

### 2.3. Совместный менторинг
Менторы могут объединиться и менторить студентов совместно. В данном случае студенты все равно привязаны к конкретному ментору, но задания студентов в объединенной группе менторы могу проверять как им удобно. Например, проверять задания и проводить митинги по очереди.

### 2.4. Джентльменское соглашение
Ментор имеют первоочередное право на хайринг студентов, которых он обучает, в свою компанию/проект/команду.

### Pay it forward
Школа работает по принципу "Pay it forward". Согласно этому принципу, мы ожидаем что студенты, отучившиеся в школе бесплатно, возвращаются в качестве менторов, чтобы передать свои знания следующему поколению студентов.
