# Проект по автоматизации тестирования API + UI для веб-приложения [Demowebshop](http://demowebshop.tricentis.com)

* Автоматизируем проверку ui-взаимодействия по api
* Добавляем Allure-listener
* Добавляем шаблоны для более красивого отчета в Allure Report 
* Логируем детализацию запросов в лог 
* Используем спецификации

## ✔ Покрытый функционал
  ### ➤  API
  * Запросы `GET`, `POST`
  * Отображение `statusCode` и `body` в ответе запроса
  * Успешная генерация токена
1. Добавление товара в Wishlist без использования cookie
2. Добавление товара в Wishlist c использованием cookie
3. Проверка функции поиска  


### ➤ API+UI  

1. Удаление товара из Wishlist c использованием cookie
2. Проверка информации в аккаунте

## 🚀 Зупуск теста локально
Необходимо создать файл `credential.properties`, в котором указать:
- `cookie` (Nop.customer)
- `login` и `password` от учётной записи на сайте http://demowebshop.tricentis.com
- `firstName`, `lastName`, `email` - данные указанные в профиле

## 🚀 Конфигурация Job в Jenkins
* Открыть сборку [Jenkins](https://jenkins.autotests.cloud/job/009_qaguru_j_unicorn_hw19_Demowebshop)
* Нажать **"Собрать с параметрами"**.
* Указать необходимые параметры.
* Нажать на кнопку "Собрать".

<img src="https://user-images.githubusercontent.com/93325839/155039519-6c4ca2b3-6109-4868-8438-8395dc336bb5.png" />  

## 📑 Отчет о результатах тестирования в Allure Report
![image](https://user-images.githubusercontent.com/93325839/151679382-de399d64-43fc-43f5-9065-073c0b1eb228.png)
![image](https://user-images.githubusercontent.com/93325839/155040626-6d6e0dcb-b755-48ec-9852-d79655522fe4.png)

## 🎦 Видео прохождения тестов в Selenoid
https://user-images.githubusercontent.com/93325839/151679836-ea4c78c6-6329-484e-9af2-1a8a6e65cf52.mp4

## 💫 Интеграция тестов c тест-менеджмент системой [Allure TestOps](https://allure.autotests.cloud/project/935/dashboards/1787)  

![image](https://user-images.githubusercontent.com/93325839/151679452-62846ea8-3288-4a9e-9584-e8b3641b6ced.png)
![image](https://user-images.githubusercontent.com/93325839/155040348-a73adcdf-7c9b-4665-9572-37eeac53ae7c.png)  

## 💫 Интеграция тестов c таск-трекер системой [Jira](https://jira.autotests.cloud/browse/HOMEWORK-349)  

<img src="https://user-images.githubusercontent.com/93325839/155040237-df5930e6-3b1d-4611-ac8f-a60047e1f3c5.png" />  

## 💫 Уведомления о прохождении тестов в Telegram 
![image](https://user-images.githubusercontent.com/93325839/151679601-7b8647ef-9e33-48b0-9ea7-7aeaa702b5dc.png)
