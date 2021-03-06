---
lang: ru
layout: article_with_sidebar
updated_at: '2018-01-08 11:55 +0400'
title: Настройка авторизации через Facebook
order: 20
published: true
identifier: ref_fblogin
---
Чтобы в магазине появилась кнопка **Войти через Facebook**, понадобится:

1.  Настроенное [приложение Facebook](#как-создать-приложение-в-facebook). 
2.  _Идентификатор приложения_ и _Секрет приложения_ для [настройки модуля Social Login](#настройка-модуля-social-login-и-facebook) в X-Cart.

## Как создать приложение в Facebook

1.  Авторизуйтесь в [Facebook для разработчиков](https://developers.facebook.com/apps).

2.  Нажмите **Создать приложение**:
    ![2.jpg]({{site.baseurl}}/attachments/ref_fblogin/2.jpg)

    Откроется окно **Создайте новый ID приложения**.
    ![18.jpg]({{site.baseurl}}/attachments/ref_fblogin/18.jpg)
    
3.	В поле **Отображаемое название** укажите название приложения. Его увидят пользователи, поэтому рекомендуется включить в него название магазина. 
	В поле **Эл. адрес для связи** напишите адрес электронной почты, который вы будете использовать для переписки касательно приложения. Нажмите **Создайте ID приложения**.
    
4.  Откроется новое окно **Проверка безопасности**. Введите код с картинки и нажмите **Отправить**. 
    ![4.jpg]({{site.baseurl}}/attachments/ref_fblogin/4.jpg)

5.  Откроется страница выбора нового товара. Наведите курсор на **Вход через Facebook** и нажмите **Настроить**:
	![5.jpg]({{site.baseurl}}/attachments/ref_fblogin/5.jpg)
    
6.  Выберите платформу:
	![6.jpg]({{site.baseurl}}/attachments/ref_fblogin/6.jpg)
    
    Запускается мастер настройки нового приложения.

7.  На первом шаге настройки укажите веб-адрес сайта, нажмите **Save** и **Продолжить**:
    ![7.jpg]({{site.baseurl}}/attachments/ref_fblogin/7.jpg)
        
8.  Последующие шаги можно пропустить, т.к. они настраиваются модулем **Social Login**.
	![8.jpg]({{site.baseurl}}/attachments/ref_fblogin/8.jpg)

9.	На странице **Настройки** заполните поля **URL-адрес политики конфиденциальности** и **URL-адрес Пользовательского соглашения** (это ссылки на соответствующие страницы в магазине), и выберите категорию приложения **Бизнес и Страницы**. Нажмите **Сохранить изменения**:
    ![10.jpg]({{site.baseurl}}/attachments/ref_fblogin/10.jpg)
     
10.  Пока приложение находится на стадии разработки, оно не действует на сайте. Перейдите на страницу **Проверка приложения** и сделайте приложение доступным для всех:
    ![11.jpg]({{site.baseurl}}/attachments/ref_fblogin/11.jpg)
    
    Подтвердите действие:
    ![12.jpg]({{site.baseurl}}/attachments/ref_fblogin/12.jpg)

    Приложение опубликовано:
    ![13.jpg]({{site.baseurl}}/attachments/ref_fblogin/13.jpg)

    Настройка приложения завершена.

## Настройка модуля Social Login и Facebook

Откройте панель управления X-Cart в новой вкладке или новом окне браузера, чтобы легко переключаться между магазином и **Facebook**.

1.  На странице **Мои модули** найдите модуль **Social login**:
    ![14.jpg]({{site.baseurl}}/attachments/ref_fblogin/14.jpg)
    
    Откройте настройки модуля:
    ![15.jpg]({{site.baseurl}}/attachments/ref_fblogin/15.jpg)
    
2. Скопируйте **Идентификатор приложения** и **Секрет приложения** со страницы **Панель** в **Facebook**. Для просмотра секрета нажмите **Показать**, введите свой пароль для **Facebook** и нажмите **Отправить**
     ![9.jpg]({{site.baseurl}}/attachments/ref_fblogin/9.jpg)

Заполните поля **Facebook App ID/API Key** (Идентификатор приложения) и **Facebook App Secret** (Секрет приложения)
     ![16.jpg]({{site.baseurl}}/attachments/ref_fblogin/16.jpg)
   
Включите или отключите опцию **Request user location**. Для чего она нужна: модуль **Social login** запрашивает информацию о местонахождении пользователя, на получение которой требуется подтверждение от **Facebook**. Если пользователь указал свое местонахождение в профиле в **Facebook** и X-Cart получил эту информацию, при авторизации покупателя в магазине его адрес подставляется автоматически.

3.  Когда все данные **Facebook** внесены, нажмите **Сохранить**.

    Теперь на странице входа в магазин покупатели увидят кнопку **Войти через Facebook**.
     ![17.jpg]({{site.baseurl}}/attachments/ref_fblogin/17.jpg)

_Дополнительная информация:_

*   {% link "Авторизация через соцсети" ref_sociallogin %}
*   {% link "Настройка авторизации через Google+" ref_glogin %}
