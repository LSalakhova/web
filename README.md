# Тестирование веб-приложений

1. [Тест-план для приложения "Интернет-магазин"](https://docs.google.com/spreadsheets/d/1o3obMZyl4Jc1viXWQFOAxKv5AI2XAGo5AFfvmCuNixU/edit?gid=0#gid=0)
2. [Чек-лист для всех разделов](https://docs.google.com/spreadsheets/d/1-YO5gSBaxfIakPl1U3Bl-hCXl2MueUJP5IuauvX2_Fo/edit?gid=0#gid=0)

    В ранее созданный Чек-Лист для тестирования интернет-магазина "Demoshopping.ru" были добавлены такие разделы, как "Корзина" и "Оформление заказов".
   
3. [Тест-кейсы: все разделы](https://app.qase.io/project/G9?author=304) 

   Дополнение ранее созданных Тест-Кейсов 10-ю новыми для каждого из следующих разделов интернет-магазина: "Корзина" и "Оформление заказов".
   [Тест-кейсы QASE.pdf](https://github.com/user-attachments/files/18341969/-.QASE.pdf)

4. В ходе работы с Тест-Кейсами на платформе Qase и созданными ранее Чек-Листами для разделов "Корзина", "Оплата" и "Оформление заказов", были выявлены дефекты и созданы отчеты на платформе Youtrack:

    * [Результаты тестового прогона из QASE](https://github.com/user-attachments/files/18347291/Liaisan.Salakhova.Test.run.results.QASE.pdf)


    * [Отчеты о дефектах из Youtrack](https://github.com/user-attachments/files/18347293/Liaisan.Salakhova.Defect.reports.from.Youtrack.2.xlsx)

5. [Charles Proxy. Изменение количества товаров в корзине](https://drive.google.com/file/d/1zQObnQsXon5AHmtV-zgSyz4ajpHp7f-m/view?usp=sharing)

   Перехват и модификация запроса на изменение количества товаров. Например, вместо отправки запроса на "1 товар", был отправлен запрос на "500 товаров".

6. [Charles Proxy. Симуляция ошибки 403](https://drive.google.com/file/d/1MqaoHw6rL_Qqjv1d-pqMZ_y1ciUXLqCZ/view?usp=sharing)

   Настроен перехват запросов при котором при обращении к https://demoshopping.ru сервер вернет статус-код 403. При этом запросы к другим ресурсам работают в штатном режиме.
7. [Charles Proxy. Перенаправление запросов с Prod на QA](https://drive.google.com/file/d/1JUp1z8F5lKrrEsd7QlZz0RFMFEpx1Ul_/view?usp=sharing)

    Конфигурация Charles Proxy для перенаправления запросов с окружения Prod на QA.




