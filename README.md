Модуль для cs-cart 4.x
=====

Установка
----
Для установки модуля оплаты необходимо:

1. Зайти в панель управления Вашего магазина;

2. Перейти на страницу Модули->Управление модулями (/admin.php?dispatch=addons.manage);

3. Загрузить архив с модулем оплаты;

4.Добавить новый способ оплаты на странице Администрирование/Способы оплаты (/admin.php?dispatch=payments.manage):
- На вкладке "Общее" заполнить:
   1. Название -- Банковской картой Visa/Mastercard; 
   2. Процессор -- Alliance bank;
- Hа вкладке "Настройки" заполните:
   1. Merchant ID -- идентификатор мерчанта; 
   2. Пароль -- секретный ключ мерчанта;
   3. Валюта -- валюта мерчанта;
   4. Transaction method -- Продажа/hold
   5. Статусы заказа
	
5.Нажать кнопку "Создать";

При выбраном режиме холдирования, списание средст происходит при смене "статуса заказа с замороженными средствами" на выбраный "статсу оплаченого заказа"


![Скриншот][1]
----

[1]: https://raw.githubusercontent.com/cloudipsp/cscart/master/Screenshot_1.png